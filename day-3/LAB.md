## Task 1 - Create EC2 instance and connect from laptop

- Create an EC2 insatnce, secure the .pem file - use ubuntu freetier
- SSH -t <.pem> ubuntu@externalip
- sudo su -
- apt update

## Task 2 - Install Jenkins

- apt install openjdk-11-jdk
- java -version
- Install Jenkins from jenkins docs
- systemctl status jenkins

## Task 3 - Access Jenkins

- Jenkins server runs on 8080 port
- Create a inbound rule for the EC2 instance to allow tcp 8080
- http://externalip:8080
- Get the default password
- Install recoemnded plugins
