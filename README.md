# GANS-SYNTHETIC-DATA-GENERATION

•	Developed and enhanced Generative Adversarial Networks (GANs) model.
Trained both the discriminator and generator models on tabular financial data and successfully generated synthetic data with high accuracy
Things done to achieve it:
Batch Normalization: Added to the generator to stabilize training. Model Capacity: Adjusted the network architecture to better capture the data distribution.
Learning Rate: Further reduced to 0.00005 for both the generator and discriminator. 
Increased Epochs: Increased the training epochs to 2000 to allow more time for convergence. 
Batch Size: Increased the batch size to 64 to make training more stable. 
Outcome: These changes resulted in synthetic data that more closely resembles the real data, as indicated by similar statistics and better evaluation metrics (MSE and MAE). 
The KDE plots also showed greater overlap between real and generated data distributions.
