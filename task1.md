* **cmd:- *sudo apt update \&\& sudo apt install nmap -y***
* 
**&nbsp;**  description: used to install nmap.



* **cmd:- *ifconfig***

   description: used to find the local ip range.



* **cmd:- *sudo nmap -sS -sV -O -T4 192.168.1.0/24***

&nbsp;  description: sudo:- for root privileges 

&nbsp;		nmap:- tool

&nbsp;		-sS:- TCP SYN (stealthy, fast)

&nbsp;		-sV:- version detection (service \& version)

&nbsp;		-O:- OS detection

&nbsp;		-T4:- faster timing (use carefully)

&nbsp;		192.168.1.0/24:- local ip range



 **Output:**		

&nbsp;	*Nmap scan report for 192.168.1.1*

	*Host is up (0.0053s latency).*

	*Not shown: 992 closed tcp ports (reset)*

	*PORT    STATE    SERVICE        VERSION*

	*21/tcp  open     ftp            GNU Inetutils FTPd 1.9.4*

	*22/tcp  open     ssh            Dropbear sshd 2019.78 (protocol 2.0)*

	*23/tcp  filtered telnet*

	*53/tcp  open     domain         dnsmasq 2.80*

	*80/tcp  open     tcpwrapped*

	*139/tcp filtered netbios-ssn*

	*443/tcp open     ssl/tcpwrapped*	

	*445/tcp filtered microsoft-ds*

	*MAC Address: 98:9D:B2:79:A4:83 (Goip Global Services Pvt.)*

	*Device type: general purpose*

	*Running: Linux 3.X|4.X*

	*OS CPE: cpe:/o:linux:linux\_kernel:3 cpe:/o:linux:linux\_kernel:4*

	*OS details: Linux 3.10 - 4.11*

	*Network Distance: 1 hop*

	*Service Info: Host: ApolloPro; OS: Linux; CPE: cpe:/o:linux:linux\_kernel*

	

	*Nmap scan report for 192.168.1.34*

	*Host is up (0.017s latency).*

	*Not shown: 999 closed tcp ports (reset)*

	*PORT     STATE    SERVICE VERSION*

	*5060/tcp filtered sip*

	*MAC Address: BE:8E:A6:C9:5E:B4 (Unknown)*

	*Too many fingerprints match this host to give specific OS details*

	*Network Distance: 1 hop*

	

	*Nmap scan report for 192.168.1.39*

	*Host is up (0.031s latency).*

	*Not shown: 999 closed tcp ports (reset)*

	*PORT     STATE    SERVICE VERSION*

	*5060/tcp filtered sip*

	*MAC Address: 8A:F6:A7:E9:CF:37 (Unknown)*

	*Too many fingerprints match this host to give specific OS details*

	*Network Distance: 1 hop*

	

	*Nmap scan report for 192.168.1.76*

	*Host is up (0.00059s latency).*

	*Not shown: 996 filtered tcp ports (no-response)*

	*PORT     STATE SERVICE       VERSION*

	*135/tcp  open  msrpc         Microsoft Windows RPC*

	*139/tcp  open  netbios-ssn   Microsoft Windows netbios-ssn*

	*445/tcp  open  microsoft-ds?*

	*3306/tcp open  mysql         MySQL (unauthorized)*

	*MAC Address: 50:5A:65:C7:F3:73 (AzureWave Technology)*

	*Warning: OSScan results may be unreliable because we could not find at least 1 open and 1 closed port*

	*Device type: general purpose|phone|specialized*

	*Running (JUST GUESSING): Microsoft Windows 11|10|2022|2008|Phone|7 (96%)*

	*OS CPE: cpe:/o:microsoft:windows\_11 cpe:/o:microsoft:windows\_10 cpe:/o:microsoft:windows\_server\_2022 cpe:/o:microsoft:windows\_server\_2008::sp1 cpe:/o:microsoft:windows 	cpe:/o:microsoft:windows\_7*

	*Aggressive OS guesses: Microsoft Windows 11 21H2 (96%), Microsoft Windows 10 (91%), Microsoft Windows 10 1607 (91%), Microsoft Windows Server 2022 (90%), Microsoft Windows Server 	2008 SP1 (88%), Microsoft Windows Phone 7.5 or 8.0 (88%), Microsoft Windows Embedded Standard 7 (87%), Microsoft Windows 10 1511 - 1607 (86%)*

	*No exact OS matches for host (test conditions non-ideal).*

	*Network Distance: 1 hop*

	*Service Info: OS: Windows; CPE: cpe:/o:microsoft:windows*

	

	*Nmap scan report for 192.168.1.77*

	*Host is up (0.000038s latency).*

	*All 1000 scanned ports on 192.168.1.77 are in ignored states.*

	*Not shown: 1000 closed tcp ports (reset)*

	*Too many fingerprints match this host to give specific OS details*

	*Network Distance: 0 hops*

	

	*OS and Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .*

	*# Nmap done at Mon Sep 22 16:31:35 2025 -- 256 IP addresses (5 hosts up) scanned in 22.52 seconds*

