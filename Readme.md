su jenkins
vi sudo
vi /etc/ssh/sshd_config

sudo apt install openjdk-8-jdk
java -version

vi /etc/environmet
export JAVA_HOME="/usr/lib/jvm/java-1.8.0-openjdk-amd64"

export PATH=$PATH:$JAVA_HOME/bin

export M2_HOME="/usr/share/maven"

source /etc/environmet 

vi /etc/profile

export JAVA_HOME="/usr/lib/jvm/java-1.8.0-openjdk-amd64"

export PATH=$PATH:$JAVA_HOME/bin

export M2_HOME="/usr/share/maven"

source /etc/profile



for perminently add
vi ~/.bashrc
export JAVA_HOME="/usr/lib/jvm/java-1.8.0-openjdk-amd64"
export PATH=$PATH:$JAVA_HOME/bin
export M2_HOME="/usr/share/maven"

