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
## OUTPUT
<img width="615" height="781" alt="image" src="https://github.com/user-attachments/assets/d56b4aa9-a681-46f6-87a9-7bd389d66053" />



The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT
<img width="1035" height="536" alt="image" src="https://github.com/user-attachments/assets/a77edaef-05e2-4a25-8d5e-1b30ea272386" />



It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT
<img width="1034" height="539" alt="image" src="https://github.com/user-attachments/assets/ee2d4892-4f88-46e9-a054-6379da9c9d19" />



The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT
<img width="1037" height="543" alt="image" src="https://github.com/user-attachments/assets/93c9c4ed-f566-45fa-b848-8c2f9764a95f" />

 

It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT
<img width="1034" height="542" alt="image" src="https://github.com/user-attachments/assets/1ea7f169-2089-4b2d-a95e-ac1b6342f53d" />




It shows the following screen in which the option Google can be selected:
## OUTPUT
<img width="1036" height="546" alt="image" src="https://github.com/user-attachments/assets/b380f072-dde7-4567-b73c-53e3bab99723" />





SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT
<img width="1034" height="545" alt="image" src="https://github.com/user-attachments/assets/3bb5b54c-7eba-4316-bc06-0944af72a17b" />




In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT
<img width="1034" height="584" alt="image" src="https://github.com/user-attachments/assets/18ccd63d-6bb5-4d29-a8ca-49de588d43ec" />


SET logs the information regarding the Google credentials:
## OUTPUT
<img width="1040" height="177" alt="image" src="https://github.com/user-attachments/assets/6bc460e0-e599-415b-894e-af8387ef7853" />



SET logs the information in the xml file under /root/.set directory:
## OUTPUT
<img width="1033" height="541" alt="image" src="https://github.com/user-attachments/assets/fa9e766d-57b5-4ece-bebf-fb22e7cb09b3" />












## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
