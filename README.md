# About this notebook

This notebook is completely adapted from the AWS SageMaker tutorial [here](https://aws.amazon.com/getting-started/hands-on/build-train-deploy-machine-learning-model-sagemaker/#:~:text=Introduction%201%20Step%201%3A%20Create%20an%20Amazon%20SageMaker,model%20performance%20...%206%20Step%206%3A%20Clean%20up).

The S3 bucket to store data is in ADSS. 

Copy and paste the following code into the next code cell and choose Run.

##Note: 

Make sure to replace these fields in the second cell: 
bucket_name = 'bucket-name' # <--- CHANGE THIS VARIABLE TO A UNIQUE NAME FOR YOUR BUCKET
aws_access_key_id='AWS_ACCESS_KEY' # <--- Replace this variable with the AWS Access Key ID
aws_secret_access_key='xvks7pBha7p2NFgspnH/pZsQ8+IzW8XZtHZwM4MQ' # <--- Replace this variable with the AWS Secret Access Key
endpoint_url='http://1.2.3.4:5678' # <--- Replace this variable with the IP Address and Port number

If you don't receive a success message after running the code, change the bucket name and try again.