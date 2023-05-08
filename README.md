Download Link: https://assignmentchef.com/product/solved-smai-homework3-ridge-regression-objective
<br>
<h1>1           Objective Question</h1>

Consider the following Ridge regression objective:

<em>J</em>(<strong>w</strong>) = argmin<strong><sub>w </sub></strong>(<strong>Y </strong>− <strong>XW</strong>)

What will the solution be for <em>λ </em>= 0 and <em>λ </em>= ∞. Select the correct pair from the options below.

<ol>

 <li>0, MLE</li>

 <li>MLE, 0</li>

 <li>0, MAP</li>

 <li>MAP, 0</li>

</ol>

Here, MLE is the maximum likelihood estimate and MAP is the maximum aposteriori estimate.

2           Subjective Question

You are interested in the problem of estimating the price of houses. A property broker told you that according to him the price of each house can depend on 9 different factors like locality, number of rooms in the houses, area of the property, etc. He provides you the detailed report of 7 such properties (i.e. for each of the 7 houses, you have been provided with the values of the 9 features). Having studied SMAI, you decide to use Linear regression for the estimating the housing prices and attempt to use the analytical or the closed form solution for the task. What is the chief issue in applying a closed form solution for this task? Will employing Ridge regression help? Explain your answer in brief.

3           Programming Question

Visualize the optimal solution obtained by Ridge regression and Lasso for different values of the hyper-parameter <em>λ</em>.

<ol>

 <li>Complete the notebook ‘Regression excercise.ipynb’.</li>

 <li>Observe the output of the Ridge regression and Lasso and comment whetherthe following statement is <strong>true or false</strong>. “ The Lasso L1 term provides a much more aggressive regularization because the intersection between the constraint function and the cost function happens at the “vertices” of the diamond where either/or each variable is equal to zero. The effect of such regularization is to “cancel” out each variable, and by varying <em>λ </em>we can test the impact of each variable on the model. In effect this is automatic variable selection. On the other hand, Ridge regression provides a less aggressive form of regularization where the coefficients tend to zero in the limit only.” (1 mark)</li>

</ol>

2