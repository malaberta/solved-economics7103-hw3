Download Link: https://assignmentchef.com/product/solved-economics7103-hw3
<br>
You have access to imaginary data on an energy-efficiency retrofit program in Atlanta <em>kwh.csv </em>(the same as the previous homework) and you are interested in whether the program reduced energy use. In your dataset is the following information: After recruiting the households for the program, you assigned them to

<table width="560">

 <tbody>

  <tr>

   <td width="73">Variable</td>

   <td width="487">Description</td>

  </tr>

  <tr>

   <td width="73"><em>electricity</em></td>

   <td width="487">kWh of electricity used by the household in the month</td>

  </tr>

  <tr>

   <td width="73"><em>sqft</em></td>

   <td width="487">Square feet of the home</td>

  </tr>

  <tr>

   <td width="73"><em>retrofit</em></td>

   <td width="487">= 1 if the home received a retrofit</td>

  </tr>

  <tr>

   <td width="73"><em>temp</em></td>

   <td width="487">The outdoor average temperature (<sup>◦ </sup>F) during the month at the home’s location</td>

  </tr>

 </tbody>

</table>

Table 1: Variable descriptions for homework 3.

treatment and control groups. Treatment homes received the retrofits on the first of the month and control homes did not have any work done.

<ol>

 <li>Suppose that for a home <em>i</em>, you think the underlying relationship between electricity use and predictor variables is <em>y<sub>i </sub></em>= <em>e<sup>α</sup>δ<sup>d</sup></em><em><sup>i</sup>z<sub>i</sub><sup>γ</sup>e<sup>η</sup></em><em><sup>i </sup></em>where <em>e </em>is Euler’s number or the base of the natural logarithm, <em>d<sub>i </sub></em>is a binary variable equal to one if home <em>i </em>received the retrofit program, <em>z<sub>i </sub></em>is a vector of the other control variables, <em>η<sub>i </sub></em>is unobserved error, and {<em>α,δ,γ</em>} are parameters to estimate.</li>

</ol>

(a) Show that <em>ln</em>(<em>y<sub>i</sub></em>) = <em>α </em>+ <em>ln</em>(<em>δ</em>)<em>d<sub>i </sub></em>+ <em>γln</em>(<em>z<sub>i</sub></em>) + <em>η<sub>i </sub></em>(b) What is the intuitive interpretation of <em>δ</em>?

<ul>

 <li>Show that . What is the intuitive interpretation of ?</li>

 <li>Show that . What is the intuitive interpretation of when <em>z<sub>i </sub></em>is the size of the home in square feet?</li>

 <li>Estimate the log-transformed equation via ordinary least squares on the transformed parametersusing any algorithm you would like. Save the coefficient estimates and the average marginal effects estimates of <em>z<sub>i </sub></em>and and . Bootstrap the 95% confidence intervals of the coefficient estimates and the marginal effects estimates using 1000 sampling replications. Display the results in a table with three columns (one for the variable name, one for the coefficient estimate, and one for the marginal effect estimate). Show the 95% confidence intervals for each estimate under each number.</li>

 <li>Graph the average marginal effects of outdoor temperature and square feet of the home withbands for their confidence intervals so that they are easy to interpret and compare.</li>

</ul>