# CI CD Deployment using Ansible CM Tool


## Steps for Installation of Jenkins

1. sudo apt install jenkins
2. sudo apt install openjdk-11-jdk
3. Add 8080 port in EC2 instance SG
4. check http://`<privateIP>:8080`

## Steps for Installation of Ansible

1. sudo apt install ansible

## Configure Jenkins to use ansible

1. go to manage plugins and install ansible without restart
2. configure ansible in Global Tool Configuration
3. configure git in Global Tool Configuration
