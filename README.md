# Deploy Reverse-Proxy on AWS in Customize VPC using Ansible
New Task...!!

TASK-DESCRIPTION:

- Create your own customize VPC on AWS
- Create a Subnet with public-ip assign (public subnet) inside this VPC
- Create an Internet Gateway
- Create a Route table and add a route for internet gateway(igw)
- Associate this Route table with the public subnet
- Configure REVERSE PROXY by Provisioning of 3 EC2 instances
- Launch two EC2 instances as Backend webservers and one ec2 instance as LoadBalancer
- Retrieve IP-addresses dynamically or by using dynamic-inventory concept or by using plugin
- Configure loadbalancer by haproxy 
- Configure backend webserver instances by apache webserver
- Do the whole task by Ansible on localhost.
