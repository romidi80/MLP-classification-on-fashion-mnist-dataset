# Multi-Layer Perceptron (MLP) Classifier for Model Optimization
Using MLPclassification method to classify fashion mnist dataset

As observed, the validation data starts with a higher loss value (lodd) and gradually converges towards zero. This is due to the fact that the validation dataset contains fewer samples than the training dataset. Consequently, the model gains limited information about the overall data distribution during one training iteration. To minimize the loss, the model requires a higher number of epochs.

The optimal model is sought through examining the impact of changing multiple features on the model's accuracy. By varying hyperparameters under consistent conditions, the best model is identified, and its accuracy is reported. Increasing the number of layers in the model improves its performance. This is attributed to the model having a higher degree of freedom, which allows it to fit the original data distribution more effectively. Among the solver options, "adam" consistently outperforms others in terms of accuracy. The choice of solver significantly affects the model's convergence and, subsequently, its accuracy. Smaller learning rates lead to higher accuracy, as they help the model approach the optimal point with finer resolution. This minimizes the risk of overshooting and allows the model to converge more effectively.

Through a comprehensive analysis of various factors, including validation data distribution, hyperparameters, layer depth, solver choice, and learning rate, we have identified the key elements that optimize the MLP classifier's accuracy. These insights contribute to the enhancement of the model's performance and its ability to accurately classify data.

![image](https://github.com/romidi80/MLP-classification-on-fashion-mnist-dataset/assets/89667194/3760a623-a3e4-4cb5-8fbd-bba08ca3274c)
