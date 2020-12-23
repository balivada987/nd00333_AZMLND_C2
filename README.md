

# Operationalizing Machine Learning

Overview:
The data used in project  is related to direct marketing campaigns of a banking institution. The primary objective is to this project is to predict whether a customer subscribe a term deposit or not in Micosoft Azure 
The project is all about creating a optimized model from scratch  by using Azure ML and deploy it as a webservice so that it can be consumed . 
It can be  done by two methods 
1.	Using Azure ML Studio 
2. Using Pipelines


The architectural diagram, steps and screen recording is available in the Udacity Project Documentation file attached in  this link: 
https://github.com/balivada987/nd00333_AZMLND_C2/blob/master/Udacity%20Project%202%20Documentation.docx


# Architecture Diagram:

![alt text](https://github.com/balivada987/nd00333_AZMLND_C2/blob/master/ArchitectureDia%201.png)


# Process Flow:
![alt text](https://github.com/balivada987/nd00333_AZMLND_C2/blob/master/ProceeFlow%202.PNG)

SP Authentication:
![alt text](https://github.com/balivada987/nd00333_AZMLND_C2/blob/master/SP%20Authentication.png)
![alt text](https://github.com/balivada987/nd00333_AZMLND_C2/blob/master/SP%20Authentication%202.png)
![alt text](https://github.com/balivada987/nd00333_AZMLND_C2/blob/master/SP%20Authentication%203.png)


![alt text](https://github.com/balivada987/nd00333_AZMLND_C2/blob/master/SP%20Authentication%204.png)

# Creating Auto ML model and Executing Auto ML Model
![alt text](https://github.com/balivada987/nd00333_AZMLND_C2/blob/master/AutoML1.png)
![alt text](https://github.com/balivada987/nd00333_AZMLND_C2/blob/master/AutoMl2.png)
# Auto ML model execution completed 
![alt text](https://github.com/balivada987/nd00333_AZMLND_C2/blob/master/AutoML3.png)
# Voting Ensemble model  is the best model 
![alt text](https://github.com/balivada987/nd00333_AZMLND_C2/blob/master/AutoML4.png)

# The best model is deployed as webservice and application insights are enabled
![alt text](https://github.com/balivada987/nd00333_AZMLND_C2/blob/master/AutoML5.png)
# Executed logs.py file  to view the logs 
![alt text](https://github.com/balivada987/nd00333_AZMLND_C2/blob/master/AutoML6.png)
# Swagger is running on locahost:9000
![alt text](https://github.com/balivada987/nd00333_AZMLND_C2/blob/master/AutoML7.png)
# Endpoint has been created in the link shown in screenshot and tested through posting json type of input

![alt text](https://github.com/balivada987/nd00333_AZMLND_C2/blob/master/AutoML8.png)
# Creating a benchmark  using bash benchmark.sh  and Testing the endpoint after benchmark creation
![alt text](https://github.com/balivada987/nd00333_AZMLND_C2/blob/master/AutoML9.png)

# Python SDK implementation
Python SDK Implementation:
After creating new notebook and connecting with the compute instance . Pipelines are built to implement a AutoML model on the same dataset.  Pipeline has been configured for AutoML and scoring
After submitting the pipeline the following screen shot is captured displaying the  status of pipeline in SDK and  designer studio
Pipeline Section in AzureML Studio:


![alt text](https://github.com/balivada987/nd00333_AZMLND_C2/blob/master/AutoML10.png)

# Pipeline is created and running on below screenshot
![alt text](https://github.com/balivada987/nd00333_AZMLND_C2/blob/master/AutoML11.png)
#
![alt text](https://github.com/balivada987/nd00333_AZMLND_C2/blob/master/AutoMl12.png)
![alt text](https://github.com/balivada987/nd00333_AZMLND_C2/blob/master/AutoML13.png)
# Pipeline Runs are completed and their screenshot
![alt text](https://github.com/balivada987/nd00333_AZMLND_C2/blob/master/AutoML14.png)
# Pipeline Endpoints are Displayed  in the screenshot
![alt text](https://github.com/balivada987/nd00333_AZMLND_C2/blob/master/AutoML15.png)
# Run Details widget screenshot
![alt text](https://github.com/balivada987/nd00333_AZMLND_C2/blob/master/AutoML16.png)
# Pipeline is screduled at regular intervals using schedule command 
![alt text](https://github.com/balivada987/nd00333_AZMLND_C2/blob/master/AutoML17.png)
# Screenshot of all the Pipeline Runs since pipeline is scheduled at a frequency of  2 minutes
![alt text](https://github.com/balivada987/nd00333_AZMLND_C2/blob/master/AutoML18.png)


# Screencast Video LInk

https://www.youtube.com/embed/-yH1SSQmINk?feature=oembed

# Areas of Improvement :
1.Data Imbalance has been detected as displayed in screenshot . Undersampling and Oversampling can be used to improve the distribution of data 
2. During sampling stratified sampling can be used 
![alt text](https://github.com/balivada987/nd00333_AZMLND_C2/blob/master/AreasofImp.png)

