

# Virtual-private-cloud
Build and configured using console and cli an AWS VPC

# Build a Virtual Private Cloud

---

## Introducing Today's Project!

In this project, I will demonstrate creating a virtual private cloud I'm doing this project to learn on subnetting

## Virtual Private Clouds (VPCs)

### What I did in this step

In this step, I will access the vpc console because I will be creating a vpc

### How VPCs work

VPCs are secure, isolated private networks that are being hosted within a public cloud provider.

### Why there is a default VPC in AWS accounts

There was already a default VPC in my account ever since my AWS account was created. This is because without it I woud have to learn how to setup vpc before accessing different services of aws.

![Virtual Private Clouds (VPCs)](https://nextwork.ai/hl-2/uploads/7f907ac7-2473-5c15-a8be-edb36581cdba_2facf927)

### Defining IPv4 CIDR blocks

To set up my VPC, I had to define an IPv4 CIDR block, which is 10.0.0.0/26.

## Subnets

### What I did in this step

In this step, I will create a subnet so I can allocate which resources will live and operate

### Creating and configuring subnets

Subnets are division of a large network. There are already subnets existing in my account, one for every availability zone

### Public vs private subnets

The difference between public and private subnets are that the latter doesn't have direct access to the internet. It's used for internal resources that doesn't need to be publicly available. For a subnet to be considered public, it has to to be connected to the internet and the resources can communicate with external networks.

![Subnets](https://nextwork.ai/hl-2/uploads/7f907ac7-2473-5c15-a8be-edb36581cdba_157c4219)

### Auto-assigning public IPv4 addresses

Once I created my subnet, I enabled auto assign IPV4 address. This setting makes sure an ipv4 address is assigned to my subnet

## Internet gateways

### What I did in this step

In this step, I will assign an internet gateway so it can communicate with external networks.

### Setting up internet gateways

Internet gateways are like bridges. They connect my vpc to the internet and other external connections.

Attaching an internet gateway to a VPC means im connected to the internet. If I missed this step I won't be able to communicate externally to other networks.

![Internet gateways](https://nextwork.ai/hl-2/uploads/7f907ac7-2473-5c15-a8be-edb36581cdba_4ae90410)

## Using the AWS CLI

### What I'm doing in this extension

In this project extension, I will the amazon cli to launch my vpc's resources. I will be hecking if it is much faster, and more efficient way to do this project.

### Exploring CloudShell and CLI

VPC resources could also be created with CloudShell, which is a command line interface. CLI's are terminal in which you code and directly command the console what you want to happen or to be done

### Debugging my setup

To set up a VPC or a subnet, you can use the command aws ec2 create-subnet --vpc-id VPC-ID. Make sure to avoid errors by including the correct and lacking parameters.

![Using the AWS CLI](https://nextwork.ai/hl-2/uploads/7f907ac7-2473-5c15-a8be-edb36581cdba_9b2465411)

### Comparing CloudShell vs AWS Console

Compared to using the AWS Console, an advantage of using commands is it is much faster and efficient if you know how to code. An advantage of using the Console is. it is beginner friendly. Overall, I preferred using the CLI


In this project, I will demonstrate creating a virtual private cloud I'm doing this project to learn on subnetting

## Virtual Private Clouds (VPCs)

### What I did in this step

In this step, I will access the vpc console because I will be creating a vpc

### How VPCs work

VPCs are secure, isolated private networks that are being hosted within a public cloud provider.

### Why there is a default VPC in AWS accounts

There was already a default VPC in my account ever since my AWS account was created. This is because without it I woud have to learn how to setup vpc before accessing different services of aws.

### Defining IPv4 CIDR blocks

To set up my VPC, I had to define an IPv4 CIDR block, which is 10.0.0.0/26.

## Subnets

### What I did in this step

In this step, I will create a subnet so I can allocate which resources will live and operate

### Creating and configuring subnets

Subnets are division of a large network. There are already subnets existing in my account, one for every availability zone

### Public vs private subnets

The difference between public and private subnets are that the latter doesn't have direct access to the internet. It's used for internal resources that doesn't need to be publicly available. For a subnet to be considered public, it has to to be connected to the internet and the resources can communicate with external networks.


### Auto-assigning public IPv4 addresses

Once I created my subnet, I enabled auto assign IPV4 address. This setting makes sure an ipv4 address is assigned to my subnet

## Internet gateways

### What I did in this step

In this step, I will assign an internet gateway so it can communicate with external networks.

### Setting up internet gateways

Internet gateways are like bridges. They connect my vpc to the internet and other external connections.

Attaching an internet gateway to a VPC means im connected to the internet. If I missed this step I won't be able to communicate externally to other networks.

## Using the AWS CLI

### What I'm doing in this extension

In this project extension, I will the amazon cli to launch my vpc's resources. I will be hecking if it is much faster, and more efficient way to do this project.

### Exploring CloudShell and CLI

VPC resources could also be created with CloudShell, which is a command line interface. CLI's are terminal in which you code and directly command the console what you want to happen or to be done

### Debugging my setup

To set up a VPC or a subnet, you can use the command aws ec2 create-subnet --vpc-id VPC-ID. Make sure to avoid errors by including the correct and lacking parameters.

### Comparing CloudShell vs AWS Console

Compared to using the AWS Console, an advantage of using commands is it is much faster and efficient if you know how to code. An advantage of using the Console is. it is beginner friendly. Overall, I preferred using the CLI
