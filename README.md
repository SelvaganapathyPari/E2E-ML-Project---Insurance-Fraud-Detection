![man-insurance-fraud]

# End-to-End Machine Learning Project - Insurance Fraud Prediction

## Problem Statement -
To build a classification methodology using Machine Learning predictive model, to determine whether a customer is placing a fraudulent motor insurance claim.
 Predictions
Y – means fraudulent detected and needs further manual inspection
N – Approved for processing insurance claim.

I intend to create a machine learning project that is close to production level, which means adhering to all of the documentation and pipelines highlighted below. 

![Mlproject](https://user-images.githubusercontent.com/102349366/163940856-bcd287d8-90eb-4138-8444-cb1efb9ef8fc.gif)

## 1. DSA - Data Sharing Agreement 
Agreement between client and the company 
	
- mention number of files & format
- mode of data transfer
- Feature details
- Language 

## 2. HLD - High Level Design 

#### 1.To collect Low level Requirement gathering 
 	 
- To identify final end goal - in this project end goal is.

#### 2. Business understanding


- identify and Understand the client requirements
- Dataset from ?( DB, SQL, no sql, SAP/ ERP, messenging system, sensors, API, blob, s3 buckets .etc)

#### 3. identify the frequency of the Receiving the data - daily, weekly, monthly basis.

#### 4. understand No.of files to be received from client

#### 5. Data Description- Understand brief idea of the Dataset

## 3. LLD - Low Level Design Documentation

#### 1. Create connecters to pull data from client's data resources
#### 2. Data Validation
##### Collected data will be validated as per the DSA guidelines
- File Name Check
- Extension Check
- No. of column check
- Datatype of Feature
- Name of column
- Null Check
#### 3. Data Transformation
- Date/time conversion
- Language transformation
- Categorical transformation
#### 4. Data Aggregation
#### 5. Data Pre-processing
- Standardization
- Normalization
- Train test split
- Multi dimensionality reduction

#### 6. Identify whether the problem statement demands 
#### Direct Machine learning Approach -or- Custom Machine Learning Approach 
- Divide data into multiple Clusters
- Group dataset into sections into differnt clusters
- For each cluster, we ll build multi-model system

#### 7. Test the Model
#### 8. Serve the Model or model Deployment

## Project Architecture

![Architecture](https://user-images.githubusercontent.com/102349366/163941083-3172c734-b915-4c5f-9613-6796c4339b5c.gif)


## Deployment

To deploy this project, install requirements and run main

```bash
  Pip install -r requirements.txt
```
## Predictions
![frauddetection_op](https://user-images.githubusercontent.com/102349366/163940933-02ab4c50-09a0-423e-bfd0-a5b089b1fa02.jpg)

## Dataset
https://www.kaggle.com/code/buntyshah/insurance-fraud-claims-detection

