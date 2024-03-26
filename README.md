![Screenshot 2024-03-26 090914](https://github.com/Kaviarasu510/Information-Gathering/assets/119392695/be0fa87d-9398-402e-b82c-ee395025a007)![Screenshot 2024-03-19 085934](https://github.com/Kaviarasu510/Information-Gathering/assets/119392695/967afd09-559b-4e6f-8a9b-e8e9802dce1b)# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

# Pen Test Tools Categories:  

Following Categories of pen test tools are identified for information gathering:

### Footprinting

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.

http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

### output

![VirtualBox_mine_05_03_2024_23_39_18](https://github.com/Kaviarasu510/Information-Gathering/assets/119392695/b4e4bd9a-4d85-4257-9501-1877ea463a11)

### Finding IP address:

ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.

### Output

![VirtualBox_mine_05_03_2024_23_42_43](https://github.com/Kaviarasu510/Information-Gathering/assets/119392695/c6eabb5f-8644-4c9a-93c9-294a52835687)

### Finding Hosting Company

get further detail by using ip2location.com website.

### Output

![Screenshot 2024-03-19 085514](https://github.com/Kaviarasu510/Information-Gathering/assets/119392695/ecd366be-1f36-4546-af37-7656f7c92eda)

### History of the website:

get further detail by using https://web.archive.org/

### output

![Screenshot 2024-03-19 085934](https://github.com/Kaviarasu510/Information-Gathering/assets/119392695/765b8084-3480-4b58-a2f8-72356d0f76ef)

# Webserver Fingerprinting

### Netcat:
sudo nc facebook.com 80
GET / HTTP/1.1
Host: facebook.com

### output

![Screenshot 2024-03-26 085015](https://github.com/Kaviarasu510/Information-Gathering/assets/119392695/9deca507-48ef-4e4c-b6da-cceda42364e4)

### Nmap:    
nmap -p 21 -sv --script=banner ftp.vim.org

### output
![Screenshot 2024-03-26 085239](https://github.com/Kaviarasu510/Information-Gathering/assets/119392695/ea6c0e22-7881-4433-b816-ed859e99c9cd)

### Whatweb
whatweb gmail.com

![Screenshot 2024-03-26 085537](https://github.com/Kaviarasu510/Information-Gathering/assets/119392695/35d0cdf0-e991-418c-a0df-99ac3b85ec71)

### httprint
httprint -h 192.168.17.106 -s /usr/share/httprint/signatures.txt -p0 |more

### Output

![Screenshot 2024-03-26 090716](https://github.com/Kaviarasu510/Information-Gathering/assets/119392695/a5bbce23-5eda-4662-840f-d617669cc0c0)

# Tracing The Location

### TCP Traceroute:
sudo traceroute -T www.gmail.com

### Output

![Screenshot 2024-03-26 090914](https://github.com/Kaviarasu510/Information-Gathering/assets/119392695/68d8f647-7cf0-4793-bfc4-c9ae27b73f6a)

### UDP Traceroute:
sudo traceroute -U www.gmail.com

### Output

![Screenshot 2024-03-26 091007](https://github.com/Kaviarasu510/Information-Gathering/assets/119392695/e7c5e7bb-a4ee-4348-b4a9-c3af8f50534f)

## Result

THe information gathering techniques tools and procedure were identified successfully.
