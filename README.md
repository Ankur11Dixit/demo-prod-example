AWS public-private Subnet example
This repo shows the demonstration of AWS public-private subnet architecture.
RESOURCES USED:
1) AWS VPC.
2) AWS EC2 instances with autoscaling group.
3) AWS Load balancers
4) Deployed an application on one of the EC2 instances.

STEPS:
1) Created a VPC with 2 private and 2 public subnets in 2 availability zones with 1 NAT Gateway per AZ.
2) Created 3 EC2 instances, 2 in private subnet and 1 in public subnet for Bastion-Host.
3) Logged in to the private server using Bastion-Host/Jump Server.
4) Installed HTML page.
5) Created Application Load Balancer in public subnet for the internet access.
6) Tested the DNS.
