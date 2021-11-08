# Neural_Network_Charity_Analysis

# Overview

Using  knowledge of machine learning and neural networks, features in the provided dataset were used to 
create a binary classifier that is capable of predicting whether applicants will be successful if funded 
by Alphabet Soup.Technical analysis that involved ; (1) Preprocessing Data for a Neural Network Model,(2) Compile, Train, and Evaluate the Model 
and (3) Optimized model were used for the Neural network Analysis.

# Results 
# 1. 
Knowledge of Pandas and the Scikit-Learn’s StandardScaler were used to preprocess the dataset

Data Preprocessing were achied with the folll
1 Target variable is y = Clean_application_df["IS_SUCCESSFUL"]
2. Features are       X = Clean_application_df.drop(["IS_SUCCESSFUL"],1)   
3. Coulmns "EIN" and "NAME" were neither targets nor features, and removed from the input data Deliverable 1
4. During Optimization Coulmn "EIN" wes neither targets nor features, and removed from 
   the input data Deliverable 3 .The colums name was included in the features in other to increase the 
   hidden layers from 2 to 3. 

![image](https://user-images.githubusercontent.com/70987568/140660385-153e0e9f-7b29-4686-8027-d706d1b22e3c.png)

![image](https://user-images.githubusercontent.com/70987568/140660393-6ad6e3e4-0640-45d5-8062-8b988422dab9.png)

![image](https://user-images.githubusercontent.com/70987568/140660573-bf495c1e-ce98-46f1-8ba5-85f9ee75e533.png)

![image](https://user-images.githubusercontent.com/70987568/140660356-c0603155-10d6-4fd0-a7c7-4004f7fde465.png)


# 2.  
Knowledge of TensorFlow was used to design a neural network and deep learning model to create a binary classification 
model that predicted if an Alphabet Soup–funded organization will be successful based on the features in the dataset.

![image](https://user-images.githubusercontent.com/70987568/140660538-9f0d4b3c-c489-44d8-935e-ad39de9daa4a.png)

![image](https://user-images.githubusercontent.com/70987568/140660546-872f1fd4-2e7a-4a5a-bc3c-a42e0bb8caff.png)

Accuracy = 72.8 % and Loss= 55.5% resulting from  2 neurons,  3 layers, and 2 types of  activation functions "relu" and "sigmoid"
selected for the neural network model.

# 3. Optimization

 Knowneldge of Neural network was used to manipulate the data by Compiling, Training, and Evaluating the Model
 3 neurons,  4 layers, and 2types of  activation functions "relu" and "sigmoid" were selected for the neural
 network model in other to increase the accuracy
 
 Model accuracy = Loss: 0.4432152807712555, Accuracy: 0.7897375822067261, for optimized model with an increase in hidden
 layer and increase in variable with additions of "NAME" columns
 
 # Summary
 79% aaccuracy and 44.3% loss were achieved with Tensor flow neural network model 
 Comparative analysis to other models such as logisticesRegression , RandomForestClassifier and SVM showed 47%, 77% and 
