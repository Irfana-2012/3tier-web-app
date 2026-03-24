# AWS 3-Tier Web Application

This project demonstrates a scalable 3-tier architecture on AWS.

Failover design 

- VPC with public and private subnets with Multi-AZ design for High availabity 
- frontend with static S3 bucket and Cloudfront for low latency
- application tier with EC2 instances in Auto Scaling Group for traffic handling
- database tier with managed relational database RDS
- Application Load Balancer to distribute incoming traffic across multiple EC2 instances
  

