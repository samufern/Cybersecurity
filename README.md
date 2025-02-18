# Cybersecurity Project

## 📌 Project Overview
This project focuses on **network traffic analysis** and **web security attacks**. It includes practical exercises on analyzing network traces and identifying vulnerabilities in web applications.

## 🚀 Getting Started

### 📋 Prerequisites
Ensure you have the following installed:
- Wireshark (for analyzing `.pcap` files)
- Python 3.x (for potential scripting analysis)
- A virtualized environment for safe web security testing
- KaliLinux
- Infested traces

### 🔧 Installation
Clone the repository:
```sh
git clone https://github.com/your_username/Cybersecurity-main.git
cd Cybersecurity-main
```

## 🏗 Project Structure
```
Cybersecurity-main/
│── Analisis de trazas.pdf   # Network traffic analysis report
│── Ataques web.pdf          # Web security attack exercises
│── trace_1.pcap             # Packet capture file for analysis
│── trace_2.pcap             # Additional network trace
│── trace_3.pcap             # HTTP-related trace
│── trace_4.pcap             # Malware-infected traffic trace
```

## 🎯 Usage

### Analyzing Network Traffic
To analyze a `.pcap` file, open Wireshark and load a trace:
```sh
wireshark trace_1.pcap
```
Use filters to extract relevant packets, e.g.:
```sh
http.request.method == "POST"
```

### Web Security Testing
The **web security exercises** cover:
- Common attack techniques (SQL injection, XSS, CSRF, etc.)
- Analysis of vulnerable web applications
- Strategies for mitigating threats

## ✅ Testing
- Use Wireshark to inspect traffic patterns.
- Perform simulated attacks in a controlled environment.
- Document findings and suggest security enhancements.

## 🛠 Built With
- **Wireshark** - Network packet analysis
- **Burp Suite / OWASP ZAP** - Web vulnerability testing
- **Python** - Scripting for network security analysis

## 🤝 Contributing
If you wish to contribute, feel free to fork the repository, make improvements, and submit a pull request.

---

