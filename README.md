# Breast-Cancer Classification

![image](https://user-images.githubusercontent.com/72307168/202231875-f645f962-e705-4476-93be-ec85ec8cf44e.png)

--> <b> <i> DATASET : </i> </b>

The dataset is directly imported from <b> <i> sklearn </i> </b> module.

--> <b> <i> METHODOLOGY : </i> </b>

0 and 1 are used to predict whether a person have a brain tumor or not in the following way:

● 0 --> The brain tumor is Benign

● 1 --> The brain tumor is Malignant 

The libraries used here are  <b> <i> Tensorflow </i> </b> and <b> <i> Keras </i> </b>.

The prgram then divides the dataset into training and testing samples in <b> <i> 80:20 </i> </b> ratio randomly using <b> <i> train_test_split() </i> </b> function available in <b> <i> sklearn </i> </b> module.

Accuracy score is then calculated by comparing with the correct results of the training dataset.

<b> <i> Model predict() </i> </b> function used here provides ous the two values in the output. 

● The first value provides us with the probability that the brain tumor is Malignant;

● And the second value provides us with the probability that the brian tumor is Benign.

So to predict whether the brain tumor is benign and malignant , we use <b> <i> np.argmax() </i> </b> function to predict the output.

You can also predict the data by entering your data according to the dataset.
  
--> <b> <i> OUTPUT : </i> </b>
  
The given output is :

![image](https://user-images.githubusercontent.com/72307168/202232328-9f6d9adf-b381-4eb1-9a81-26bb51cc326d.png)

