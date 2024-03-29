## Project part one: 
![Project_1](./project_part_one.png)
- Custom Multi-Tier VPC deployed in AWS using Terraform.  
- Deployed in multiple AZ's (availability zones) to allow for fault tolerance support.  
- 12 subnets (IPv4 and IPv6) configured for the database, application, web, and reserved ranges.  

## Project part two: 
![Project_2](./project_part_two.png)
- Public subnets assigned towards the web environment for incoming/outgoing traffic.  
- Private subnets assigned towards the reserved, database, and application environments for outgoing traffic only.  
- Added an internet gateway and a public route table for the web environment.  
- Cleaned up code & added variables/tags.  
- Added private internet connection capabilities via the NAT gateway along with the required elastic IP's.  
- Added private route table connections to allow for the database, reserved, and application environments to allow only outbound traffic.
- Testing completed internally within the private environments to confirm that outbound traffic is functioning via the NAT gateway.
