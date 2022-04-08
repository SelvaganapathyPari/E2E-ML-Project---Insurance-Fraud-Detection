
# End-to-End Machine Learning Project - Insurance Fraud Prediction

In this Machine Learning project, we will deal with a problem statement addressed by an insurance company, in which we need to detect fraudulent insurance applications and route them to manual inspection, while moving the rest for approval. 

I intend to create a machine learning project that is close to production level, which means adhering to all of the documentation and pipelines highlighted below. 


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






## Deployment

To deploy this project, install requirements and run main

```bash
  Pip install -r requirements.txt
```

