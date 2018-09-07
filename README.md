# microservices-aws-fargate
Microservices example using Docker + AWS + ECS(Fargate)

## Build

 - Build docker images 
 
 ```./start.sh build```

 - Create ECR repo 
 
 ```aws ecr create-repository --repository-name msdemo/customerservice``` 
 
 ```aws ecr create-repository --repository-name msdemo/orderservice```

 - configure ecr repo uri in file  ```start.sh``` MANUALLY.

 - Push docker images 
 
 ```./start.sh push```

## Architecture

Please follow link (here)[https://boby.com.au/technical/2018/08/30/Deploying-Microservices-Aws.html]
