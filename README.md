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
![WhatsApp Image 2023-11-06 at 09 14 11_7cabb1f1](https://github.com/KothaiKumar/ARP-Attack-and-Network-Sniffing/assets/121215739/91b79f31-7f1a-4eda-a4b8-4f82fcdda25b)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/KothaiKumar/ARP-Attack-and-Network-Sniffing/assets/121215739/0c40aac9-ccbc-49c0-9154-418f7c649088)


## dsniff:
 
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/KothaiKumar/ARP-Attack-and-Network-Sniffing/assets/121215739/4718883e-dbfb-4a6a-8891-2d49049d2fdd)

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/KothaiKumar/ARP-Attack-and-Network-Sniffing/assets/121215739/f5c4e176-3acd-4d24-b8ed-07c1cd5ba165)


## Invoke the wireshark and examine the various menus  and controls of the tool:
![image](https://github.com/KothaiKumar/ARP-Attack-and-Network-Sniffing/assets/121215739/a05a5d98-0879-408f-9485-1569d23b1099)

## ettercap :
ettercap supports active and passive dissection of many protocols and includes many features for network and host analysis.

![image](https://github.com/KothaiKumar/ARP-Attack-and-Network-Sniffing/assets/121215739/76345dc1-e907-450f-95b5-e80623bd7ec3)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
