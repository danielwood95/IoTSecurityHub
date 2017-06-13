# IoTSecurityHub

IoT Security Hub is a user-friendly interface for consumers to visualize Internet of Things (IoT) vulnerabilities in their home. The hub runs on a Raspberry Pi and is configured as a Wi-Fi access point, analyzing connected devices for default passwords, conducting deep packet inspection to find leaking sensitive personal information, and detecting anomalous device behavior in the case of a bot net attack.   
See IoTNetworkMonitor.pdf for the final report submitted to the Federal Trade Commission's IoT Home Inspector Challenge.

### Installation

pip install paramiko

brew install zmap
open /usr/local/etc/zmap/blacklist.conf
Comment out lines for:
	10.0.0.0/8          # RFC1918: Private-Use   
	172.16.0.0/12       # RFC1918: Private-Use  
	192.168.0.0/16      # RFC1918: Private-Use  

### How to run?
####To run, past the following in bash:

export FLASK_APP=server.py
flask run

