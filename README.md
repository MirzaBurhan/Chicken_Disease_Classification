# Chicken_Disease_Classification
workflow:
Update config.yaml
Update secrets.yaml [Optional]
Update params.yaml
Update the entity
Update the configuration manager in src config
Update the components
Update the pipeline
Update the main.py
Update the dvc.yaml





DVC cmd
dvc init
dvc repro
dvc dag


AWS-CICD-Deployment-with-Github-Actions
1. Login to AWS console.
2. Create IAM user for deployment
#with specific access

1. EC2 access : It is virtual machine

2. ECR: Elastic Container registry to save your docker image in aws


#Description: About the deployment

1. Build docker image of the source code

2. Push your docker image to ECR

3. Launch Your EC2 

4. Pull Your image from ECR in EC2

5. Lauch your docker image in EC2

#Policy:

1. AmazonEC2ContainerRegistryFullAccess

2. AmazonEC2FullAccess



3. Create ECR repo to store/save docker image
849998521557.dkr.ecr.us-east-1.amazonaws.com/chicken


4. Create EC2 machine (Ubuntu)
5. Open EC2 and Install docker in EC2 Machine:
