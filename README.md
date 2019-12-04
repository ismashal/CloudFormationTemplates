# VPC creation using AWS Cloud Formation 

 1. The following Cloud Formation Template will create the follwing resource in your AWS account.

		 - VPC with CIDR block ( 172.X.0.0/16 )
		 - 2 Private subnets ( 172.X.4.0/24 and 172.X.5.0/24 )
		 - 2 Public subnets ( 172.X.8.0/24 and 172.X.9.0/24 )
		 - Private route table
		 - Public route table
		 - Attach Route table to subnets
		 - Internet Gateway
		 - Attach internet gateway to VPC
		 - Internet Gateway to public route table
		 - NAT Gateway Creation 
		 - Elastic IP Address for NAT gateway
		 - Attach NAT gatway to private route table

- **Note : You need to enter the paramameter while creating the cloud formation stack ( Number [1-255] of environment. Note this will be used to define the second octect of your VPC CIDR. )**