# About this notebook

This notebook is adapted from the AWS SageMaker tutorial [here](https://aws.amazon.com/getting-started/hands-on/build-train-deploy-machine-learning-model-sagemaker/#:~:text=Introduction%201%20Step%201%3A%20Create%20an%20Amazon%20SageMaker,model%20performance%20...%206%20Step%206%3A%20Clean%20up).

We are using [Dell ECS](https://www.google.com/search?q=dell+ecs&rlz=1C1GCEO_enSG1032SG1032&oq=dell+ecs&aqs=chrome.0.69i59j0i512l4j69i60l3.2583j0j7&sourceid=chrome&ie=UTF-8) for storing data.

The ECS bucket is used to store data from AWS SageMaker. 

To-Do:

1. Update the `.env` variables contents with 
- ECS Access Key  
- Secret Access Key

2. Replace variable `bucket_name = 'bucket-name'`

3. Replace variable `endpoint_url='http://1.2.3.4:5678'`
