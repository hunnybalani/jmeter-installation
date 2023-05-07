# jmeter-installation

Step 1: Installe Apache JMeter

https://jmeter.apache.org/download_jmeter.cgi

Step 2: Add perfmon plugin in JMeter
   1. Download and add to JMeter lib and ext folder    
   2. Unzip the contents and add jar files from lib and ext folders to their respective folders in apache-jmeter
   
   https://jmeter-plugins.org/wiki/PerfMon/

Step 3: Install the perfmon server agent

https://github.com/undera/perfmon-agent/blob/master/README.md

Step 4: Start the perfmon server agent
   
   Mac/linux - terminal - sh startAgent.sh
   
   Windows - startAgent.bat
   
   Check if the client can talk to server via port 4444

Step 5: Open jmeter using, i.e. executing the sh file in bin folder
   
   Mac/linux - terminal - sh jmeter.sh
   
   Windows - jmeter.bat
   
Step 6: Open the test set 
  
  https://github.com/hunnybalani/jmeter-installation/blob/main/loadtest.jmx
  
Step 7: Add the csv files mentioned in the test path

Step 8: Run and Validate
