# Project_CICD
This is a repo containing the steps and required repos to run the CICD project

## Steps to ru the app

- Run the ansibl_cicd and terraform_cicd as mentioned in their respective read me 
- After running both copy the new IP to 3 different places: Frontend_CICD/jenkinsfile final stage, Backend_CICD/jenkisfile final stage, and finally to the jenkins kubernetes cloud service in localhost:8080/configureClouds --> Kubernetes
- SSH to the EC2 machine for the following data:
- Copy root/.minikube/ca.crt data to the certificate in the kubernetes cloud config
- Go to manage credentials and fill in the credentials in there in this order
- /root/.minikube/profiles/minikube/client.key
- /root/.minikube/profiles/minikube/client.crt
- /root/.minikube/ca.crt


## The required repositories

-  https://github.com/OmarLaz97/Frontend_CICD
-  https://github.com/OmarLaz97/Backend_CICD
-  https://github.com/OmarLaz97/Ansible_CICD
-  https://github.com/OmarLaz97/Terraform_CICD 
-  https://github.com/OmarLaz97/k8s_CICD


## All the commands needed to run will be found in the read me of each repository
Thank you


