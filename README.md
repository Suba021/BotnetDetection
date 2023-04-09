# BotnetDetection
## Inspiration:

Security is a major concern for Internet of Things (IoT) devices. Due to their vulnerabilities, these devices are an easy target for unauthorised access. Traditional security mechanisms are not easily deployed on these tiny devices. In light of this, the inspiration for   botnet detection machine learning model is to promote better security to the people.By using the extensive Intel oneAPI tools we can optimise the model.With this model, people are informed about the health of the machine. Ultimately, this project has the potential to play a significant role in improving  security and reducing vulnerability on a global scale.

## How Botnet works ?


The term botnet is actually short for “ro-bot net-work”, which refers to a group of robot devices (computers, mobile phones, IoT devices) that are now under the control of an attacking party. Typically the devices in a botnet have been infected by malware, and the attacker controlling the botnet is called a “bot herder”.Once a cybercriminal (or bot herder) has control of a group of infected devices (composing a botnet) they can remotely command every device to simultaneously carry out coordinated activities, including malicious and criminal activities like:DDOS, Spam attack,Data Breach,Monitoring etc.

## Methodology


1.Import libraries

2.Understand the features and visualise it 

3.Replace null with Zero.

4.The features such as 'src_ip', 'conn_state', 'src_port', 'dst_ip', 'dst_port', and 'ts

5.We converted the categorical features into numerical using the LabelEncoder() function from the sklearn library of python. We used label encoding despite the one-hot encoding because one-hot encoding increases the dimensionality of the dataset by adding an extra column of every single category. 


6.Test with different classification algorithms and find the best

7.Train the model in One Api for the better results with fast computation

8.Test the accuracy with the algorithms and find the best

## Algorithms

* Logistic Regression (LR)

* Gaussian Naive Bayes (GNB)
 
* Decision Trees (DT)
 
* Random Forest (RF)
 
* Extreme Gradient Boosting (XGB)



## Classifiers

LR  → 85.3

NaiveBayes → 86.54

Decision Tree → 99.991

Random Forest → 99.992

XGB → 86.74

## Expected Results:

![Untitled design](https://user-images.githubusercontent.com/129875760/230754254-9d294618-d39b-42b9-a637-b0bb0c445cbf.jpg)




