Download Link: https://assignmentchef.com/product/solved-stat40001_59800-homework-1
<br>
<strong>Q.N. 1) </strong>Calculate the following numerical results to the three decimal places

<ol>

 <li>a) <strong>ln3 + </strong>√<strong>2sin(</strong>π<strong>) </strong>− e<strong><sup>3</sup></strong></li>

</ol>

b)

<ol>

 <li><strong>ln5</strong>÷− <strong>exp(2) + 2</strong>× −√ −</li>

 <li><strong>(9 2)           4             10 + ln6              exp(1)</strong></li>

 <li><strong>log14 + ln14 + (47</strong>mod <strong>5)</strong></li>

</ol>

<strong>Q.N. 2) </strong>Create the following vectors using rep function:

V1= 1 2 3 4 5 1 2 3 4 5 1 2 3 4 5 1 2 3 4 5

V2= 1 1 1 1 2 2 2 2 3 3 3 3 4 4 4 4 5 5 5 5

V3= MATH, MATH, STAT, STAT, STAT, STAT, STAT, ECE, ECE, ECE, BIO, BIO

<strong>Q.N. 3) </strong>An article entitled ”What Does It Take to Heat a New Room? Estimating Utility Demand in a Home” by Robert Carver was published in the Journal of Statistics Education v.6, n.1 (1998). It has been observed that in a residential home, energy consumption is closely related to the outdoor temperature and size of the house. The date collected for this study are provided in the link below:

http://jse.amstat.org/datasets/utility.dat.txt

a)Import the data in R

b)How many variables are included in this dataset?

c)The missing values in this dataset are denoted by ∗. Please create a clean dataset by removing the missing vales.

<strong>Q.N. 4)</strong>The Fibonacci sequence is a famous sequence in mathematics. The first two elements are defined as [1, 1]. Subsequent elements are defined as the sum of the preceding two elements. For example, the third element is 2 (= 1+1), the fourth element is 3 (= 1+2), the fifth element is 5 (= 2+3), and so on.Print first 50 Fibonacci numbers.

Hint: To obtain the first 10 Fibonacci numbers in R, we can use

&gt; Fibonacci &lt;- numeric(10)

&gt; Fibonacci[1] &lt;- Fibonacci[2] &lt;- 1

&gt; for (i in 3:10) Fibonacci[i] &lt;- Fibonacci[i – 2] + Fibonacci[i – 1] &gt; Fibonacci

1

<strong>Q.N. 5) </strong>Use R to solve the following system of equations:

<table width="243">

 <tbody>

  <tr>

   <td width="196"><strong>2</strong>x<strong><sub>1 </sub>+ </strong>x<strong><sub>2 </sub>+ </strong>x<strong><sub>3</sub></strong>− <strong>3</strong>x<strong><sub>4 </sub>+ </strong>x<strong><sub>5</sub></strong></td>

   <td width="48"><strong>= 12</strong></td>

  </tr>

  <tr>

   <td width="196">x<strong><sub>1</sub></strong>− x<strong><sub>2 </sub>+ 2</strong>x<strong><sub>3 </sub>+ </strong>x<strong><sub>4</sub></strong>− x<strong><sub>5</sub></strong></td>

   <td width="48"><strong>= 1</strong></td>

  </tr>

  <tr>

   <td width="196"><strong>2</strong>x<strong><sub>1 </sub>+ </strong>x<strong><sub>2</sub></strong>− x<strong><sub>3 </sub>+ 2</strong>x<strong><sub>4 </sub>+ </strong>x<strong><sub>5</sub></strong></td>

   <td width="48"><strong>= </strong>−<strong>2</strong></td>

  </tr>

  <tr>

   <td width="196">x<strong><sub>1</sub></strong>− <strong>3</strong>x<strong><sub>2 </sub>+ </strong>x<strong><sub>3 </sub>+ 2</strong>x<strong><sub>4</sub></strong>− x<strong><sub>5</sub></strong></td>

   <td width="48"><strong>= </strong>−<strong>9</strong></td>

  </tr>

  <tr>

   <td width="196">x<strong><sub>1 </sub>+ 2</strong>x<strong><sub>2</sub></strong>− x<strong><sub>3 </sub>+ 3</strong>x<strong><sub>4</sub></strong>− x<strong><sub>5</sub></strong></td>

   <td width="48"><strong>= 0</strong></td>

  </tr>

 </tbody>

</table>

<strong>Q.N. 6) </strong>Create the following matrix (M) with the column and row names (Note that the numbers are in sequence from 1 to 20)

&gt;M column-1 column-2 column-3 column-4 column-5

<table width="435">

 <tbody>

  <tr>

   <td width="153">Experiment.1</td>

   <td width="69">1</td>

   <td width="61">5</td>

   <td width="69">9</td>

   <td width="69">13</td>

   <td width="15">17</td>

  </tr>

  <tr>

   <td width="153">Experiment.2</td>

   <td width="69">2</td>

   <td width="61">6</td>

   <td width="69">10</td>

   <td width="69">14</td>

   <td width="15">18</td>

  </tr>

  <tr>

   <td width="153">Experiment.3</td>

   <td width="69">3</td>

   <td width="61">7</td>

   <td width="69">11</td>

   <td width="69">15</td>

   <td width="15">19</td>

  </tr>

  <tr>

   <td width="153">Experiment.4</td>

   <td width="69">4</td>

   <td width="61">8</td>

   <td width="69">12</td>

   <td width="69">16</td>

   <td width="15">20</td>

  </tr>

 </tbody>

</table>

<ol>

 <li>Determine the dimension of the matrix M</li>

 <li>Select the first two row of the matrix M</li>

 <li>Calculate the sum of all columns of the matrix M</li>

 <li>Calculate the sum of all rows of the matrix M</li>

 <li>Use “sample” to shuffle the elements of each row of the matrix M</li>

</ol>

<strong>Q.N. 7) </strong>Test scores of Fifteen students in Test 1 and Test 2 are presented below

<table width="149">

 <tbody>

  <tr>

   <td width="43">S.N.</td>

   <td width="55">Test 1</td>

   <td width="50">Test2</td>

  </tr>

  <tr>

   <td width="43">1</td>

   <td width="55">56</td>

   <td width="50">86</td>

  </tr>

  <tr>

   <td width="43">2</td>

   <td width="55">78</td>

   <td width="50">67</td>

  </tr>

  <tr>

   <td width="43">3</td>

   <td width="55">87</td>

   <td width="50">78</td>

  </tr>

  <tr>

   <td width="43">4</td>

   <td width="55">89</td>

   <td width="50">89</td>

  </tr>

  <tr>

   <td width="43">5</td>

   <td width="55">95</td>

   <td width="50">87</td>

  </tr>

  <tr>

   <td width="43">6</td>

   <td width="55">98</td>

   <td width="50">67</td>

  </tr>

  <tr>

   <td width="43">7</td>

   <td width="55">NA</td>

   <td width="50">94</td>

  </tr>

  <tr>

   <td width="43">8</td>

   <td width="55">78</td>

   <td width="50">78</td>

  </tr>

  <tr>

   <td width="43">9</td>

   <td width="55">87</td>

   <td width="50">81</td>

  </tr>

  <tr>

   <td width="43">10</td>

   <td width="55">98</td>

   <td width="50">83</td>

  </tr>

  <tr>

   <td width="43">11</td>

   <td width="55">54</td>

   <td width="50">78</td>

  </tr>

  <tr>

   <td width="43">12</td>

   <td width="55">89</td>

   <td width="50">NA</td>

  </tr>

  <tr>

   <td width="43">13</td>

   <td width="55">78</td>

   <td width="50">93</td>

  </tr>

  <tr>

   <td width="43">14</td>

   <td width="55">98</td>

   <td width="50">98</td>

  </tr>

  <tr>

   <td width="43">15</td>

   <td width="55">97</td>

   <td width="50">100</td>

  </tr>

 </tbody>

</table>

<ol>

 <li>How many students have their test 1 score greater than 80 ?</li>

 <li>How many students have their test 2 score greater than 85 ?</li>

</ol>

2

<ol>

 <li>Did all fifteen students take both tests?</li>

 <li>How many students did better in the second test than the first test?</li>

 <li>How many students have the same score in the first and second test?</li>

</ol>