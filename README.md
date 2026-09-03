# aws-cloud-infrastructure-project
AWS cloud infrastructure implementation, architecture diagrams, and deployment documentation.
# Scalable Student Registry System (AWS Cloud Infrastructure)

A cloud-native, end-to-end student registration platform deployed on Amazon Web Services (AWS) featuring high availability, auto-scaling, load balancing, and secure infrastructure design.

---

## Team Members
*Ali Alnaggar 
* Malak Gharib
* Adham amr
* Youssef rawy

---

## Core Architecture & Infrastructure

* **Compute & High Availability:** Public subnets hosting Amazon EC2 instances managed by an Application Load Balancer (ALB) and Auto Scaling group to handle variable user traffic.
* **Database Layer:** Amazon RDS running MariaDB isolated inside private subnets with no direct public internet access.
* **Storage:** Amazon S3 for hosting static media assets and web files.
* **Networking & Security:** Custom Amazon VPC with subnet isolation, restricted Security Groups per tier, and minimal-privilege IAM roles.
* **Monitoring & Testing:** Amazon CloudWatch for real-time alarms and metrics, paired with Apache JMeter for load and performance simulation.

---

## Tech Stack & Tools

* **Frontend & Backend:** PHP, HTML, CSS (Dynamic Forms & UI)
* **Cloud Provider:** Amazon Web Services (AWS)
* **AWS Services:** EC2, RDS (MariaDB), S3, ALB, Auto Scaling, VPC, IAM, CloudWatch
* **Testing Tool:** Apache JMeter

---

## Project Features

* Fully functional dynamic registration forms built with PHP.
* Auto-scaling infrastructure that dynamically handles high concurrent user loads.
* Tiered VPC security isolating database traffic from the public internet.
* Real-time system performance monitoring and alarm triggers under simulated load.
