# Hyperparameter Tuning

Hyperparmater tuning is the technique for choosing appropriate/optimal hyperparameter in a machine learning algorithms. Hyperparamters provides more control on how the machine will learn, and they are predefined.

Other parameters are learnable parameters as these parameteres are learned while training occuring.

Hyperparameter Tuning is an important task in machine learning and Deep learning based methods, as the models performance largely depends on appropriate hyperparameters.

Hyperparameters can be tuned manually. Different hyperparameters can be tried for a single model to see if the models performance is increasing. In this repository we tried sklearn's API's for automating hyperparameter tuning. We tried GridsearchCV and RandomizedsearchCV. 

GridsearchCV train the model for all the given set of hyperparameters and shows the best set of hyperparameters. RandomizedsearchCV choose random sets of hyperparameters and train the model with it. When the model is small (take less time to train) GridseachCV is a good option as it left no stone unturned. BUt if the model is large, RandomizedsearchCV can be tried for hyperparameter Tuning 
