  variables
  =========
java -version

mvn -V

temperory variable

vi /etc/environmet

export JAVA_HOME="/usr/lib/jvm/java-1.8.0-openjdk-amd64"

export PATH=$PATH:$JAVA_HOME/bin

export M2_HOME="/usr/share/maven"

export PATH=${M2_HOME}/bin:${PATH}


source /etc/environmet 



permanent  variables
===================



vi ~/.profile

export JAVA_HOME="/usr/lib/jvm/java-1.8.0-openjdk-amd64"

export PATH=$PATH:$JAVA_HOME/bin

export M2_HOME="/usr/share/maven"

export PATH=${M2_HOME}/bin:${PATH}

source /etc/profile







vi ~/.bashrc

export JAVA_HOME="/usr/lib/jvm/java-1.8.0-openjdk-amd64"

export PATH=$PATH:$JAVA_HOME/bin

export M2_HOME="/usr/share/maven"

export PATH=${M2_HOME}/bin:${PATH}

