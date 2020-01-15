# Jenkins on aws
### Steps
##### 1. Create security group
Go to EC2 > NETWORK & SECURITY > Security Groups [Create Security Group]
Name the security group
[Name : jenkins-admin]
Settings for**"Inbound"**
- ssh (my ip)
- http (Anywhere)
- https (Anywhere)