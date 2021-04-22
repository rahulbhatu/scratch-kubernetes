# Scratch containerization and orchestration
This repository contains configuration files that will be required to deploy this
containerized application [scratch-api](https://github.com/rahulbhatu/scratch-api) to kubernetes cluster.
We have use kubernetes secret to store the confidential data.


# Deploy the code
**Prerequsiste** : To deploy the code we will need and existing kubernetes cluster or
minukube to test this deployment.
kubectl tool is required to deploy from command line utility.


we can simply clone the repo and execute below command
`kubectl create -f app-deployment.yaml,app-service.yaml,db-deployment.yaml,db-service.yaml,secret.yml`

This deploy the containerized application on the kubernetes cluster in the default namespace.
