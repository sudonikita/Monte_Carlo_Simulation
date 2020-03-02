Monte_Carlo_Simulation

The Monte Carlo simulation can be used to show the change of estimation performance and many other computational results. It provides a number of advantages over deterministic analysis such as Probabilistic Results, Scenario Analysis, Correlation of Inputs etc.

E(y|x) = 5 + 1.2X1 + 3X2

The model has X1 ∼ N(−1,0.4^2), X2 ∼ N(−1,0.1^2) and the sample size varies from 200 to 2000. By fixing the predictor x for the following steps, the Monte Carlo simulation can clearly show the bias, variance and MSE for each of these variables. Through the simulation results, several patterns can be found.

Conclusion:

Three points can be made from the results:
First, the bias of each variable is decreasing with the increasing of sample size, which means bias is not constant and will decrease with the increasing of sample size. This is due to the unbiasedness of MLE.

Second, the variance coefficients converges to zero as n → ∞. So it is clear that each variance of coefficients decreases with an increasing sample size.

Third, the MSE of estimated coefficients are not constant. The reason is twofold. First, the bias will converge to zero due to consistency of estimator. Second, the variance converges to zero with an increasing sample size. Thus, the MSE undoubtedly converges to zero, which is also clearly displayed in the simulation results.

All in all, the simulation is really helpful to see what happened based on different sample size or even different model settings. For different assumptions of random variables and errors, the team may get some interesting findings further. But these will be left for future studies.
