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
![1](https://github.com/user-attachments/assets/6745e441-c717-45ff-ac2e-46b2eb5d1ae3)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![2](https://github.com/user-attachments/assets/24756fb9-723b-4324-ad51-af5535e1ab67)


 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![3](https://github.com/user-attachments/assets/5e9e7797-bb83-4832-927d-98d4680ed55d)




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![4](https://github.com/user-attachments/assets/cb8e16d1-4a64-437b-929d-d37abe0c1411)



Invoke the wireshark and examine the various menus  and controls of the tool:
![5](https://github.com/user-attachments/assets/ae74904c-7602-491e-947c-9b47f988e647)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
