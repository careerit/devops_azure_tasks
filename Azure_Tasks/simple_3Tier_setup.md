# Create Infra for Simple three tier Application

1. Create a Virtual Network
2. Create 3 subnets - Bastion, Frontend, Backend
3. Create NSG one each for each subnet
4. Create one VM in Bastion Subnet, 2 webservers in Frontend subnet, 1 DB server in backend.
5. DB server should have no additional NSG rules apart from default rules
6. Only Bastion should have public IP and SSH port should be open
7. Install apache2 on both the servers.
7. Add a Load server and add the 2 webservers to the laod balancer
8. Access the website with the public IP of your load balancer
