# aws-cmd

sudo su

sudo yum list installed

sudo yum install java-1.8.0

sudo yum install jenkins -y

sudo service Jenkins start

sudo yum install -y java-1.8.0-openjdk.x86_64

sudo /usr/sbin/alternatives --set java /usr/lib/jvm/jre-1.8.0-openjdk.x86_64/bin/java

sudo /usr/sbin/alternatives --set javac /usr/lib/jvm/jre-1.8.0-openjdk.x86_64/bin/javac

https://www.digitalocean.com/community/tutorials/how-to-install-jenkins-on-ubuntu-16-04
https://www.youtube.com/watch?v=BfKwJPHJGkI
$ wget -q -O - http://pkg.jenkins-ci.org/debian/jenkins-ci.org.key | sudo apt-key add -
http://www.bogotobogo.com/DevOps/Jenkins/Jenkins_Install.php
deb http://pkg.jenkins-ci.org/debian-stable binary/
or
$ sudo sh -c 'echo deb http://pkg.jenkins-ci.org/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list'
