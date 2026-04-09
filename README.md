# Highly Available Web Application using Auto Scaling, Load Balancer, RDS, CloudFront, and Monitoring

### Step 5: Create Auto Scaling Group
- Use Launch Template
- Set minimum, desired, and maximum capacity

### Step 6: Create Amazon RDS
- Launch MySQL database in private subnets
- Disable public access

### Step 7: Launch Bastion Host
- Create Bastion Host in public subnet
- Allow SSH only from your IP

### Step 8: Configure HTTPS
- Request SSL certificate using AWS Certificate Manager
- Attach certificate to ALB

### Step 9: Configure Route 53
- Create hosted zone
- Map domain to ALB or CloudFront

### Step 10: Configure CloudFront
- Create distribution
- Use ALB as origin

### Step 11: Configure CloudWatch and SNS
- Create CPU utilization alarm
- Configure SNS email notifications

---

## Screenshots

Add screenshots for:

- VPC
- Subnets
- EC2 Instances
- Application Load Balancer
- Auto Scaling Group
- Amazon RDS
- Bastion Host
- Route 53
- CloudFront
- CloudWatch Alarm
- SNS Email Alert

Example:

![ALB Screenshot](screenshots/alb.png)

---

## Resume Points

- Designed a highly available web application using EC2, Auto Scaling Group, and Application Load Balancer.
- Implemented Amazon RDS in private subnets for secure database access.
- Configured Bastion Host for secure SSH access to private infrastructure.
- Secured traffic using HTTPS and SSL certificates.
- Integrated Route 53 and CloudFront for custom domain and faster content delivery.
- Configured CloudWatch alarms and SNS notifications for infrastructure monitoring.

---
