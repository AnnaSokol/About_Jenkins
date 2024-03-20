# About_Jenkins
## Jenkins is an open source automation server. It helps automate the parts of software development related to building, testing, and deploying, facilitating continuous integration, and continuous delivery.
## Install for Ubuntu/Debian 
# Steps to install:
1. check the version of Ubuntu/Debian
```
cat /etc/os-release
```
2. check the version of Java, we need 8 Version / install java 8
```
java -version
sudo apt-get update
sudo apt-get install openjdk-8-jre
```
3. Install Jenkins
```
https://www.jenkins.io/doc/book/installing/linux/#debianubuntu
```
4. check status of Jenkins
```
sudo service jenkins status
```
5. stop / start Jenkins 
```
sudo service stop 
sudo service start
```
## Jenkins is now the web server on port 8080.
```
sudo cat /var/lib/jenkins/secrets/initialAdminPassword
```