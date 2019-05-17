# AI with Databricks and Azure Machine Learning

Trey Research Inc. delivers innovative solutions for manufacturers. They specialize in identifying and solving problems for manufacturers that can run the range from automating away mundane but time-intensive processes to delivering cutting edge approaches that provide new opportunities for their manufacturing clients. 

Trey Research is looking to provide the next generation experience for connected car manufacturers by enabling them to utilize AI to decide when to pro-actively reach out to the customer thru alerts delivered directly to the car's in-dash information and entertainment head unit. For their PoC, they would like to focus on two maintenance related scenarios.

In the first scenario, Trey Research recently instituted new regulations defining what parts are compliant or out of compliance. Rather than rely on their technicians to assess compliance, they would like to automatically assess the compliance based on component notes already entered by authorized technicians. Specifically they are looking to leverage Deep Learning technologies with Natural Language Processing techniques to scan through vehicle specification documents to find compliance issues with new regulations. Then each car is evaluated for out compliance components. 

In the second scenario, Trey Research would like to predict the likelihood of battery failure based on the telemetry stream of time series data that the car provides about how the battery performs when the car is started, how it is charging while running and how well it is holding its charge, among other factors. If they detect a battery failure is immenent within the next 30 days, they would like to send an alert.

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
In this workshop, you will ...

At the end of this workshop, you will be better able to [deliver, demonstrate, solve, present, migrate, build, design, architect, construct, modify] ….

### Whiteboard design session 
In this whiteboard design session, you will work in a group to ...

At the end of this whiteboard design session, you will be better able to [deliver, demonstrate, solve, present, migrate, build, design, architect, construct, modify] ….

#### Outline: Key Concerns for Customer situation ####
- Use of AML automated machine learning within Azure Databricks for model creation of ML based time series forecasting models (not for deep learning models) and understanding of its capabilities (automated pre-processing, featurization and hyper-parameter tuning)
- Use of model explainability features 
- Model lifecycle management from training in Azure Databricks to deployment for use in batch and real-time inferencing scenarios
- Deep learning model for NLP in text classification
- Deep learning model (RNN) for forecasting against time-series data
- Want to use PyTorch for deep learning

### Hands-on lab 
In this hands-on lab, you will ...

At the end of this hands-on lab, you will be better able to [deliver, demonstrate, solve, present, migrate, build, design, architect, construct, modify] ….


#### Outline: Hands-on lab exercises
- Exercise 0: Before the hands-on lab
- Exercise 1: Creating a forecast model using automated machine learning
- Exercise 2: Understanding the forecast model using Model explainability and registering the model
- Exercise 3: Creating a deep learning model (RNN) for time series data and registering the model
- Exercise 4: Evaluating the models
- Exercise 5: Using the selected forecast model for scoring of streaming telemetry
- Exercise 6: Creating a deep learning text classification model 
- Exercise 7: Using the text classification model in a batch scoring pipeline


## Azure services and related products
-	Azure Databricks
-	Azure Data Explorer
-	Azure Data Lake Storage Gen 2
-	Azure Machine Learning service
-	Azure Machine Learning Automated Machine Learning
-	Azure Storage
-	IoT Hub
-	Pytorch
-	Power BI

## Related references
*This should be a list of and links to prereqs, architectural diagrams, supporting docs, or briefing decks related to the material.* 
- [MCW](https://github.com/Microsoft/MCW)
