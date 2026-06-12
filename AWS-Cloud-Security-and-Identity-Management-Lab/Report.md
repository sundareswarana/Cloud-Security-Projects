#Create AWS Account (Free $100 Credit for 3 months)

Go to:

Amazon Web Services official site

https://aws.amazon.com/

Steps:

	Click “Create an AWS Account”
	
	Enter:
	
Email 

Password 

Account name 

	Add:
   
Free Tier available

Verify phone (OTP) 

Choose: 

Basic Support Plan

In AWS (while configuring):

You will usually see it as:

•	(UTC+05:30) Asia/Kolkata


After login:

Go to Billing Dashboard 

 Enable: 
 
•	Billing alerts 

•	Free tier alerts

This prevents unexpected charges


#Launch EC2 Instance

Go to:

AWS Console → Search → EC2

	Click “Launch Instance” 
  
	Configure: 
  
	Name: MyFirstServer (Any Name)
  
  AMI: Ubuntu Linux
  
  Instance type: t3.micro (Free Tier) 
  
Key Pair: 

Click Create Key Pair 

Name: my-key 

Download .pem file  (very important) 

  Network: 
  
  Allow: 

SSH (port 22) 

HTTP (port 80) 

Click Launch Instance
You now have a cloud server running.

