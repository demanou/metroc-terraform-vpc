# metroc-terraform-vpc

#Deploy VPC with CIDR 10.80.0.0/16
#Enable DNS resolution, hostnames
#Deploy IGW and attached to VPC
#Deploy a Route Table
#Deploy a Route with 0.0.0.0/0 Destination IGW
#Deploy 4 Subnets, 2 in each AZ
#Add 1 subnet from each AZ to Public RT.
#Deploy 1 SG for LoadBalancer port 80, 443 source 0.0.0.0/0
#Deploy 1 SG for EC2 port 22, 80, 443 source 0.0.0.0/0
#All the resources-id to store in SSM Parameter
