# Networking-Unit-Project

Create a Virtual Private Cloud (VPC) and Virtual Switch (VSwitch) in Alibaba Cloud is a fundamental step for building your network infrastructure. In this lab, you will go through the process of creating a VPC and VSwitch in Alibaba Cloud using the Alibaba Cloud Management Console.


## Tasks:

**Task 1: Create a VPC**

Create a VPC name it (project-xyz) in Riyadh Region, make sure the IPv4 CIDR Block you choose can have only (256) subnet and each subnet can have (256) IP

**Task 2: Create a VSwitch**

A Virtual Switch (VSwitch) is a subnet within your VPC. You can create multiple VSwitches within a VPC to segment your network.

1. Create a subnet in Zone A and name it (project-xyz-a)
2. Create a subnet in Zone B and name it (project-xyz-b)

**Task 3: Verify Your ECS VMs connection**

After creating the 2 ECS Instances try to ping the other instance and ``` ping alibabacloud.sa ``` 

1. Create an ECS in VSwitch project-xyz-a and name it (app-xyz-a1)
2. Create an ECS in VSwitch project-xyz-b and name it (app-xyz-b1)

**Task 4: Create an internet Nat Gateway to allow private instances to access the internet**

After creating and configure the INGW try to this command ``` ping alibabacloud.sa ``` 

1. Create an ECS in VSwitch project-xyz-a and name it (app-xyz-a1)
2. Create an ECS in VSwitch project-xyz-b and name it (app-xyz-b1)

## Submission:

- After finishing the tasks take screen shot of newly create VPC basic information and VSwitchs details and the ping command responses.
- Then upload the pictures to the forked repo and then create a pull request.
