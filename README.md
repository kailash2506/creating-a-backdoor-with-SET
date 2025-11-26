# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

## DATE: 03/11/25


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
The command `sudo setoolkit` in the prompt gives menu with set prompt:  
## OUTPUT:  
<img width="538" height="637" alt="image" src="https://github.com/user-attachments/assets/5e3c510f-40b5-46d3-bd70-6fb01cf2ef35" />


The command `sudo setoolkit` in the prompt gives menu with set prompt. Select menu 1 for Social Engineering Attacks.  
It displays the following menu and select 2 for Website Attack Vectors:  
## OUTPUT:  
<img width="326" height="248" alt="image" src="https://github.com/user-attachments/assets/1237cdf3-0fc6-498a-a572-ab1ece6f7cd8" />


The website Attack Vectors displays the following menu. In this menu, 3 for Credential Harvester Attack Method is selected:  
## OUTPUT:  
<img width="353" height="164" alt="image" src="https://github.com/user-attachments/assets/72e5eccc-21a9-41ef-a9d5-8cc682b7b9a2" />


The Credential Harvester Attack Method displays the following menu. In this menu, 1 for Web Templates is selected:  
## OUTPUT:  
<img width="323" height="153" alt="image" src="https://github.com/user-attachments/assets/54bbeeb7-cac7-4b7e-bf58-2e203197741b" />


The Credential Harvester Attack Method displays the following menu. In this menu, 1 for Web Templates is selected.  
It shows the following screen in which the IP address of the attacker needs to be given (default value):  
## OUTPUT:  
<img width="771" height="391" alt="image" src="https://github.com/user-attachments/assets/e5e25d62-89c9-49be-876a-95d72ef5b6a6" />


It shows the following screen in which the option Google can be selected:  
## OUTPUT:  
<img width="485" height="349" alt="image" src="https://github.com/user-attachments/assets/69be793f-4ebf-4465-9f3e-469f771ffbe5" />


SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:  
## OUTPUT:  
<img width="565" height="172" alt="image" src="https://github.com/user-attachments/assets/fd2d030b-d489-4255-a82d-ac0265a4f664" />


In Windows IE, on giving the URL `http://192.168.1.2`, the fake Google page is displayed. The victim can enter the username and password.  
## OUTPUT:  
<img width="549" height="778" alt="image" src="https://github.com/user-attachments/assets/d83b1351-f6ab-4c92-b2e2-9038fb0f8e3f" />


SET logs the information regarding the Google credentials:  
## OUTPUT:  
<img width="569" height="284" alt="image" src="https://github.com/user-attachments/assets/f5f02b27-f0d8-474c-ba6d-d2e7e93ea827" />


SET logs the information in the XML file under `/root/.set` directory:  
## OUTPUT:  
<img width="746" height="478" alt="image" src="https://github.com/user-attachments/assets/73835511-3ac9-4785-abfb-bdf2e2456354" />


## RESULT:
The Social Engineering Toolkit (SET) is used to create a backdoor and is examined successfully.
