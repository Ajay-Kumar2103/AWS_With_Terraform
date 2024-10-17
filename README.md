**AWS With Terraform:**

This project automates the creation of AWS infrastructure using Terraform. The infrastructure includes the following components:

**VPC (Virtual Private Cloud):** A custom VPC to host the resources.
**Public Subnets:** Two public subnets in different availability zones.
**Internet Gateway:** Allows instances in the VPC to access the internet.
**Route Table:** Routes traffic from the subnets to the internet gateway.
**Security Groups:** Firewall rules to control inbound and outbound traffic.
**EC2 Instances:** Two t2.micro instances deployed in different subnets.
**Application Load Balancer (ALB)**: Distributes traffic across the EC2 instances.
**S3 Bucket:** Used for storage with specific access controls.


<img width="528" alt="image" src="https://github.com/user-attachments/assets/69bd7609-a541-49f3-8742-610f70c7f003">


