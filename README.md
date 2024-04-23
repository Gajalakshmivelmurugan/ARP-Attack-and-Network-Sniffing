## ARP-Attack-and-Network-Sniffing
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
![Screenshot 2024-04-23 232545](https://github.com/Gajalakshmivelmurugan/ARP-Attack-and-Network-Sniffing/assets/144871940/047e70d2-9ec1-4f39-bb4e-8445cc5d6389)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![Screenshot 2024-04-23 232602](https://github.com/Gajalakshmivelmurugan/ARP-Attack-and-Network-Sniffing/assets/144871940/7f2b3107-e994-4fec-9c0a-85bb814e7638)


 dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![Screenshot 2024-04-23 232616](https://github.com/Gajalakshmivelmurugan/ARP-Attack-and-Network-Sniffing/assets/144871940/cb7a303c-0551-49b5-91dd-8a6803049470)




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:


![Screenshot 2024-04-23 232627](https://github.com/Gajalakshmivelmurugan/ARP-Attack-and-Network-Sniffing/assets/144871940/4ebf8d85-86e2-4735-bd2e-baeab392c654)


Invoke the wireshark and examine the various menus  and controls of the tool:
![Screenshot 2024-04-23 232639](https://github.com/Gajalakshmivelmurugan/ARP-Attack-and-Network-Sniffing/assets/144871940/d0a17541-8d82-4c2a-8b5a-332f00802f62)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
