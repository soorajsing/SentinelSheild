# SentinelSheild
SentinelSheild is an API-based real-time toxic comment and tweet detection using Bi-LSTM and dropout layer tuning.
# Problem Statement
In our pursuit of identifying various forms of harmful online comments such as threats, obscenities, insults, and identity-based hate speech, we will commence by sourcing a suitable dataset from platforms like Kaggle. This dataset will encompass a collection of Twitter comments, forming the foundation of our analysis.

To ensure the dataset's quality and usability, we will undertake preprocessing steps. This includes the removal of stop words, which are common words that do not contribute significantly to the meaning of the text. The aim of this preprocessing is to streamline the data and improve the efficiency of subsequent stages.

Subsequently, we will embark on the training phase, where a classification model will be developed. The purpose of this model is to categorize each comment into its respective classification: threats, obscenities, insults, or identity-based hate speech. The training process will involve exposing the model to labeled examples, enabling it to learn the distinct patterns associated with each class of toxic comments.In conclusion, our project encompasses data collection, preprocessing, and model training to effectively identify and categorize different types of toxic comments. This effort not only requires technical prowess but also an ethical commitment to promote a safer and more inclusive online environment.
# Step-wise Algorithm
1. Begin by importing the essential modules through the following lines.
2. Construct the sequential neural network architecture by creating an instance of the Sequential API.
3. Integrate the Embedding layer into the model structure with the help of the `model.add` method.
4. Enhance the neural network's capabilities by adding a Bi-Directional LSTM layer, employing a hyperbolic tangent (tanh) activation function.
5. Safeguard against overfitting by introducing a dropout layer while applying a specified weight constraint.
6. Foster feature extraction by incorporating fully connected Dense layers, each utilizing tanh as its activation function.
7. Culminate the architecture with a final Dense layer, employing the sigmoid activation function.
8. Prepare the model for training by compiling it, using the Adam optimizer.
9. Commence the training process by utilizing the `model.fit` function for approximately 5 epochs.
10. Leverage the trained model to predict values for a single input using the `model.predict` function.
# Flow Chart

![Screenshot 2023-07-30 200846](https://github.com/shriyanshsinha9/TocSecur/assets/126511293/0856c58e-5355-40fc-82da-1b19f0dd8ed0)

# Screenshots


![Screenshot 2023-07-30 201144](https://github.com/shriyanshsinha9/TocSecur/assets/126511293/6bee4241-327f-474f-a284-5ece942f26ee)
<br>

![Screenshot 2023-07-30 201217](https://github.com/shriyanshsinha9/TocSecur/assets/126511293/eeafb06f-142f-4638-a284-85d3bd327683)
<br>

![Screenshot 2023-07-30 201249](https://github.com/shriyanshsinha9/TocSecur/assets/126511293/1ba20caa-24a7-4a33-89ab-dd40814d8014)
