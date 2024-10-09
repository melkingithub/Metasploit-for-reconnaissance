# Metasploit-for-reconnaissance
# Metasploit
Metasploit for reconnaissance in pentesting

# AIM:
To get introduced to Metasploit Framework and to  perform reconnaissance  in pentesting .

## DESIGN STEPS:

### Step 1:
Install kali linux either in partition or virtual box or in live mode

### Step 2:
Investigate on the various categories of tools as follows:

### Step 3:
Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Find out the ip address of the attackers system

## OUTPUT:
![image](https://github.com/user-attachments/assets/09668381-d565-4e28-9df8-7dcf3f3491f9)

## Invoke msfconsole
## OUTPUT:
![image](https://github.com/user-attachments/assets/47d32faf-6c0f-47c3-89b3-b0f8e5d9472f)

Type help or a question mark "?" to see the list of all available commands you can use inside msfconsole.
![image](https://github.com/user-attachments/assets/b65f2416-5e86-4550-8aa2-3a0cb4daa507)

## Port scanning:
## msf > nmap -sT 192.168.1810/24-p1-1000
![image](https://github.com/user-attachments/assets/cd84661c-4803-4c2d-abc5-52c2853b1f65)

## msf > db_nmap 192.168.181.0/24
![image](https://github.com/user-attachments/assets/70689229-3021-4ae1-beef-874369a068ed)

## kali > ls-l
![image](https://github.com/user-attachments/assets/c8d53105-3a10-4654-acef-0dd193e905f1)

## search
![image](https://github.com/user-attachments/assets/25bd0399-9327-48a5-92eb-8c75553c9b32)

## info
![image](https://github.com/user-attachments/assets/61274cda-176d-4bb8-afae-ce6d741c1182)

## MYSQL ENUMERATION
## db_nmap -sV -sC -p 3306 <metasploitable_ip_address>
![image](https://github.com/user-attachments/assets/b7238c2e-c491-46c8-9dff-eba2119d0bf5)

## search
![image](https://github.com/user-attachments/assets/ed40e38a-88b1-4638-b20a-373ceb7cba3a)

##  use 11 Or: use auxiliary/scanner/mysql/mysql_version
![image](https://github.com/user-attachments/assets/c31cf0cd-8c53-4732-a704-0e6c4ef3fa58)

## Use the set rhosts command to set the parameter and run the module, as follows :
![image](https://github.com/user-attachments/assets/5e33f9bd-1ecc-4544-a5f0-0b0027c64fa6)

## After scanning, you can also brute force MySQL root account via Metasploit's auxiliary(scanner/mysql/mysql_login) module.
![image](https://github.com/user-attachments/assets/87a68c48-8e23-4e57-9c13-28ae8d09596b)

## /usr/share/wordlists: set PASS_FILE /usr/share/wordlistss/rockyou.txt 
![image](https://github.com/user-attachments/assets/d0abc8c0-049e-4426-a9aa-1e9bc300872e)
![image](https://github.com/user-attachments/assets/09375ac1-c71c-4125-8e4b-f6776fba746d)

## RESULT:
The Metasploit framework for reconnaissance is  examined successfully
