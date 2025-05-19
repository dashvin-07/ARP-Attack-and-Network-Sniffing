# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks
# AIM:
To explore network sniffing and ARP Attacks
## STEPS:
### Step 1:
Install kali linux either in partition or virtual box or in live mode
### Step 2:
Investigate on the various categories of tools as follows:
### Step 3:
Open terminal and try execute some kali linux commands
## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:
![1](https://github.com/user-attachments/assets/05246049-1672-4142-a2c5-cbe068d934c1)
![2](https://github.com/user-attachments/assets/81e43d8f-0b42-4ec2-999c-16d853e1fd68)
From kali linux issue the command :sudo arpspoof -i eth0 -t
## OUTPUT:
![3](https://github.com/user-attachments/assets/4c4b4953-421d-4a12-bd20-1d4db5af0bcc)
dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![4](https://github.com/user-attachments/assets/2b44e4c3-7779-4d55-aca9-b9aa115e4568)
In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![5](https://github.com/user-attachments/assets/279c1219-29f4-42c5-be51-bc0aa1bd77bf)
Invoke the wireshark and examine the various menus  and controls of the tool:
## OUTPUT:
![6](https://github.com/user-attachments/assets/acf45b34-81b4-4e99-9f5e-5e706afb2ca6)
## Ettercap:
Ettercap supports active and passive dissection of many protocols (even encrypted ones) and includes many feature for network and host analysis. Ettercap can be used as sniffing tool as illustrated below:
![7](https://github.com/user-attachments/assets/1feffc1f-d6e2-41c7-8d22-c6719a9c8977)
## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
