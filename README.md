# Multiple-Linear-Regression-Monte-Carlo-Simulation-

Model selection plays a central role in regression analysis, especially when evaluating 
predictors in complex datasets. Selecting a model that balances  it and simplicity helps 
prevent over itting, ensuring better predictive performance and interpretability. This 
study examines the performance of two popular model selection criteria, AIC and cross
validated MSE, through a Monte Carlo simulation. I compared a True Model, defined to 
capture the assumed data-generating process, with a simpler Reduced Model and a more 
complex Enlarged Model. By evaluating model performance over 5000 simulations, I
aim to determine which criterion is more effective in identifying the correct model.

## Results

The True Model was selected most frequently by both criteria, with AIC slightly favoring it over 
cross-validated MSE. The Enlarged Model was chosen in a signi icant minority of cases, suggesting 
that increased complexity sometimes improved model  it or predictive accuracy slightly but did 
not provide an overall advantage over the True Model. 
1.True Model: R-squared ≈ 0.302, indicating this model explains about 30.2% of the 
variance in YYY. 

2. Reduced Model: R-squared ≈ 0.194, con irming a substantial loss in explained variance. 

3.Enlarged Model: R-squared ≈ 0.302, mirroring the True Model but with additional terms 
that did not signi icantly improve  it.
