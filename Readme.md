  variables setup in ubuntu
  ==========================
  
  JAVA INSTALLATION
  -----------------
 java -version
 sudo apt-get install openjdk-8-jdk -y
 whereis java
/usr/lib/jvm/java-1.8.0-openjdk-amd64
 JAVA_HOME=/usr/lib/jvm/java-1.8.0-openjdk-amd64
 PATH=$HOME/bin:$PATH:$JAVA_HOME
 export PATH
 source ~/.profile
 echo $PATH

MAVEN INSTALLATION
------------------
 sudo apt-get install maven
 whereis maven
/usr/share/maven
 vi ~/.profile
 M2_HOME=/usr/share/maven
 PATH=$HOME/bin:$PATH:$JAVA_HOME:$M2_HOME
 export PATH
 source ~/.profile
 echo $PATH
 mvn --version


  variables setup in Amazon Linux
 =================================
 
  JAVA INSTALLATION
  -----------------
 sudo yum install java-1.8*
 find /usr/lib/jvm/java-1.8* |head -n 3
 whereis java
 /usr/lib/jvm/java-1.8-openjdk-1.8.0.272.b10-1.amzn2.0.1.x86_64
 vi ~/.bash_profile
 JAVA_HOME=/usr/lib/jvm/java-1.8-openjdk-1.8.0.272.b10-1.amzn2.0.1.x86_64
 PATH=$PATH:$HOME/bin:$JAVA_HOME
 export PATH 
 source ~/.bash_profile
 echo $PATH


MAVEN INSTALLATION
------------------
 cd /opt
 wget https://dlcdn.apache.org/maven/maven-3/3.8.4/binaries/apache-maven-3.8.4-bin.tar.gz
 tar -xvzf apache-maven-3.8.4-bin.tar.gz
apache-maven-3.8.4
 whereis maven
/opt/apache-maven-3.8.4
 vi ~/.bash_profile
 M2_HOME=/opt/apache-maven-3.8.4
 M2=/opt/apache-maven-3.8.4/bin
 PATH=$PATH:$HOME/bin:$JAVA_HOME:$M2:$M2_HOME
 export PATH 
 source ~/.bash_profile
 echo $PATH



