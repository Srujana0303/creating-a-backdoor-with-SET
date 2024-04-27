# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:

![image](https://github.com/Srujana0303/creating-a-backdoor-with-SET/assets/132996836/bfaaab37-22c6-4b90-b1bb-4af51cddd2dd)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

![image](https://github.com/Srujana0303/creating-a-backdoor-with-SET/assets/132996836/02e637d5-a3d2-4dc6-ac95-ec498c06e2d0)

It displays the following menu and select 2 for Website Attack Vectors:

![image](https://github.com/Srujana0303/creating-a-backdoor-with-SET/assets/132996836/ed8c8f8d-7777-44cf-8eb7-eae2d0cd8e2b)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![image](https://github.com/Srujana0303/creating-a-backdoor-with-SET/assets/132996836/3252a85a-26e4-4fc9-b90a-7c4e54ea4577)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![image](https://github.com/Srujana0303/creating-a-backdoor-with-SET/assets/132996836/31e480a9-de95-47af-baa4-d28384d0e705)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![image](https://github.com/Srujana0303/creating-a-backdoor-with-SET/assets/132996836/87c01892-0c3e-47ca-845b-35f52e8260eb)

It shows the following screen in which the option Google can be selected:

![image](https://github.com/Srujana0303/creating-a-backdoor-with-SET/assets/132996836/66b9d268-ba42-49f3-878d-acd31194ef98)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![image](https://github.com/Srujana0303/creating-a-backdoor-with-SET/assets/132996836/19c966ed-8a4d-47b5-855e-cb0c02decece)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the

![image](https://github.com/Srujana0303/creating-a-backdoor-with-SET/assets/132996836/e9edc0fe-cb41-41ec-bf3b-7a97186b3467)

SET logs the information regarding the Google credentials:
username and password 

![image](https://github.com/Srujana0303/creating-a-backdoor-with-SET/assets/132996836/feb47ff8-1fd5-4685-bd49-958c92c3e77c)

SET logs the information in the xml file under /root/.set directory:

![image](https://github.com/Srujana0303/creating-a-backdoor-with-SET/assets/132996836/4c394e29-786b-44d7-9773-77b555af9b95)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
