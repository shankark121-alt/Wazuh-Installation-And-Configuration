# **PROJECT OVERVIEW**

This project demonstrates the installation and configuration of Wazuh, an open-source security monitoring platform used for threat detection, security monitoring, 
vulnerability detection, log analysis, and incident response. Wazuh provides a centralized security monitoring solution that helps administrators monitor endpoints, 
detect suspicious activities, analyze security events, and identify potential threats in an IT infrastructure.The objective of this project is to understand how Wazuh 
works as a SIEM and XDR platform and how it can be used to monitor Windows and Linux systems.

# **PROJECT OBJECTIVES**

Understand Wazuh architecture and its components.

Install and configure the Wazuh server.

Configure Wazuh agents on endpoint machines.

Connect Windows and Linux systems to the Wazuh server.

Monitor endpoint security events and system activities.

Detect suspicious activities and security threats.

Analyze logs through the Wazuh dashboard.

Understand centralized security monitoring.

# **TOOLS AND TECHNOLOGIES**

### TOOLS AND TECHNOLOGIES

| Tool / Technology   | Purpose                                              |
| ------------------- | ---------------------------------------------------- |
| Wazuh Manager       | Centralized security monitoring and threat detection |
| Wazuh Indexer       | Stores and indexes security data                     |
| Wazuh Dashboard     | Visualizes security events and alerts                |
| Wazuh Agent         | Collects endpoint security data                      |
| Kali Linux / Ubuntu | Linux lab environment                                |
| Windows Server 2022 | Windows endpoint monitoring                          |
| VMware Workstation  | Virtual lab environment                              |

# **WAZUH ARCHITECTURE**

Wazuh consists of three main server-side components:

Wazuh Manager: Analyzes collected security data, detects threats, and generates alerts.

Wazuh Indexer: Stores and indexes security events for searching and analysis.

Wazuh Dashboard: Provides a graphical interface for monitoring and investigating security events.

# **INSTALLATION PROCEDURE**

# Step 1: Prepare the Linux System

Install and update the supported Linux operating system.

Verify internet connectivity.

Check system resources and available disk space.

Configure the network and hostname.

# Step 2: Install Wazuh Server

Download the official Wazuh installation assistant.

Run the installation process using the official instructions.

Install the Wazuh Manager, Indexer, and Dashboard.

Verify that all required services are running.

<img width="1282" height="772" alt="image" src="https://github.com/user-attachments/assets/5c6e85a2-b619-48af-8dc8-688e69a1dca2" />

# Step 3: Access Wazuh Dashboard

Open the Wazuh Dashboard in a web browser:

https://<WAZUH_SERVER_IP>

Log in using the credentials generated during installation.

<img width="1245" height="587" alt="image" src="https://github.com/user-attachments/assets/bd6b9a1f-99e1-4694-866d-47809c8f3145" />

# Step 4: Install Wazuh Agent

Install the appropriate Wazuh Agent on the endpoint machine.

For this project, the planned endpoints are:

Windows Server 2022

Linux endpoint

Configure the agent with the Wazuh Manager IP address and register or enroll the agent.

# Step 5: Verify Agent Connection

Start the Wazuh Agent service.

Open the Wazuh Dashboard.

Navigate to the agent management section.

Verify that the endpoint is connected and active.

<img width="1587" height="711" alt="image" src="https://github.com/user-attachments/assets/ab845990-9a55-4361-87fa-1987b17fd036" />

# Step 6: Security Monitoring

Perform the following monitoring activities:

Monitor Windows security events.

Monitor Linux system logs.

Identify failed login attempts.

Detect suspicious authentication activities.

Review security alerts.

Analyze endpoint security events.

# EXPECTED RESULTS

After successful installation and configuration:

Wazuh Dashboard should be accessible.

Wazuh Manager, Indexer, and Dashboard should be operational.

Endpoint agents should connect successfully.

Windows and Linux security events should be visible.

Security alerts should be generated for detected events.

# CONCLUSION

This project provides practical knowledge of installing and configuring Wazuh for centralized security monitoring. It helps develop an understanding of 
SIEM operations, endpoint monitoring, log analysis, threat detection, and security event investigation.






