# Lab 3 – Introduction to Amazon Elastic Compute Cloud (EC2)

## Author

* **Name**: SANTHABABU  G
* **Register Number**: 212224040292
* **Date of Submission**: 27-02-2026

---

## Objective

The objective of this experiment is to understand the fundamentals of Amazon Elastic Compute Cloud (EC2). This lab focuses on launching and managing a virtual server, understanding instance types and AMIs, connecting to an EC2 instance, monitoring its status, and performing basic instance operations such as start, stop, and terminate.

---

## Prerequisites

* Basic understanding of cloud computing concepts
* AWS account or AWS Academy Lab access
* Web browser with internet connectivity
* Basic knowledge of Linux commands (optional)

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Key Pair
* Security Group
* SSH Client (PuTTY / Terminal)

---

## Tasks Performed

### Task 1: Explore Amazon EC2 Dashboard

Explore the EC2 service dashboard in the AWS Management Console. Observe the different sections such as Instances, AMIs, Instance Types, Key Pairs, Security Groups, and Elastic IPs.

---

### Task 2: Launch an EC2 Instance

Launch a new EC2 instance using Amazon Linux 2 AMI. Select an appropriate instance type (t2.micro) under the free tier. Configure basic settings such as instance name, key pair, and security group.

---

### Task 3: Configure Security Group

Configure a security group to allow inbound access:

* SSH (Port 22) from your IP address
* HTTP (Port 80) from anywhere (0.0.0.0/0)

This security group acts as a firewall for the instance.

---

### Task 4: Connect to EC2 Instance

Connect to the running EC2 instance using SSH. Use the downloaded key pair and connect via terminal or PuTTY.

For Amazon Linux:

```
ssh -i "keyname.pem" ec2-user@<Public-IP>
```

---

### Task 5: Perform Basic Instance Operations

Perform the following operations from the EC2 console:

* Stop the instance
* Start the instance
* Reboot the instance

Observe the state changes of the instance.

---

### Task 6: Monitor EC2 Instance

Monitor the EC2 instance using the Monitoring tab. Observe metrics such as CPU utilization, network in/out, and instance status checks.

---

### Task 7: Terminate EC2 Instance

Terminate the EC2 instance after completing the experiment to avoid unnecessary AWS charges.

---

## Workflow (Student Explanation)

1.Logged in to the AWS Management Console using my AWS account.

2.Opened Amazon EC2 from the Services menu.

3.Explored the EC2 Dashboard sections such as Instances, AMIs, Instance Types, Key Pairs, Security Groups, and Elastic IPs.

4.Clicked on Launch Instance to create a new virtual server.

5.Selected Amazon Linux 2 as the AMI.

6.Chose the instance type t2.micro under the free tier.

7.Created a new key pair and downloaded the .pem file.

8.Configured the security group to allow:

9.SSH (Port 22) from my IP address

10.HTTP (Port 80) from anywhere (0.0.0.0/0)

11.Launched the EC2 instance and waited until its status changed to Running.

12.Copied the public IP address of the instance.

13.Connected to the instance using SSH with the key pair file.

14.Verified successful login to the instance terminal.

15.Performed instance operations such as Stop, Start, and Reboot from the EC2 console.

16.Observed the instance state changes during each operation.

17.Opened the Monitoring tab and checked metrics like CPU Utilization and Network activity.

18.Finally, terminated the EC2 instance to avoid unnecessary AWS charges.

---

## Output Screenshots (Attach 3)

### Screenshot 1: EC2 Dashboard / Instance List
<img width="1919" height="1019" alt="Screenshot 2026-02-27 172330" src="https://github.com/user-attachments/assets/76df68d2-814c-4c55-b1ba-2c0bd7f0d7c0" />


---

### Screenshot 2: SSH Connection to Instance

<img width="1919" height="996" alt="Screenshot 2026-02-27 173006" src="https://github.com/user-attachments/assets/37d7c2f2-6230-4979-8216-5d34d5a30cf1" />


---

### Screenshot 3: Instance Monitoring / Status

<img width="1919" height="1039" alt="Screenshot 2026-02-27 173944" src="https://github.com/user-attachments/assets/76b0cce2-dde3-49ce-882d-7dad83d7f644" />


---

## Result 

This experiment provided hands-on experience with Amazon EC2 by demonstrating how to launch, connect, manage, and monitor a virtual server in AWS. It helped in understanding the concept of Infrastructure as a Service (IaaS) and how compute resources can be provisioned and controlled on demand in the cloud.
