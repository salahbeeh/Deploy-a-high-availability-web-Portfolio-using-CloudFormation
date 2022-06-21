# Udacity Cloud DevOps Engineer

## Deploy a high-availability web app using CloudFormation 

### Problem Statement 
* Your company is creating an Instagram clone called Udagram. Developers want to deploy thier application to the AWS infrastructure. They pushed thier latest contribution to a public S3 Bucket.  

* You have been tasked with provisioning the required infrastructure and deploying thier latest contribution files which are located in a public S3 Bucket to the Apache Web Server running on an EC2 instance, along with the necessary supporting software.

* This needs to be automated so that the infrastructure can be discarded as soon as the testing team finishes their tests and gathers their results.

### Installation Dependencies
```
$ pip3 install awscli --upgrade --user
```

### Diagram of the Infrastructure
![Infrastructure-Diagram](/samples/portfolio.jpeg)

### Deployment Instruction for the Infrastructure
```
$ ./create.sh stackName network_infrastructure.yml infrastructure_parameters.json
```

### Output of Project
![Website-of-the-project](/samples/portfolio-deployment.png)


