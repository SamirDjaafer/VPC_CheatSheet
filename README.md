# VPC Cheat Sheet

## VPC?

- VPC stands for: Virtual Private Cloud.
- It is your OWN Isolated Network in the Cloud! 
- You define an IP Range for the Private IPs
- You have to decide which region you want your VPC to be in.

## Subnet?

- Subnets are Sub-Networks inside the VPC.
- Subnets can only be in one Availability Zone.
- Each Subnet takes a sub-set of the VPC IP range.

## Internet Gateway (IGW)?

- Mangaes the connection between your VPC and the Internet

## Security Group?

- Security groups can be defined in your VPC.
- Security groups are applied on a per-instance level.
- Security groups control which traffic can come in to the instances and which traffic can leave the instances.

- Acts as a Firewall!

## Network Access Control List (NACL)?

- NACL's are applied on a Subnet level!
- NACL's control which traffic can enter and leave this Subnet

## Route Table

- Controls Routing of Outgoing requests
- Setup on the Subnet

## NAT (Network Address Translation) Gateway

- Translates Private IPs to Public IPs
- Allows Internet Access for Private Instances, lets them reach out to the internet with this backdoor access.

## CIDR Block?

- A notation for IP address ranges!
- /32 would be for exact IP address
- /8 would mean the last 3 numbers could range from 0.0.0 to 255.255.255
- /16 would mean the last 2 numbers could range from 0.0 to 255.255 but the first 2 numbers are FIXED

You get where this is going? 










