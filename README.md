# Cloud-Integrated IoT Home Automation System

##  Overview
This project demonstrates a real-world IoT architecture for remotely monitoring and controlling home appliances using cloud networking, ISP infrastructure, and IoT gateways.

Unlike basic home automation projects, this system is designed to simulate actual telecom and ISP-level communication, enabling secure device control from a remote smartphone over cellular and cloud networks.



##  Problem Statement
Traditional IoT home automation systems often fail to represent real deployment scenarios involving:
- Remote access across different networks
- ISP and cloud-based routing
- Scalable client-server communication

This project addresses these challenges by implementing a **cloud-integrated, network-aware IoT control system**.



##  System Architecture
The architecture includes:

- **Smartphone (User Interface)**
- **Cellular Network (3G/4G Simulation)**
- **Central Office Server**
- **Router & Cloud Network**
- **ISP Network (DNS & IoT Servers)**
- **Home IoT Gateway**
- **IoT Devices (Light & Fan)**

📡 Data flows bidirectionally between the user and IoT devices through secure routing and cloud communication.



##  Data Flow Explanation
1. User sends a control command from a smartphone.
2. Command travels through the cellular network to the central office server.
3. The router forwards the request via the cloud.
4. ISP network resolves services using DNS and IoT servers.
5. Home gateway receives the command.
6. IoT devices (fan/light) respond accordingly.
7. Device status is sent back to the user.



##  Technologies Used
- Cisco Packet Tracer
- IoT Gateway
- Cloud Networking
- TCP/IP & Routing
- DNS Server
- IoT Devices (Fan, Light)
- Client-Server Architecture



##  Key Features
- Remote IoT device control over cloud networks
- Multi-subnet routing and ISP simulation
- Realistic telecom-based communication flow
- Scalable architecture for future expansion
- Gateway-based device management


##  Possible Enhancements
- Security authentication for IoT devices
- Automation rules (temperature-based fan control)
- Mobile app integration
- Real hardware deployment using Arduino / ESP modules
- MQTT or HTTP-based communication


##  Project Diagram

<img width="1211" height="504" alt="architecture png" src="https://github.com/user-attachments/assets/47e5ae68-41b4-4104-ae3d-2c33c6aa64f6" />




##  Learning Outcomes
- Practical understanding of IoT architecture
- Cloud and ISP network simulation
- Real-world networking concepts
- End-to-end system design thinking



## Use Cases
- Smart home systems
- Remote device monitoring
- Industrial IoT (IIoT) foundations
- Telecom-integrated IoT solutions


## Author
Saloni Kumari Singh  
BCA | IoT & Networking Enthusiast  
Aspiring Data Analyst  

🔗 GitHub: https://github.com/inolas-bit



##  License
This project is for educational and demonstration purposes. 
This was also my minor project for BCA 5th sem. 
