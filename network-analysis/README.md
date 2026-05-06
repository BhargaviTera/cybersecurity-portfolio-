# 🔍 Network Traffic Analysis

## 🎯 Objective
Analyze captured network traffic to identify suspicious activity, investigate protocol communication, and extract security-relevant information using packet analysis techniques.

---

## 🛠 Tools Used
- Wireshark
- TCP/IP Protocol Analysis
- DNS & HTTP Packet Inspection
- Packet Filtering Techniques

---

## 🔍 Activities Performed

### 📡 Packet & Protocol Analysis
- Analyzed PCAP files using Wireshark to inspect network communication.
- Investigated TCP three-way handshakes and identified packet sequence behavior.
- Examined DHCP Discover, Offer, Request, and Acknowledgment traffic.
- Inspected DNS queries and responses to identify host communication.

### 🌐 Traffic Investigation
- Analyzed HTTP requests and responses to identify accessed resources and server communication.
- Investigated FTP traffic and identified credentials transmitted in plain text.
- Monitored source and destination IP addresses to understand communication flow.
- Reviewed packet timing, protocols, and connection states to identify abnormal behavior.

### 🖧 Host & Service Enumeration
- Identified active hosts, network services, and protocol usage.
- Investigated email-related communication and internal server activity.
- Reviewed traffic associated with common services such as HTTP, DNS, FTP, and SMTP.

### 🚨 Security Investigation
- Identified suspicious login attempts and unusual network activity.
- Investigated failed authentication attempts and suspicious connection patterns.
- Extracted indicators such as IP addresses, hostnames, packet numbers, and protocol details.

---

## 🔎 Example Wireshark Filters Used

```bash
ftp
dns
http
smtp
tcp.flags.syn == 1
ip.addr == 192.168.1.52
```

---

## 🧭 Investigation Methodology
1. Opened packet capture files in Wireshark.
2. Applied protocol-based and IP-based filters.
3. Investigated communication flows and packet details.
4. Identified suspicious traffic and authentication activity.
5. Extracted relevant indicators and analyzed protocol behavior.

---

## 🚩 Key Findings
- Detected unencrypted FTP credential transmission.
- Identified suspicious authentication attempts and unusual traffic behavior.
- Observed network communication between internal and external hosts.
- Extracted network indicators including IP addresses, hostnames, and packet details.

---

## 🛡 Security Recommendations
- Replace insecure protocols such as FTP with encrypted alternatives like SFTP.
- Implement continuous network monitoring and alerting for suspicious activity.
- Restrict unnecessary services and monitor failed authentication attempts.
- Apply proper network segmentation and access controls.

---

## 💡 Skills Demonstrated
- Network Traffic Analysis
- Packet Inspection & Filtering
- Protocol Analysis (TCP/IP, DNS, HTTP, FTP, DHCP)
- Security Monitoring & Investigation
- Threat Detection Fundamentals
- Network Troubleshooting

---

## 📚 Learning Outcome
This project improved my understanding of network communication, packet analysis, protocol investigation, and identifying suspicious activity using Wireshark and network security monitoring techniques.
