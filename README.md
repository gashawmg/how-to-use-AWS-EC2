# how-to-use-AWS-EC2
Step by step procedure for deploying ML model in Amazon's AWS Elastic Computing (CE2)
Steps in deploying ML model using AWS EC2 instance
Part I
1.	Create AWS Free Tier account 
 
AWS Free Tier
2.	Go to the search bar, type EC2, and click on EC2
 

3.	Click on Launch instance
 
4.	Give name for your app
 

5.	Select the operating system
 
 
 

6.	Create key-pair and save .pem file in your computer.
 
 
7.	Use the remaining default values and launch the instance.
 
Part II
1.	Install three software packages (Putty, PuttyGen and WinSCP)
https://www.putty.org/
 
https://www.puttygen.com/download-putty 
https://winscp.net/eng/download.php
 
2.	 Generate the private key using PuTTYgen
 
3.	Use WinSCP to move your files by drag and drop to your EC2 instance storage
-	First connect to EC2 instance using its public IP address or Public IPv4 DNS and using the private key generated using PuTTYgen.
 
-	Drag and drop files needed to run your app from your local folder to EC2 instance storage.
 

I deployed a ML web app for HOMO-LUMO gap prediction using AWS CE2 instance
   
 







