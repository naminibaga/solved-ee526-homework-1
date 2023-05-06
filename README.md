Download Link: https://assignmentchef.com/product/solved-ee526-homework-1
<br>
There is a ground-truth model

<table width="0">

 <tbody>

  <tr>

   <td width="603">                                                                            <em>y </em>= <em>f</em>(<em>x</em>) + <em>ǫ,        </em>0 ≤ <em>x </em>≤ 1<em>,</em>where</td>

   <td width="21">(1)</td>

  </tr>

  <tr>

   <td width="603"><em>f</em>(<em>x</em>) = 1 + 2sin(5<em>x</em>) − sin(15<em>x</em>)</td>

   <td width="21">(2)</td>

  </tr>

 </tbody>

</table>

and <em>ǫ </em>is additive noise that is Gaussian distributed with zero mean and unit variance. The added noises for different <em>x </em>values are independent.

Using this model, we would like to test polynomial fitting. Specifically,

(a) Generate 51 equally spaced <em>x </em>values between 0 and 1:

<em>.                                              </em>(3)

<table width="0">

 <tbody>

  <tr>

   <td width="329">(b) Generate <em>y<sub>i </sub></em>values for these <em>x<sub>i </sub></em>values:</td>

   <td width="264"> </td>

   <td width="21"> </td>

  </tr>

  <tr>

   <td width="329"><em>y<sub>i </sub></em>= <em>f</em>(<em>x<sub>i</sub></em>) + <em>ǫ<sub>i</sub>,</em></td>

   <td width="264"><em>i </em>= 0<em>,</em>1<em>,…,</em>50<em>.</em></td>

   <td width="21">(4)</td>

  </tr>

 </tbody>

</table>

where <em>ǫ<sub>i </sub></em>are independently and identically distributed standard Gaussian random variables. The set of generated values (<em>x<sub>i</sub>,y<sub>i</sub></em>)<em>,i </em>= 0<em>,…,</em>50, will serve as the training data.

<ul>

 <li>Fit a polynomial of order <em>k </em>= 1 to the dataset, minimizing the residual sum of squares. Plot the fitted polynomial using black color.</li>

 <li>Repeat the steps (b) to (c) 30 times. Keep all the plotted polynomials.</li>

 <li>Repeat the experiment for <em>k </em>= 3<em>,</em>5<em>,</em>7<em>,</em>9<em>,</em> For each <em>k</em>, use a new figure. Also, on each figure, show the function <em>f</em>(<em>x</em>) using red color.</li>

</ul>

You need to write the code using Python. You should implement the polynomial fitting function (see the “Linear Regression” lecture notes). You will be graded based on two artifacts: 1) the figures generated (need to be included in the submitted homework report), and 2) the source code submitted.

<strong>Problem 2. </strong>Use Python to implement the perceptron algorithm and test it on the following data:

Page 1 of 2

where there are 6 points, (<em>x</em><sub>1</sub><em>,x</em><sub>2</sub>) is the input, and <em>y </em>is the binary output label. Initialize your algorithm with the vector

<em>θ </em>= [<em>b,w</em><sub>1</sub><em>,w</em><sub>2</sub>]<em><sup>T </sup></em>= [0<em>,</em>0<em>,</em>0]<em><sup>T</sup>.                                                    </em>(5)

Plot the points and the final hyperplane (a line) on the same graph.

<strong>Problem 3. </strong>The Spambase Data Set contains email spam data for 4601 email messages. Download the data from <a href="https://archive.ics.uci.edu/ml/datasets/spambase">https://archive.ics.uci.edu/ml/datasets/spambase</a> and divide the data into training set and test set. The training set should contain the first 2/3 of spam messages and first 2/3 of ham (i.e., non-spam) messages. The test set should contain the last 1/3 spam messages and last 1/3 ham messages.

<ul>

 <li>Write a logistic regression program (function) using gradient descent algorithm. Andtrain the weights using training set and then test the result on the test set. Experiment with the step size (learning rate).</li>

 <li>Next, normalize the features, so that each feature in the training data has mean 0 andvariance 1. Then run logistic regression on the normalized data.</li>

</ul>

You should perform the simulation using Python.

You need to submit in the homework report a summary of the results you obtained, and the results on the learning rate used, and training and test errors. Source code in Python should also be submitted.

END OF ASSIGNMENT

Page 2 of 2