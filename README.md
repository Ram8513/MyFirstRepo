Jenkins script 
sudo wget -O /etc/yum.repos.d/jenkins.repo https://pkg.jenkins.io/redhatstable/jenkins.repo
sudo rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io-2023.key amazon-linux-extras install java-openjdk11 -y yum install jenkins -y  systemctl restart jenkins
