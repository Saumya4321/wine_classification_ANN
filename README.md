# Determine the origin of Wines using FNN

## Objective
Develop a Feed forward Neural network (FNN) to classify the origin of wines based on chemical analysis data, distinguishing among three distinct cultivars from Italy.
Given the values of 13 chemical constituents of a sample wine, the goal is to distinguish from which of the three cultivars it is from.

## Tasks done
+ Preprocessing of the dataset, including normalization and train-test splitting.
+ Implementation of an Artificial Neural Network (ANN) using Keras.
+ Model training with appropriate loss functions and optimization techniques.
+ Performance evaluation using accuracy and loss metrics.

## Dataset used

The dataset used is publicly available on [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/109/wine).
The data are the results of a chemical analysis of wines grown in the same region in Italy but derived from three different cultivars.
The analysis determined the quantities of 13 constituents found in each of the three types of wines. 

The attributes are -
1) Alcohol
2) Malic acid
3) Ash
4) Alcalinity of ash  
5) Magnesium
6) Total phenols
7) Flavanoids
8) Nonflavanoid phenols
9) Proanthocyanins
10) Color intensity
11) Hue
12) OD280/OD315 of diluted wines
13) Proline

## Code usage
1. Clone the repository
```
git clone https://github.com/Saumya4321/wine_classification_ANN.git
cd wine_classification_ANN

```
3. Install all the required python modules by running the following command
  ```
pip install -r requirements.txt

```
5. Run the ```ANN_wine_classification.ipynb``` notebook to train and evaluate the model. Adjust hyperparameters as needed for better performance.

## Results
The trained ANN model achieves a competitive accuracy in classifying wine samples based on their features.
<div align="center">
  
![image](https://github.com/user-attachments/assets/c17bb5e4-d2e8-4480-ac61-8d670c94d559)

![image](https://github.com/user-attachments/assets/91bf248b-573b-4052-b14b-a29db0210c11)

</div>

