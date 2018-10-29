# TDI
 Traffic signs classification using Bayesian Neural Networks.
Goal: The aim of this project is to create a Traffic signs classifier, using Bayesian Neural Networks (BNN). In BNN’s weights are random variables and instead of finding the best value for weights, posterior distributions for them will be estimated. By treating the weights in a neural network as random variables, and performing posterior inference on these weights, BNNs can avoid overfitting, provide posterior uncertainty estimates, and model a large class of stochastic functions with heteroskedastic and multi-modal noise. In BNN’s, model selection, choosing the number of nodes and layers is still an open problem Here, I use the so called DREAM GAME strategy to select appropriate model [1]. The strategy uses a robust estimator of the model evidence, the normalizing constant in the denominator of Bayes’ theorem. The evidence provides a single quantitative measure of relative support for each model. The unknown models will be trained and validated. Thereafter, using DREAM GAME strategy the best model will be selected. so it can classify traffic sign images using the German Traffic Sign Dataset.
The project steps are as follows:
•	Download Image Data
•	Load the data set. Split the sets into training and validation data. Randomize the split to  avoid biasing the results for BNN
•	Explore summarize and visualize the data set and pre-process images 
•	Select several model architectures (different nodes and layers)
•	Extract  training features from images
•	Train BNN’s using the Features
•	Test models to make predictions on new images
•	Select the best model using DREAM GAME strategy
•	Summarize the results with a written report

 [1] E. Volpi, G. Schoups, G. Firmani, J. A. Vrugt, Sworn testimony of the model evidence: Gaussian Mixture Importance (GAME) sampling, Water Resources Research, 53, 7, 2017.












