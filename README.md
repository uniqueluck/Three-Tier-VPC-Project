🏗️ 3-Tier Architecture using AWS VPC
📌 Project Description
This project demonstrates the implementation of a 3-tier architecture on AWS using Virtual Private Cloud (VPC). The architecture consists of a Presentation Tier (Web Layer), Application Tier, and Data Tier, each in separate subnets with proper routing and security configurations.

🧱 Architecture Overview
VPC with public and private subnets

Internet Gateway attached to the VPC

NAT Gateway in a public subnet for internet access from private subnets

Web Tier (Public Subnet): EC2 instances running a web server (e.g., Apache/Nginx)

App Tier (Private Subnet): EC2 instances running the application logic

DB Tier (Private Subnet): Database on EC2

Security Groups for controlled access between tiers

📊 AWS Services Used
VPC, Subnets (public & private)

Internet Gateway

NAT Gateway

Route Tables

EC2 Instances

Security Groups

🛡️ Security Configurations
Web tier is open to HTTP/HTTPS traffic


App tier only allows traffic from Web tier security group

DB tier only allows traffic from App tier

No direct internet access to App and DB tiers (uses NAT for outbound)

![Architecture Diagram](https://github.com/uniqueluck/Three-Tier-VPC-Project/blob/main/instance.png)
![Architecture Diagram](https://github.com/uniqueluck/Three-Tier-VPC-Project/blob/main/vpc.png)
![Architecture Diagram](https://github.com/uniqueluck/Three-Tier-VPC-Project/blob/main/subnets.png)
![Architecture Diagram](https://github.com/uniqueluck/Three-Tier-VPC-Project/blob/main/igw.png)
![Architecture Diagram](https://github.com/uniqueluck/Three-Tier-VPC-Project/blob/main/rout_table.png)
![Architecture Diagram](https://github.com/uniqueluck/Three-Tier-VPC-Project/blob/main/done.png)

## 🙌 Thank You!

Thanks for checking out this project! If you have any suggestions or feedback, feel free to connect with me.

**Author**: Bhagyashri Bobade  
📧 Email:bhagyashribobade979@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/bhagyashribobade/  
