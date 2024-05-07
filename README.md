# Mobile-Price-Classification-using-AWS-Sagemaker-and-AWS-Lambda

Data Source - https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification?resource=download

Let's divide the workload
1. Initialize Boto3 SDK and create S3 bucket. 
2. Upload data in Sagemaker Local Storage. 
3. Data Exploration and Understanding.
4. Split the data into Train/Test CSV File. 
5. Upload data into the S3 Bucket.
6. Create Training Script
7. Train script in-side Sagemaker container. 
8. Store Model Artifacts(model.tar.gz) into the S3 Bucket. 
9. Deploy Sagemaker Endpoint(API) for trained model, and test it.


### Let's divide the workload:

1. Deploy the Sagemaker Endpoint.
2. Create Lambda Function
3. Create Rest API in API Gateway
4. Deploy API
5. Test API using Postman and Python Script


This project entails the implementation of a sophisticated machine learning pipeline leveraging Amazon SageMaker and complementary AWS services. Commencing with infrastructure setup, the process involves initializing the Boto3 SDK to establish an S3 bucket and uploading data into SageMaker Local Storage. Subsequently, thorough data exploration and understanding are conducted to inform the subsequent steps. The dataset is then partitioned into train/test CSV files before being re-uploaded into the S3 bucket. Following data preparation, a training script is crafted and executed within a SageMaker container, culminating in the generation of model artifacts, which are stored in the designated S3 bucket for future access. Transitioning to deployment, the focus shifts towards operationalizing the trained model by creating a SageMaker Endpoint. This stage encompasses the development of a Lambda function, the establishment of a REST API in API Gateway, deployment of the API, and comprehensive testing using tools like Postman and Python scripts. Through this project, proficiency in AWS services, machine learning pipeline development, and the deployment of machine learning models as RESTful APIs for practical applications is demonstrated.
