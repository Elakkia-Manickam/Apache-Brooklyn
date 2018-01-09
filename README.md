# Apache-Brooklyn
Apache Brooklyn steps to launch in Red hat

#  Java Runtime Environment (JRE) installed (version 7 or later)
# link to follow
http://linuxtechlab.com/installing-java-7-8-centosrhel-7/

# step 1 : (Install JAVA)
yum install java-1.7.0-openjdk-devel

# step 2 : (Test the version of JAVA)
java –version

# step 3 : Chenge the environmant settings (temporarily)
$ JAVA_HOME=/usr/java/jdk1.7.0_05
$ export JAVA_HOME
$ PATH=$JAVA_HOME/bin:$PATH
$ export PATH

# step 4 : change the environment settings (permanently)
$ vi .bashrc
$ JAVA_HOME=/usr/java/jdk1.7.0_05
$ PATH=$JAVA_HOME/bin:$PATH

