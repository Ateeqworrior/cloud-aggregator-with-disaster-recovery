# Cloud Aggregator with Disaster Recovery (CAWDR)
Author: Ateeq Ur Rahaman
Capstone Project @ PES University
Co-authors: Edde Vinith, Tejas B N, Nisank Arnav, Shilpa S
Timeline: Jan 2024 – Jan 2025

## Overview
Cloud Aggregator with Disaster Recovery (CAWDR) is a unified platform designed to streamline multi-cloud resource management and offer enterprise-grade disaster recovery across AWS and Azure. It ensures minimal downtime, zero data loss, and automated recovery for mission-critical workloads.

## ✨ Key Features
⚙️ Cross-Cloud Interoperability
Manage AWS & Azure resources from a single platform for enhanced visibility and control.

### 🔄 Real-Time Block-Level Replication
Ensure data durability through continuous and efficient synchronization.

### 🔁 Automated Failover & Failback
Instant and seamless transition during outages or planned maintenance.

### 📊 Monitoring & Smart Alerts
Stay ahead of failures with proactive system health checks and notifications.

### 🖥️ User-Friendly Web Dashboard
Intuitive interface to configure settings, monitor performance, and trigger operations.

# 🧠 Architecture

  The system leverages a dual-cloud architecture, featuring:

• Primary Environment: Hosted on AWS for normal operations.

• Secondary Environment: Mirrored setup on Azure for disaster recovery.

• Failover Controller: Automated traffic redirection during service disruptions.

• Monitoring Layer: Tracks system health and performance in real-time.

# 🛠️ Tech Stack


Backend	       -->     Python (Flask)

Frontend	    -->      HTML5, CSS3, JavaScript

Database      -->    	MySQL

Cloud Services   --> 	AWS (CloudEndure), Azure (ASR)

Deployment Tools  --> 	NGrock(Free Deployment)

Monitoring APIs	  -->  CloudWatch, Azure Monitor



# 💾 Requirements
🔧 Hardware
High-capacity SSD storage
Encrypted networking infrastructure


# 🧑‍💻 Software & Cloud
AWS CloudEndure or Azure Site Recovery
Secure VPN or Direct Connect / ExpressRoute
Ngrok for Free Deployment


# ⚙️ How to Use
Launch the App:
Visit http://localhost:5000 or deploy on your preferred cloud instance.

Configure Credentials:
Under the Settings tab, securely add AWS and Azure access keys.

Start Replication:
Initiate real-time sync between the two cloud platforms.

Run DR Tests:
Simulate failover/failback from the Dashboard.

Monitor Systems:
Access metrics, logs, and alerts for system health.

# 👥 Contributing
Contributions are always welcome to improve CAWDR!

bash
Copy code
# Step 1: Fork the repository
# Step 2: Create a new feature branch
git checkout -b feature/your-feature-name

# Step 3: Commit your changes
git commit -m "Add your feature"

# Step 4: Push and submit PR
git push origin feature/your-feature-name


# 🪪 License
Licensed under the MIT License.


# 🙋‍♂️ About the Author
Ateeq Ur Rahaman
Final Year CSE Student | Cloud & DevOps Enthusiast | Cybersecurity Explorer
📍 PES University | 🌐 https://www.linkedin.com/in/ateeq-ur-rahaman-999901312/
🛠️ Passionate about building reliable and scalable cloud-native solutions.





