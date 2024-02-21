# AWS CLI Installation and EC2 Instance Creation

This script automates the installation of AWS CLI version 2 on a Linux machine and the creation of an EC2 instance using AWS CLI commands.

## Prerequisites
- Linux operating system
- `curl` and `unzip` utilities installed
- AWS IAM user with appropriate permissions to create EC2 instances

## Installation Steps
1. **Install AWS CLI v2:**
   If AWS CLI v2 is not installed, the script will automatically download and install it.

2. **Create EC2 Instance:**
   After installing AWS CLI, the script will create an EC2 instance with the specified parameters:
   - AMI ID: ami-0e670eb768a5fc3d4
   - Instance Type: t2.micro
   - Key Name: sumit_cloud_pem
   - Subnet ID: subnet-02c70686ab298583d
   - Security Group IDs: sg-0cd2b900a8a5aa848 (Add your security group IDs separated by space if required)
   - Instance Name: Sumit_CLI_Instance

## Usage
1. Clone the repository containing the script.
2. Make the script executable: `chmod +x create_ec2_instance.sh`
3. Run the script: `./create_ec2_instance.sh`

The script will guide you through the installation of AWS CLI and the creation of an EC2 instance. Ensure that you have appropriate permissions and network connectivity to execute the script successfully.

For any issues or questions, please contact 
Linkedln :- https://www.linkedin.com/in/sumitgupta190a/
