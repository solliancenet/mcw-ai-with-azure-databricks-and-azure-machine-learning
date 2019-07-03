# Machine Learning

Trey Research Inc. delivers innovative solutions for manufacturers. They specialize in identifying and solving problems for manufacturers that can run the range from automating away mundane but time-intensive processes to delivering cutting edge approaches that provide new opportunities for their manufacturing clients. 

Trey Research is looking to provide the next generation experience for connected car manufacturers by enabling them to utilize AI to decide when to pro-actively reach out to the customer thru alerts delivered directly to the car's in-dash information and entertainment head unit. For their PoC, they would like to focus on two maintenance related scenarios.

In the first scenario, Trey Research recently instituted new regulations defining what parts are compliant or out of compliance. Rather than rely on their technicians to assess compliance, they would like to automatically assess the compliance based on component notes already entered by authorized technicians. Specifically they are looking to leverage Deep Learning technologies with Natural Language Processing techniques to scan through vehicle specification documents to find compliance issues with new regulations. Then each car is evaluated for out compliance components. 

In the second scenario, Trey Research would like to predict the likelihood of battery failure based on the telemetry stream of time series data that the car provides about how the battery performs when the car is started, how it is charging while running and how well it is holding its charge, among other factors. If they detect a battery failure is imminent within the next 30 days, they would like to send an alert.

Upon detection of an out of compliance component or a battery at risk of failure, they would like to be able to send an alert directly to the customer inviting them to schedule a service appointment to replace the part. 

In building this PoC, Trey Research wants to understand how they might use machine learning or deep learning in both scenarios, and standardize the platform that would support the data processing, model management and inferencing aspects of each. 

They are also interested to learn what new capabilities Azure provides that might help them to document and explain the models that are created to non-data scientists or might accelerate their time to creating production ready, performant models. 

Finally, they would like to be able to easily create dashboards that summarize the alerts generated so they can observe the solution in operation. 

## Target audience
-	Data Engineers
-	Data Scientist
-	AI Engineers
-	Software Engineers 


## Abstract

### Workshop
In this workshop design session, you will design and implement a solution that combines Azure Databricks with Azure Machine Learning Service to build, train and deploy the machine learning and deep learning models. You will learn:
- Use of automated machine learning and understanding of its capabilities 
- Use of model explainability features
- Model lifecycle management from training in Azure Databricks to deployment for use in batch and real-time inferencing scenarios
- Deep learning models for NLP in text classification and forecasting against time-series data
- To compare PyTorch and Keras for deep learning

At the end of this workshop, you will be better able to design and implement solutions leveraging the Azure Machine Learning Service and Azure Databricks.

### Whiteboard design session 
In this whiteboard design session, you will work with a group to design a solution that combines Azure Databricks with Azure Machine Learning Service to build, train and deploy the machine learning and deep learning models. You will learn:
- Use of automated machine learning and understanding of its capabilities 
- Use of model explainability features
- Model lifecycle management from training in Azure Databricks to deployment for use in batch and real-time inferencing scenarios
- Deep learning models for NLP in text classification and forecasting against time-series data
- To compare PyTorch and Keras for deep learning

At the end of this whiteboard design session, you will be better able to design solutions leveraging the Azure Machine Learning Service and Azure Databricks.


### Hands-on lab 
In this lab, you will use Azure Databricks in combination with Azure Machine Learning Service to build, train and deploy the desired models. You will learn:
  - How to train a forecasting model against time series data without any code by using automated machine learning.
  - How to create a recurrent neural network (RNN) model using PyTorch in Azure Databricks that can be used to forecast against time-series data.
  - How to use a trained forecast model to score data in real-time using Spark Structured Streaming within Azure Databricks.
  - How to train an Natural Language Processing text classification model using Keras.

## Azure services and related products
-	Azure Databricks
-	Azure Machine Learning Service
-	Azure Machine Learning Automated Machine Learning
-	Azure Storage
-	IoT Hub
-	PyTorch
-	Power BI

## Related references
- [MCW](https://github.com/Microsoft/MCW)
