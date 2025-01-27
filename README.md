# Rice_Leaf_Disease_Prediction_Using_Transfer_Learning

Pre-Requisite 
	
	TensorFlow
	Keras
	Numpy
	Pandas
	matplotlib
	seaborn

## Architecture

Will be uploaded....

## Steps to run

Load the data set for each program using their path
	

1.Model_6_Cov_out_soft - The code for trainig model 1 (refer Proposed System Diagram)
	
	The trained Model will be saved the path specified in saveModel (code).


2.Transfer_Learning - This code will use transfer learning methodoly for training Model 2

	Ensure to load the savedModel by the (1) code.
	This will save model 2 in specified path.

3.Output_Prediction - This code is used to perform classification:
	
	Load any saved model (1 or 2) to test them for given Data set.

4.RAA_T1_Algorithm (Result Analyzer Algorithm)
	
	This code will load both model1 and model2 and combine their result and compare them
	to provide multiple disease identification on  a single leaf.
