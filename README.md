# jenkins-master-and-slave-history
slave history 
==========================
 1  amazon-linux-extras install java-openjdk11 -y
    2  yum install java-1.8.0-openjdk maven -y
    3  update-alternatives --config java
    4  java -version
    5  java --version
    6  cd /
    7  ll
    8  chmod 777 opt
    9  ll
   10  cd
   11  update-alternatives --config java
   12  git -version
   13  git --version
   14  git -v
   15  yum install git -y
   16  cd /opt/workspace/
   17  ls
   18  cd java-project
   19  ls
   20  yum install tree -y
   21  tree
   22  cd
   23  wget https://dlcdn.apache.org/tomcat/tomcat-9/v9.0.82/bin/apache-tomcat-9.0.82.tar.gz
   24  tar -xzf apache-tomcat-9.0.82.tar.gz
   25  vim apache-tomcat-9.0.82/conf/tomcat-users.xml
   26  vim apache-tomcat-9.0.82/webapps/manager/META-INF/context.xml
   27  ./apache-tomcat-9.0.82/bin/startup.sh
   28  history

master history 
==============
  1  git -v
    2  yum install git -y
    3   sudo wget -O /etc/yum.repos.d/jenkins.repo https://pkg.jenkins.io/redhat-stable/jenkins.repo
    4    sudo rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io-2023.key
    5  amazon-linux-extras install java-openjdk11 -y
    6  yum install jenkins -y
    7  service  jenkins start
    8  cat /var/lib/jenkins/secrets/initialAdminPassword
    9  java --version
   10  history





   slave history 
   ==============
    1  vim a.sh
    2  sh a.sh
    3  yum install git -y
    4  amazon-linux-extras install java-openjdk11 -y
    5  update-alternatives --config java
    6   wget https://dlcdn.apache.org/tomcat/tomcat-9/v9.0.82/bin/apache-tomcat-9.0.82.tar.gz
    7  tar -xzf apache-tomcat-9.0.82.tar.gz
    8  vim apache-tomcat-9.0.82/conf/tomcat-users.xml
    9  vim apache-tomcat-9.0.82/webapps/manager/META-INF/context.xml
   10  ./apache-tomcat-9.0.82/bin/startup.sh
   11  yum install git -y
master histor
==============
 1  vim a.sh
    2  sh a.sh
    3  2
    4  sh a.sh
    5  update-alternatives --config java
    6  service jenkins start

