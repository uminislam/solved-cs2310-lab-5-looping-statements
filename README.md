Download Link: https://assignmentchef.com/product/solved-cs2310-lab-5-looping-statements
<br>
Please test the correctness of your programs in Q-1, Q-2 and Q-3 using PASS.

<strong><u>Q-1.</u></strong><em> </em>

Write a program which reads a positive integer n and outputs all the factors of n, total factors and sum of factors. A number i is a factor of n if i divides n, and 1&lt;i&lt;n.




Let’s use <strong>for-loop</strong> in your program.




<strong>Hint:</strong> Write a <strong>for-loop</strong> with an integer counter i. In each iteration, check if n is divisible by i (one way to perform such check is to use the <strong>modulo operator</strong>).

<em> </em>

<strong><u>Expected Output:</u></strong>

<strong><em> </em></strong>

<table width="0">

 <tbody>

  <tr>

   <td width="289">Example 1</td>

   <td width="318">Example 2</td>

  </tr>

  <tr>

   <td width="289">Enter a Number in Range [2 to N]: <u>-10</u> <em> </em>Error! Input can’t be a negative number.</td>

   <td width="318">Enter a Number in Range [2 to N]: <u>17</u>No Factor for the Number 17Total Factors are: 0Sum of Factors is: 0</td>

  </tr>

  <tr>

   <td width="289">Example 3</td>

   <td width="318">Example 4</td>

  </tr>

  <tr>

   <td width="289">Enter a Number in Range [2 to N]:<u>0</u>Error! Input can’t be zero.</td>

   <td width="318">Enter a Number in Range [2 to N]:<u>1</u>Error! Input can’t be one.</td>

  </tr>

  <tr>

   <td width="289">Example 5</td>

   <td width="318">Example 6</td>

  </tr>

  <tr>

   <td width="289">Enter a Number in Range [2 to N]: <u>12</u>The Factor(s) of 12 are: 2 3 4 6Total Factors are: 4Sum of Factors is: 15 </td>

   <td width="318">Enter a Number in Range [2 to N]:<u>2</u>No Factor for the Number 2Total Factors are: 0Sum of Factors is: 0 </td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<em>NOTE: Your program MUST follow the EXACT input/output format! Otherwise, you may not pass the test cases even your calculation is correct.</em>







<strong><u>Q-2.</u></strong>

<em> </em>

Write a program which reads numbers until -999 is entered and compute the following.

<ol>

 <li>How many positive numbers are entered?</li>

 <li>How many negative numbers are entered?</li>

 <li>How many zeros are entered?</li>

 <li>Sum of positive numbers</li>

 <li>Sum of negative numbers</li>

 <li>Average of positive numbers</li>

</ol>




Hints:  1) Exclude -999 from all computations.

2) Use <strong>while-loop</strong> in your program.




<strong><em> </em></strong>

<strong><u>Expected Output:</u></strong>

<strong><em> </em></strong>

<table width="0">

 <tbody>

  <tr>

   <td width="289">Example 1</td>

   <td width="348">Example 2</td>

  </tr>

  <tr>

   <td width="289">Enter Numbers! Enter -999 to Stop:<em> </em><em> </em><em> </em><u>-999</u>Total Positive Numbers are: 5Total Negative Numbers are: 3Total Zeros are: 2Sum of Positive Numbers is: 15Sum of Negative Numbers is: -6Average of Positive Numbers is: 3 </td>

   <td width="348">Enter Numbers! Enter -999 to Stop:<u>-999</u>Total Positive Numbers are: 0Total Negative Numbers are: 0Total Zeros are: 0Sum of Positive Numbers is: 0Sum of Negative Numbers is: 0Average of Positive Numbers is: 0</td>

  </tr>

  <tr>

   <td width="289">Example 3</td>

   <td width="348">Example 4</td>

  </tr>

  <tr>

   <td width="289">Enter Numbers! Enter -999 to Stop:<em> </em>Total Positive Numbers are: 0Total Negative Numbers are: 7Total Zeros are: 2Sum of Positive Numbers is: 0Sum of Negative Numbers is: -17Average of Positive Numbers is: 0 </td>

   <td width="348">Enter Numbers! Enter -999 to Stop:<em> </em>Total Positive Numbers are: 4Total Negative Numbers are: 3Total Zeros are: 2Sum of Positive Numbers is: 10Sum of Negative Numbers is: -7Average of Positive Numbers is: 2.5</td>

  </tr>

 </tbody>

</table>

<em> </em>




























<strong><u>Q-3. (to be marked)</u></strong>

<em> </em>

Write a program to produce a square matrix with 0’s down the main diagonal, 1’s in the entries just above and below the main diagonal, 2’s above and below that, etc.

<ul>

 <li>1 2 3 4</li>

 <li>0 1 2 3</li>

 <li>1 0 1 2</li>

 <li>2 1 0 1</li>

 <li>3 2 1 0</li>

</ul>







<table width="0">

 <tbody>

  <tr>

   <td width="289">Example 1</td>

   <td width="348">Example 2</td>

  </tr>

  <tr>

   <td width="289">Enter the number of rows: <u>5</u>0  1 2 3 41  0 1 2 32  1 0 1 23  2 1 0 14  3 2 1 0</td>

   <td width="348">Enter the number of rows: <u>8</u>0        1 2 3 4 5 6 71        0 1 2 3 4 5 62        1 0 1 2 3 4 53        2 1 0 1 2 3 44        3 2 1 0 1 2 35        4 3 2 1 0 1 26        5 4 3 2 1 0 1                              7 6 5 4 3 2 1 0</td>

  </tr>

  <tr>

   <td width="289">Example 3</td>

   <td width="348">Example 4</td>

  </tr>

  <tr>

   <td width="289">Enter the number of rows: <u>0</u>Please enter positive integer.</td>

   <td width="348">Enter the number of rows: <u>3</u>0  1 21  0 12  1 0</td>

  </tr>

 </tbody>

</table>


