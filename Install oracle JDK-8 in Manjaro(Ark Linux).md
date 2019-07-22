## Install oracle jdk8 in Manjaro OS(Ark Linux):
* Download jdk8 ***Linux X64 .tar.gz*** file from oracle website 

	Link: https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html

* Extract it to desired location
* Open File Manager and enable hidden files
* Open .profile from Home/'your_username' ***(Replace your_username with your PC username)***
---
**Edit the .profile and add as following at the end of the file.**

***Replace the location with your jdk8 extracted location***
    

	export JAVA_HOME=/home/bs295/Applications/jdk1.8.0_221
	PATH=$JAVA_HOME/bin:$PATH
	export PATH
    
---
**Edit .bashrc and add add as following at the end of the file.**

***Replace the location with your jdk8 extracted location***

	export JAVA_HOME=/home/bs295/Applications/jdk1.8.0_221
	PATH=$JAVA_HOME/bin:$PATH
	export PATH
  
  --- 
  After doing run these commands for check environment
  
    java -version
    javac -version
    
You should see like this
    
    java version "1.8.0_221"
    Java(TM) SE Runtime Environment (build 1.8.0_221-b11)
    Java HotSpot(TM) 64-Bit Server VM (build 25.221-b11, mixed mode)
---
    javac 1.8.0_221
  
