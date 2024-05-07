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
