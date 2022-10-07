## Problem statement 1#
Write a Terraform project that creates a VPC with a CIDR range set from a variable in a region set by another variable. Then apply the project and set the CIDR variable using a file and the region using an environment variable.

## Problem statement 2#
There will be two parts of this project. Let’s first look into their problem statements.

Part one#
Make a Terraform project that creates a VPC and sets the tag Name to your name.

Part two#
Create another Terraform project that looks up that VPC using a data block filtering on the Nametag and outputs the CIDR range of the VPC to the terminal.

Output#
Subfolder part1 creates the VPC with the Name tag set to Kevin. Subfolder part2 shows how to look this up by data block and output it.

## Problem statement 3#
Write a Terraform module that creates a VPC and 2 subnets. The module takes inputs for the CIDR ranges for the VPC and subnets and should return the created VPC and each subnet as an output. Create a Terraform project that uses the module and print the output of the module to the console.

Inputs#
As defined in the problem statement, the module takes inputs for the CIDR ranges and for the VPC and subnets.

Output#
The module should return the created VPC and each subnet as an output.

