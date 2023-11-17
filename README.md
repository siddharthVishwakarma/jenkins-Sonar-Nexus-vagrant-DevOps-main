# Jenkins SonarQube Nexus vagrant machines
Automating the setup of 3 machines Nexus , Sonarqube , Jenkins 
this will facilitate testing complete pipelines for Devops

# download the files 
git clone https://github.com/siddharthVishwakarma/jenkins-Sonar-Nexus-vagrant-DevOps-main.git

# run the below commands in side the download directory 
vagrant up 

# to access the machines 
- vagrant ssh jenkins
- vagrant ssh nexus 
- vargrant ssh sonar

# Machines web ports 
- jenkins http port is 8080 
- Sonarqube port is 9000 & 80 user/pass is : admin/admin
- nexus port 8081
