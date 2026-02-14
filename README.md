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

<img width="1471" height="943" alt="image" src="https://github.com/user-attachments/assets/9d469f96-d657-4086-b11c-fa6a54c9c2ac" />


The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT

<img width="540" height="183" alt="Screenshot 2026-02-14 132925" src="https://github.com/user-attachments/assets/1a124c7c-33cb-447a-bdb7-3c0540825500" />


It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT

<img width="644" height="281" alt="Screenshot 2026-02-14 133907" src="https://github.com/user-attachments/assets/9a2f05d7-c912-477b-b8ff-ddd4b651fb13" />


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT

<img width="592" height="189" alt="Screenshot 2026-02-14 133856" src="https://github.com/user-attachments/assets/0914c7b8-5329-4d36-becf-2a8f2106d7f1" />


It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT

<img width="461" height="131" alt="Screenshot 2026-02-14 133844" src="https://github.com/user-attachments/assets/6900e5f8-4367-4e32-9d33-b37617514d94" />



It shows the following screen in which the option Google can be selected:
## OUTPUT

<img width="837" height="485" alt="Screenshot 2026-02-14 133828" src="https://github.com/user-attachments/assets/8e6f4cc4-3887-4627-8bbe-b67d66589522" />




SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT

<img width="1692" height="153" alt="image" src="https://github.com/user-attachments/assets/8a9461ff-a839-43ed-a149-8c0638731723" />



In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT
<img width="1919" height="1090" alt="image" src="https://github.com/user-attachments/assets/4c4a71bd-4a0a-4020-b016-18ab81bfda8f" />


SET logs the information regarding the Google credentials:
## OUTPUT

<img width="1643" height="422" alt="Screenshot 2026-02-14 133603" src="https://github.com/user-attachments/assets/e2c1d62a-2f6e-4b1b-bfe3-693f18abbeb7" />






## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
