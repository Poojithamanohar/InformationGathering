# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

Pen Test Tools Categories:
Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.

http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.


## OUTPUT:

![image](https://github.com/Poojithamanohar/InformationGathering/assets/119423592/b8b67460-9010-4ec5-8be4-891e6d433244)

Finding IP adress:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.

ping saveetha.ac.in

Output:

![image](https://github.com/Poojithamanohar/InformationGathering/assets/119423592/087196f7-32b0-4a4b-82db-87c48d5fc5c3)

Finding Hosting Company:
get further detail by using ip2location.com website.

Output:
![image](https://github.com/Poojithamanohar/InformationGathering/assets/119423592/b27db43e-064b-40d2-b15a-6dbf3447f10a)

History of the wbsite:

Output:

https://web.archive.org/

![image](https://github.com/Poojithamanohar/InformationGathering/assets/119423592/a292d6dd-58ca-4ac2-b475-202753c30914)

Web server Fingerprint:

Netcat:

nc 172.17.52.118 80

Output:

![image](https://github.com/Poojithamanohar/InformationGathering/assets/119423592/4279a1d9-1c1e-4239-aeea-ff6b0775c06c)

nmap:

nmap -p 21 -sV --script=banner ftp.vim.org

Output:

![image](https://github.com/Poojithamanohar/InformationGathering/assets/119423592/0882d47a-660b-4aca-b0d6-5cbf3b07f485)

Whatweb:

whatweb infosys.com

whatweb zoho.com

whatweb -v -a 3 172.17.52.201

Output:

![image](https://github.com/Poojithamanohar/InformationGathering/assets/119423592/58f2b592-125b-46ca-9996-f9eab475358f)

httprint:

httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more

Output:

![image](https://github.com/Poojithamanohar/InformationGathering/assets/119423592/38b30f7e-f38f-4cad-a579-335b7f2c1aff)


Tracing the Location:

TCP Traceroute:

sudo traceroute -T www.saveetha.ac.in

Output:

![image](https://github.com/Poojithamanohar/InformationGathering/assets/119423592/d78c5bba-207f-4253-8b26-6d03b06e944c)

UDP Traceroute:

sudo traceroute -U www.saveetha.ac.in

Output:

![image](https://github.com/Poojithamanohar/InformationGathering/assets/119423592/400d595d-34f4-4ef8-a1ed-100840278457)

ICMP Traceroute:

sudo traceroute  www.saveetha.ac.in

Output:

![image](https://github.com/Poojithamanohar/InformationGathering/assets/119423592/00dac1d0-ad76-4a65-b210-23415e517750)

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
