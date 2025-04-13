# VPC Cheatsheet
## What is a VPC?
**V**irtual **P**rivate **C**loud. A logically isolated section of AWS you can launch resources into. 

**Hint:** Think of it like a private network, but in the AWS cloud.

## Where is a VPC?
**Region-wide** resource.

### Availability Zone (AZ)
One or more data centers, each with redundant power, networking, and connectivity, and housed in separate facilities. 

Multiple AZs per region.

### Default VPC
A default VPC is created in a region, with a subnet in each VPC.

### How many VPCs per region?
**5**

## What is in a VPC?
### Subnets 
A subnet is a **range of IP addresses** in your VPC. 

You launch AWS resources, such as Amazon EC2 instances, into your subnets. 

You can connect a subnet to the internet, other VPCs, and your own data centers, and route traffic to and from your subnets using route tables.