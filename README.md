# Load-Balancer-ALB-High-Availability-Project

🚀 AWS Application Load Balancer (ALB) – High Availability Project

Successfully designed and implemented a highly available web application architecture on AWS using an Application Load Balancer across multiple Availability Zones.

🔹 Architecture Highlights:
✅ Custom VPC with public and private subnets across 2 Availability Zones (ap-south-1a & ap-south-1b)
✅ Application Load Balancer deployed in public subnets
✅ EC2 web servers deployed in private subnets
✅ Security Groups configured following least-privilege principles
✅ Traffic distributed automatically by the ALB
✅ High Availability and Fault Tolerance achieved

🧪 Failover Testing:
To validate the setup, I stopped one EC2 instance behind the Load Balancer. The ALB automatically routed all incoming traffic to the healthy EC2 instance, ensuring uninterrupted access to the application.

💡 Key Learning:
Even if one server becomes unavailable due to maintenance or failure, users can continue accessing the application without downtime. This is one of the core benefits of using Load Balancers and Multi-AZ deployments in AWS.

AWS Services Used:
🔹 VPC
🔹 Public & Private Subnets
🔹 EC2
🔹 Application Load Balancer (ALB)
🔹 Security Groups
🔹 Route Tables

#AWS #CloudComputing #DevOps #AmazonWebServices #LoadBalancer #EC2 #VPC #CloudArchitecture #HighAvailability #FaultTolerance #Networking #CloudProjects #AWSProjects
