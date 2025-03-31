# University Campus Network (Cisco Packet Tracer)

## 📌 Overview
This project showcases a **University Campus Network** built in **Cisco Packet Tracer**, consisting of **50+ nodes** with multiple VLANs for efficient network segmentation. The network supports essential services like **HTTPS, DNS, and DHCP**, along with an **SMTP email service** configured for two demo nodes.

## 📡 Network Features
- **Multiple VLANs** for different university departments.
- **DNS, DHCP, and Web (HTTPS) services** implemented.
- **SMTP Email Service** configured for selected nodes.
- **Hierarchical Network Design** for scalability and security.
- **Inter-VLAN Routing** to allow controlled communication between departments.

## 🏫 VLAN Configuration
The network is structured using VLANs to separate traffic efficiently:

| VLAN ID | Department            | Subnet          |
|---------|----------------------|----------------|
| 10      | Admin                | 192.168.1.0/24 |
| 20      | Finance              | 192.168.2.0/24 |
| 30      | HR                   | 192.168.3.0/24 |
| 40      | Business             | 192.168.4.0/24 |
| 50      | Engineering & Computing | 192.168.5.0/24 |
| 60      | Art & Design         | 192.168.6.0/24 |
| 70      | Student Lab          | 192.168.7.0/24 |
| 80      | IT Department        | 192.168.8.0/24  |
| 90      | Classroom 2          | 192.168.9.0/24  |
| 100     | Classroom 1          | 192.168.10.0/24 |

Each VLAN is connected through **layer 3 switches and routers** to ensure controlled inter-department communication.

## 🌐 Network Services
- **DHCP Server**: Assigns IP addresses dynamically to end devices.
- **DNS Server**: Resolves domain names for seamless browsing.
- **Web Server**: Hosts internal university websites over HTTPS.
- **Email Server (SMTP)**: Configured for two nodes for demonstration.

## 🛠️ How to Use
1. **Clone the repository**:
   ```sh
   git clone https://github.com/yourusername/university-campus-network.git
   cd university-campus-network
   ```
2. **Open the .pkt file in Cisco Packet Tracer**.
3. **Test DHCP**: Check if devices receive IPs dynamically. ( ** Check in the ipconfiguration , if it is assigned to static or DHCP , if not DHCP , then change it to DHCP ** )
4. **Test DNS**: Ping domain names from PCs.
5. **Access Web Server**: Open a browser and visit the internal university website.
6. **Send Emails**: Use SMTP-configured nodes for testing.

## 📈 Future Enhancements
- Implement **Firewall Rules** for better security.
- Add **Load Balancing** for web services.
- Configure **VPN for remote access**.

🚀 **A fully functional and scalable university network model!** Let me know if you need any modifications! 🔥

