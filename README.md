

# Heart-disease-heart-attack-prediction
This Project is for prediction of possibility of having a heart disease.
The dataset used is taken from kaggle


## Let's understand the working of the code


Importing the required libraries and modules


<img width="589" alt="image" src="https://github.com/Hitesh2112/Heart-disease-heart-attack-prediction/assets/97521900/d3f13620-6096-47c6-b058-fd51ef7fc777">


Reading the CSV file using pandas library

<img width="591" alt="image" src="https://github.com/Hitesh2112/Heart-disease-heart-attack-prediction/assets/97521900/78115ddf-8ce7-4575-8bfd-8e8b5682c686">


Checking for Null values

<img width="163" alt="image" src="https://github.com/Hitesh2112/Heart-disease-heart-attack-prediction/assets/97521900/32df9e69-a995-417e-a899-fae33d2919a7">


Finding the correlation matrix for finding the most important attributes affecting the heart disease and non necessary attributes which can be removed

<img width="167" alt="image" src="https://github.com/Hitesh2112/Heart-disease-heart-attack-prediction/assets/97521900/cf12c114-929a-4fee-854a-73e2ed5519fc">


Now ,ploting the heat map for correlation matrix

<img width="434" alt="image" src="https://github.com/Hitesh2112/Heart-disease-heart-attack-prediction/assets/97521900/a9853f09-b2af-4133-9f72-0bca37398b01">


Dropping the useless attributes

<img width="635" alt="image" src="https://github.com/Hitesh2112/Heart-disease-heart-attack-prediction/assets/97521900/68a71935-13ea-47f2-a1ce-6e6ffd355e8e">


For training of dataset ,we need to divide the dataset into two parts ,one is 'X' represents input and other is 'Y' represents output

<img width="295" alt="image" src="https://github.com/Hitesh2112/Heart-disease-heart-attack-prediction/assets/97521900/ebb10328-b6a6-48b7-ab7f-b0789e39b3fc">


Splitting the dataset into training and testing sets

<img width="605" alt="image" src="https://github.com/Hitesh2112/Heart-disease-heart-attack-prediction/assets/97521900/e0ade16c-4753-44fa-bbd5-d1e1f32d7763">


Training the model (Logistic Regression)

<img width="530" alt="image" src="https://github.com/Hitesh2112/Heart-disease-heart-attack-prediction/assets/97521900/dec5bddc-db3e-4cf3-9d25-feaa576ebdc5">


Classification report for logistic regression model

<img width="389" alt="image" src="https://github.com/Hitesh2112/Heart-disease-heart-attack-prediction/assets/97521900/b79cbc12-34a8-4d9d-a8db-3d028cffb081">


Similarly we implemented for other Machine Learning algorithms such as : Gausian Naive Baies, Decision Tree
and Ensemble techniques like : Random Forest Classifier, Extra Trees Classifier, Gradient Boosting


At the end also trained the dataset using Neural Newtorks

<img width="565" alt="image" src="https://github.com/Hitesh2112/Heart-disease-heart-attack-prediction/assets/97521900/05f28b44-4b6c-454d-8776-4c04889a9f00">


Adding layers in the neural network


<img width="540" alt="image" src="https://github.com/Hitesh2112/Heart-disease-heart-attack-prediction/assets/97521900/1c5acde1-eba5-4e35-ae7b-bd8f84b4930a">


Compiling the neural Network

<img width="512" alt="image" src="https://github.com/Hitesh2112/Heart-disease-heart-attack-prediction/assets/97521900/e93f870e-3675-4662-8210-62ad0925cc4c">


Fitting ANN to Training set

<img width="532" alt="image" src="https://github.com/Hitesh2112/Heart-disease-heart-attack-prediction/assets/97521900/57f79982-bdc8-48f1-ac34-b274e4020af5">

### At the end ,we saw that accuracy for training dataset is best for Random Forest, Extra Tree Classifier and Decision tree, but test set accuracy is best for Logistic regression and Gradient boosting 
