# EC2

This stack creates an EC2 virtual machine in its own VPC.
Machine has enabled public access for SSH.

Image is Amazon Linux 2.  
Default instance type is `t2.micro`. Change by providing `--type` parameter. 

EC2 has attached empty IAM Role that you can modify to give needed permissions.

Machine is started right after the deployment.
To connect, find it in AWS Console EC2 and select "Connect".
Use default "EC2 Instance Connect" to open SSH session in the browser.

**Remember to stop the instance when you are no longer using it.**
