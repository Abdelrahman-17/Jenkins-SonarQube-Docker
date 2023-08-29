# Jenkins CI/CD Pipeline - SonarQube, Docker, Github Webhooks on AWS 


<img src="https://github.com/Abdelrahman-17/Jenkins-SonarQube-Docker/blob/main/Jenkins%20%20SonarQube%2C%20Docker.png">


we will be creating a CI/CD pipeline in which we will push the code to GitHub and from the GitHub we will pull the code through Jenkins and after pulling the code from the GitHub we will test the code on SonarQube which is a static code analysis tool  on which we can scan the bugs and vulnerabilities of the code and also we can add the rules,record regarding the scanning and then after scanning the code if our code pass we will deploy it on docker and everything will be done on ec2 instance so we will need 3 ec2 instance one for Jenkins,one for SonarQube,one for Docker deployment so then after deploying in on Docker we will access it on our browser just to verify if its working or not




