# Purpose
This analysis aims to deploy deep-learning and Neural networks to assist the Alphabet Soup company in determining the best allocation of their funds. This analysis used features in the dataset to create binary classifiers to predict if the fund recipient will succeed. This report outlines the steps taken to preprocess the data, select and train a suitable model, evaluate its performance, and make a recommendation based on the results.

# Results
## Model 1: Alphabet Soup Charity Model
* ### Data Preprocessing 
In this section, I explored the data to ensure it is processed and cleaned in a manner suitable for machine learning. Secondly, I used exploratory data analysis techniques to gain insights into the data distribution and identify patterns or correlations. This model removed the EIN and NAME columns; additionally, ‘Other’ replaced the CLASSIFICATION and APPLICATION_TYPE columns due to high fluctuations, as shown in Figure 1A below. Once the data was deemed suitable, I split the dataset into training and testing sets. The target variable for the model is “IS_SUCCESSFUL” and is verified by the value of 1 for YES and 0 for NO, as shown in Figure 1B below.

### Figure 1A: Model 1 Processed Data for Machine Learning
 ![Process](images/Processed_data.png)
 
 ### Figure 1B: Model 1 Data Fitting
  ![DATA](images/Data_Fitting.png)
 
 * ### Compiling, Training, and Evaluating the Model
This model used the application of a neural network. The number of features dictated the number of hidden nodes. The number of features dictated the number of hidden nodes; a three-layer training model generated 435 parameters, as shown in Figure 2A. The target accuracy for this exercise is 75%; however, the model achieved only 72% accuracy, as shown in Figure 2B below.
 
 ### Figure 2A: Model 1 Input Features and Hidden Nodes and Parameters
   ![INPUT](images/Input_Features.png)
   
 ### Figure 2B: Model 1 Accuracy Score
   ![INPUT](images/Accuracy_Score.png)

Tools and libraries used are:

* Python
* Google Colab
* Pandas SK-learn
* TensorFlow

