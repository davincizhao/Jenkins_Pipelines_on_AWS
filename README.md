## Install Jenkins in Linux(Centos)

```
sudo wget -O /etc/yum.repos.d/jenkins.repo https://pkg.jenkins.io/redhat/jenkins.repo
sudo rpm --import https://pkg.jenkins.io/redhat/jenkins.io.key
yum install jenkins

sudo systemctl start jenkins
systemctl status jenkins
sudo systemctl enable jenkins
```
### Setting Up Jenkins 
```
http://your_ip_or_domain:8080
```
Use the following command to print the password on your terminal:
```
sudo cat /var/lib/jenkins/secrets/initialAdminPassword
```
### Login Jenkins in browser

### Install blue Ocean plugin in Jenkins
"Manage Jenkins"-->"Manage Plugins"-->"Available" label--> input "blue ocean" in search.
