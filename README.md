
---

**Project 1 – Clustering and Classification**
This project explored the differences between unsupervised and supervised learning using neural networks. First, a Self-Organizing Map (SOM) was applied to the Digits dataset for clustering, with different grid sizes to study the granularity of clusters and the occurrence of dead neurons. The results were analyzed using hit maps, quantization error, and visualizations of mapped samples. Next, SOM-based classification was implemented by labeling neurons through majority voting, followed by performance evaluation with accuracy, precision, recall, and F1-score. Finally, a Single Layer Feedforward Network (SLFN) was implemented from scratch using NumPy and Pandas to classify Titanic passenger survival outcomes, emphasizing manual forward pass, backpropagation, and metric computation.

**Project 2 – Time Series Forecasting with NAR and NARX**
In this project, the focus shifted to nonlinear time series forecasting using two types of neural models: NAR (Nonlinear Autoregressive) and NARX (Nonlinear Autoregressive with Exogenous Inputs). Using the Delhi Climate dataset, the models forecasted temperature, wind speed, and humidity. The NAR model relied solely on historical values of the target variable, while the NARX model incorporated additional exogenous features to improve accuracy. The study compared the models in terms of predictive performance, visualization of forecast trends, and the benefits of including exogenous inputs.

**Project 3 – CNN Autoencoder for Image Denoising**
This exercise involved designing and training a Convolutional Neural Network (CNN)-based autoencoder to perform image denoising. Noisy versions of images were used as input, and the model learned to reconstruct the clean versions, capturing essential patterns while removing noise. The architecture included convolutional and pooling layers for encoding, followed by upsampling and convolutional layers for decoding. Performance was evaluated visually by comparing reconstructed outputs with clean originals and quantitatively using error metrics, highlighting the model’s capability to preserve key image features while suppressing unwanted noise.

**Project 4 – Transformer for Automated Essay Feedback**
In the final project, a Transformer model was built from scratch to perform text classification for automated essay feedback. The dataset consisted of essays with associated feedback categories, and the Transformer architecture leveraged self-attention mechanisms to model contextual relationships between words. The implementation involved constructing positional encodings, multi-head attention layers, and feedforward networks. After training, the model was evaluated using accuracy, precision, recall, and F1-score, demonstrating the Transformer’s strong capability in understanding complex textual structures for feedback prediction.

---

