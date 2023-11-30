# Attack Type Classification on Wireless Network Dataset .
A dataset for intrusion detection systems in wireless sensor networks

## Inroduction 
WSNs are highly vulnerable to attacks, due to their open and distributed nature and limited resources of the sensor nodes. Moreover, in WSNs packets broadcasting has to be done frequently, sensor nodes can be deployed randomly in an environment so an attacker adversary can be easily injected to a WSN .

An attacker can compromise a sensor node, eavesdrop messages, inject fake messages, alter the integrity of the data, and waste network resources. Denial of Service (DoS) attack is considered one of the most general and dangerous attacks that threaten WSN security. This attack has several forms and its main objective is to interrupt or suspend the services provided by WSNs DoS is a common attack that could have a severe impact on WSN’s functionalities and services. Many different types of DoS attacks have been identified so far, for example, Blackhole attack, Grayhole attack, Flooding attack, and Wormhole.

## Context of Study 
WSN-DS Dataset: </br>
The experiment uses a simulated wireless sensor network-detection system (WSN-DS)dataset developed by Almomani et al , and the network simulator NS-2 was used to simulate wireless sensor network environment based on the LEACH routing protocol to collect data from network and preprocessed to generate 23 features identifying the state of each sensor,and simulates four diﬀerent types of Denial of Service (DoS) attacks: Blackhole, Grayhole,Flooding, and Scheduling, the simulation parameters are summarized . Only 19 features including the class label were in the dataset ﬁle. This dataset was generated as an IDS dataset to apply machine learning techniques in order to detect and classify DoS attacks. The data distribution can be seen in Ipython Notebook </br>


## Methodology 
We use  a specialized dataset WSN-DS in order to classify four types of DoS attacks : Blackhole, Grayhole, Flooding, and Scheduling among normal network traﬃc. We will compare three feature selection methods with the Logistic Regression Classifier and Radndom forest witth over sampling , and examine their  performance with each method and ﬁnd the pair that chieve better results. We will propose an intelligent, eﬃcient, and learnable model using the  these classifiers  with applying feature reduction, and ensuring that the model's are  compatible with the characteristics of WSN. </br>

## Techniques Involoved 
• Preprocessing data using various methods provided by pandas and sklearn.</br>
• Implementation of predictive methods: Logistic Regression , regression, and Random Forest Classifier with oversampling .</br>
• Implementation and  analysis methods in Python and Apache Spark.</br>
