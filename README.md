# Red-Vs-Blue-Team
Capstone Engagement Assessment
Red Vs Blue team project is cybersecurity assessment technique which simulate real-life cyber attacks 
against organisation to locate weaknesses, exploit vulnerabilities and improve information security by 
maintaining internal network defense against all cyber attacks and threats.


As a red team member, initially played a role of attacker (blackhat hacker) gaining unauthorised access to 
capstone VM, accessed hidden directory on web server and uploaded PHP reverse shell payload to establish a Meterpreter 
session allowing for exfiltration of company data. 
I then performed the role of a Blue Team analyzing the Kibana logs to summarize the incident before making system hardening recommendations. 
By performing all of the roles, this exercise gave us good insight into both offensive and defensive security roles.

This repository contains a readout of this activity containing the following details:

       Network Topology
       Network Reconnaissance
       Vulnerability Assessment
       Exploit summary
       Incident Analysis
       Mitigation Strategies
  

Network Diagram: 

![Red Vs Blue NW Diagram](https://github.com/MedhaParte/Red-Vs-Blue-Team/blob/main/Red%20Vs%20Blue-NW.jpg)

  
The configuration details of each machine may be found below: 

|     Name          	|     Function      	|     IP Address       	|     Operating   System    	|
|-------------------	|-------------------	|----------------------	|---------------------------	|
|     Hypervisor    	|     Hypervisor    	|     192.168.1.1      	|     Windows               	|
|     Kali          	|     Attack VM     	|     192.168.1.90     	|     Kali Linux            	|
|     Capstone      	|     Target VM     	|     192.168.1.105    	|     Ubuntu Linux          	|
|     ELK           	|     Logging       	|     192.168.1.100    	|     Ubutnu Linux          	|

Benefits of red team/blue team exercises : 

It help organizations to identify points of vulnerability and determine areas of improvement in defensive incident response processes. 
Build the organization’s first-hand experience about how to detect and contain a targeted attack.
Develop response and remediation activities to return the environment to a normal operating state.
