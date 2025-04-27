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
![image](https://github.com/user-attachments/assets/decd3ceb-beb7-44da-a00d-3a3aed58fae9)


From kali linux issue the command : sudo arpspoof -i eth0 -t
## OUTPUT:
![image](https://github.com/user-attachments/assets/bec1ae59-98fe-4166-8ce3-ab81587cdaae)


 dsniff:n Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![image](https://github.com/user-attachments/assets/43a36db3-7c1c-4e15-94e1-62e3ca042bbc)



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/user-attachments/assets/79c0f802-5be5-47cc-8d73-63ac976f0802)



Invoke the wireshark and examine the various menus  and controls of the tool:
![image](https://github.com/user-attachments/assets/1283688d-5d54-41bd-ba3b-95d01235fd12)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
