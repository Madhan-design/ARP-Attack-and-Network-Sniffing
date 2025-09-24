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
<img width="632" height="1077" alt="Screenshot 2025-09-24 203652" src="https://github.com/user-attachments/assets/d946558a-2a78-41f7-9e6d-6f7832d2a448" />

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
<img width="960" height="458" alt="Screenshot 2025-09-24 203725" src="https://github.com/user-attachments/assets/c8b40c46-2e10-492b-b6cf-ba0594a0ebe8" />


 dsniff:




In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
<img width="1176" height="508" alt="4 4" src="https://github.com/user-attachments/assets/0ae2b9a8-58af-4b86-91e0-1ba0a7b66397" />




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
<img width="1171" height="173" alt="4 5" src="https://github.com/user-attachments/assets/45a07e9a-4bc7-4905-9882-104d70fdc2a4" />
<img width="1277" height="531" alt="4 6" src="https://github.com/user-attachments/assets/6546bfb0-acdd-4cce-a1b5-94328b01d40c" />



Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
