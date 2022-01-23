# ML_TB
Objective
1) Artificial intelligence (AI) based Machine learning (ML) approaches for predicting resistance in the genes rpoB, inhA, katG, pncA, gyrA and gyrB for the drugs rifampicin, isoniazid, pyrazinamide and fluoroquinolones.
2) Several sequence and structural features that indicate the influence of mutations on the target protein coded by each gene.
3) We used ML algorithms - naïve bayes, k nearest neighbor, support vector machine, and artificial neural network, to build the prediction models.
4) Detection of resistance conferring mutations will help in rapid diagnosis of DR/MDR-TB and understanding the mechanism of resistance to develop effective treatment strategies.

Process: 
In the present study, Artificial Intelligence (AI) and ML algorithms were used to classify single nucleotide variations (SNVs) as being resistant or susceptible in TB and predict novel resistance conferring mutations.

![image](https://user-images.githubusercontent.com/65915038/150667640-f6eb3bc4-7c60-4836-b1dd-bf72baa3f5e7.png)

![image](https://user-images.githubusercontent.com/65915038/150667656-b4c3b677-ade2-44fe-9b02-2d7876f8718a.png)


Building Machine Learning Model: 

Model: 
Gaussian Naive Bayes
K Nearest Neighbors
Support Vector Machine
Artificial Neural network
The internal validation of the models was performed using 10-fold cross validation. 
The performance of the models was further measured using the blind test set containing 20% of the data, which was not part of the training set used for generating the models.
Statistical evaluation:
The predictive performance of the classification models on the testing data was evaluated using accuracy and a receiver operating characteristic (ROC) curve from which area under curve (AUC) was also calculated.

Roc Graph (SVM, KNN, NB) (rpoB , gyrA Gene)

![image](https://user-images.githubusercontent.com/65915038/150667699-63603074-fd8c-4b21-a712-faf5023b9924.png)
![image](https://user-images.githubusercontent.com/65915038/150667700-02ead329-d056-4f6f-9bd4-08fef1bb13ae.png)

ANN Model: 
One hidden layer with 10 neurons and relu as activation function
Sigmoid activation function for Output layer
Optimize: Adam
Loss: Binary Cross Entropy
Metrics: Accuracy
Epochs: 300
![image](https://user-images.githubusercontent.com/65915038/150667825-76b0de3e-ee0a-4277-9d2e-a199876f8ae4.png)








