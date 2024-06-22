# Audio-Video-Calling-GUI-java
To run Server:

Step 1: place project directory AudioVideo in c:\ drive

Step 2: open command prompt and run following commands on server computer

	prompt> cd \
	prompt> c:
	c:\>cd AudioVideo
	c:\AudioVideo>set CLASSPATH=%CLASSPATH%;lib\*;.;
	c:\AudioVideo>javac CNProjectChatServer.java
	c:\AudioVideo>java CNProjectChatServer


To run Client:

Step 1: place project directory AudioVideo in c:\ drive

Step 2: open source code in file CNProjectChatClient.java
	and find the code "public static final String SERVER_IP = "192.168.43.207";"
        and update IP address of server computer in this code.

Step 3: open command prompt and run following commands on client computer

	prompt> cd \
	prompt> c:
	c:\>cd AudioVideo
	c:\AudioVideo>set CLASSPATH=%CLASSPATH%;lib\*;.;
	c:\AudioVideo>javac CNProjectChatClient.java
	c:\AudioVideo>java CNProjectChatClient

Cautions:
1. Run Server & Client on two different computers to avoid webcam, microphone and speakers conflict
2. Run Server first
