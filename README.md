# AWS Migration Project

This project demonstrates the migration of on-premises infrastructure to AWS using AWS Application Migration Service (MGN), along with a step-by-step process to ensure a smooth and minimal-downtime transition.

## 🛠️ Technologies Used

- AWS EC2, S3, RDS, VPC, IAM, CloudFormation
- AWS MGN (Application Migration Service)
- AWS DMS (Database Migration Service)
- AWS CloudWatch, CloudTrail
- Linux (Shell Scripting, File Permissions)
- Git, Bash

---

## 🚀 Migration Steps

1. **Install the AWS Replication Agent** on the source server.
2. **Wait until the initial sync** is finished (approx. 1 hour after instance discovery in AWS).
3. **Launch test instances** to validate the setup.
4. **Perform acceptance tests** on the test instance. After successful validation, delete the test instance.
5. **Wait for the cutover window**.
6. **Confirm there is no lag** between the source and replication.
7. **Stop all operational services** on the source server.
8. **Launch the cutover instance**.
9. **Verify and finalize** the cutover after confirming the instance is running as expected.
10. **Archive the source server** for backup or compliance.

---

## ✅ Achievements

- Reduced infrastructure costs using pay-as-you-go AWS services.
- Enhanced application performance with autoscaling and cloud-native optimizations.
- Improved availability and disaster recovery readiness.

---

## 📂 Future Improvements

- Add CI/CD pipeline to deploy migrated apps.
- Implement CloudWatch alarms for better monitoring.
- Automate cutover process using AWS Lambda or Step Functions.

---

### 📸 Screenshots & Diagrams

**Benefits of Cloud Migration**  
![Benefits](screenshots/Screenshot%202025-04-24%20204824.png)

**6 Rs of Migration Strategy**  
![6 Rs](screenshots/Screenshot%202025-04-24%20205145.png)

**AWS MGN Tool - Process Flow**  
![MGN Flow](screenshots/Screenshot%202025-04-24%20205420.png)

**Virtualization Setup - Linux & Windows VMs**  
![VM Setup](screenshots/Screenshot%202025-04-24%20205950.png)

**SSH & Firewall Config for Migration**  
![SSH Config](screenshots/Screenshot%202025-04-24%20210203.png)

**Cloud-Init & Networking Setup**  
![Cloud Init](screenshots/Screenshot%202025-04-24%20210329.png)

**Systemd Setup for Apache Post-Migration**  
![Apache Boot](screenshots/Screenshot%202025-04-24%20210433.png)

**Final Post-Migration Steps**  
![Post Steps](screenshots/Screenshot%202025-04-24%20210504.png)

---


---

## 👤 Author

**Karunakar Jadi**  
[GitHub](https://github.com/Karunakarjadi1609) | [LinkedIn](https://www.linkedin.com/in/karunakarjadi123)  
