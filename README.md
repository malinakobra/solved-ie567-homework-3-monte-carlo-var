Download Link: https://assignmentchef.com/product/solved-ie567-homework-3-monte-carlo-var
<br>



<ol>

 <li><strong> Monte Carlo VaR.</strong> (total 5 points) You have written 60 calls and 60 puts on ABC stock, and 40 calls and 40 puts on DEF stock. Each option is on 100 shares. The ABC call and puts have strike prices of $100, and the DEF calls and puts have strike prices of $150. All of the options expire in one month (0.08333 year). The prices of ABC and DEF are $101.17 and $148.97 per share, respectively. The continuously compounded interest rate is 0.01 or 1% per year, and neither ABC nor DEF will pay dividends during the next month.  The implied volatility of ABC is 0.45 or 45% and the implied volatility of DEF is 0.37 or 37%.</li>

</ol>

<ul>

 <li> Please use the binomial model to compute the current value of the portfolio.</li>

 <li>The expected returns on ABC and DEF are 0.0005 (0.05%) and 0.0004 (0.04%) per day, respectively, and the standard deviations of their returns are 0.028 (2.8%) and 0.023 (2.3%) per day. The correlation between their returns is 0.40 (40%). Assume that the returns of the two stocks are normally distributed. Consider a simple VaR model in which the only market factors are the returns of the two stocks, and use the Monte Carlo method with a probability of 1% to compute the VaR of the portfolio.  What is your estimate of the 1% VaR?</li>

 <li> Plot the distribution of profits and losses on the portfolio.</li>

</ul>

<ol start="2">

 <li><strong>Monte Carlo VaR of the portfolio in Question 1, but using a horizon of 21 trading days. </strong>(2 points) Consider the options portfolio from Question 1, and use the Monte Carlo method to compute the VaR with a horizon of 21 trading days (approximately one month). Use the assumptions and parameters from Question 1, but keep in mind that you will have to convert the parameters to the 21-day horizon.</li>

 <li><strong>VaR of the portfolio is Question 1, but using the bivariate <em>t</em> </strong>(total 3 points)  Consider again the portfolio in Question 1, and once again assume that the VaR horizon is one trading day.   The mean vector is</li>

</ol>

0.0005

, 0.0004

as in Question 1.  The matrix  is

0.028                    0.028   0.023   0.4

Σ                                                                                                                 ,

0.028   0.023   0.4                 0.023




1

Neil D. Pearson

and the degrees of freedom is  = 4.




<ul>

 <li>(2 points) Use these parameters, the Monte Carlo method, and a one-day horizon to compute the 1% VaR of the portfolio.</li>

</ul>




Plot the distribution of profits and losses on the portfolio.




<em>Remark.</em>  We will spend some time in class talking about how you can simulate random deviations from the multivariate <em>t</em> distribution using the R function rmvt().  Thus, it is ok if you do not yet know how to do this.