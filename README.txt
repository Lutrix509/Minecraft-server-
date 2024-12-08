On terminal


Sudo apt update 


Sudo apt install openjdk-8-jdk -y


/usr/lib/jvm/java-8-openjdk-amd64/bin/java


export JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64
export PATH=$JAVA_HOME/bin:$PATH


source ~/.bashrc


On the start.sh file


/usr/lib/jvm/java-8-openjdk-amd64/bin/java -Xmx2G -Xms2G -jar server.jar nogui


That on the terminal
 
chmod +x start.sh


To start the server put command in the terminal 


./start.sh





