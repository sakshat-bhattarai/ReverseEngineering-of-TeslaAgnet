# 🔥 Reverse Engineering Agent Tesla Malware  

![GitHub repo size](https://img.shields.io/github/repo-size/yourusername/agent-tesla-analysis)
![GitHub contributors](https://img.shields.io/github/contributors/yourusername/agent-tesla-analysis)
![GitHub issues](https://img.shields.io/github/issues/yourusername/agent-tesla-analysis)
![GitHub stars](https://img.shields.io/github/stars/yourusername/agent-tesla-analysis?style=social)
![GitHub license](https://img.shields.io/github/license/yourusername/agent-tesla-analysis)

## 🛠️ About This Project  
This repository provides an **in-depth reverse engineering analysis** of **Agent Tesla**, a highly evasive **Remote Access Trojan (RAT) and spyware**. Since its discovery in **2014**, Agent Tesla has evolved from a simple **keylogger** to a powerful malware capable of:  

- **Credential theft** from over 50 applications (browsers, email clients, FTP tools, VPNs)  
- **Keylogging & screenshot capture** for data exfiltration  
- **Remote system control** through C2 communication  
- **Obfuscation & anti-analysis techniques** to evade detection  

This project explores **static and dynamic analysis** techniques to uncover its **obfuscation methods, persistence mechanisms, and network communication**.  

---

## 📌 Key Findings  
✔ **Uses AutoIt for packing & obfuscation**  
✔ **Modifies registry keys for persistence**  
✔ **Steals credentials & intercepts user activity**  
✔ **Communicates with C2 servers via HTTP, SMTP, FTP, and Telegram**  
✔ **Employs anti-VM & anti-debugging techniques**  

---

## 🧑‍💻 Methodology  
The analysis was conducted using a combination of **static and dynamic analysis** techniques.  

### **📝 Static Analysis Tools**  
- 🛠️ **VirusTotal** – Online malware detection  
- 🛠️ **PEStudio** – PE file analysis  
- 🛠️ **dnSpy** – .NET reverse engineering  
- 🛠️ **AutoIt Extractor** – AutoIt decompiler  

### **💻 Dynamic Analysis Tools**  
- 🛠️ **ProcMon** – System process monitoring  
- 🛠️ **RegShot** – Registry modification detection  
- 🛠️ **Process Explorer** – Real-time process investigation  
- 🛠️ **PESieve** – Memory scanning and malware unpacking  

---

## 📂 Folder Structure  
```plaintext
📁 agent-tesla-analysis/
│── 📄 README.md              # Project documentation  
│── 📂 Samples/               # Malware samples (if legal)  
│── 📂 Static_Analysis/       # Static analysis findings  
│── 📂 Dynamic_Analysis/      # Dynamic analysis results  
│── 📂 Tools/                 # Scripts and tools used in analysis  
│── 📂 Reports/               # Research documentation  
│── 📂 Screenshots/           # Captured screenshots of analysis  
│── LICENSE                  # Project license  
