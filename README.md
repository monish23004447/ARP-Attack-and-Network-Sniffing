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
![Screenshot 2025-04-17 101242](https://github.com/user-attachments/assets/df9ed816-e626-473b-b908-8e9335f6699f)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![Screenshot 2025-04-24 094608](https://github.com/user-attachments/assets/d25772c7-f872-4a15-ba49-f52992d877f1)


 dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![435376523-cae623b8-5cea-46ea-8ce2-4ca2966806d1](https://github.com/user-attachments/assets/46680b15-dc80-4de6-971b-1fdea5048305)



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![435377329-cc675d18-debe-42a3-8b3c-58fecac61d5f](https://github.com/user-attachments/assets/5da7a394-806a-4542-90c9-a29da63b5e48)

Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
