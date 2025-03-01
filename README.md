# 🕷️ Reverse Engineering Agent Tesla Malware  

## 🛠️ About This Malware Analysis  
This repository provides an **in-depth reverse engineering analysis** of **Agent Tesla**, a sophisticated **Remote Access Trojan (RAT) and spyware 🔍**. Since its discovery in **2014**, Agent Tesla has evolved from a basic **keylogger** into an advanced malware capable of:  

- 🛑 **Credential theft** from browsers, email clients, FTP tools, and VPNs  
- 🎥 **Keylogging & screenshot capture** for data exfiltration  
- 🌍 **Remote system control** through C2 communication  
- 🕵️ **Anti-analysis techniques** to evade security tools  
- 🔐 **Obfuscation & encryption** to bypass detection  

This project uses **static and dynamic analysis techniques** to uncover **Agent Tesla’s obfuscation methods, persistence mechanisms, and network communication strategies**.  

---

## ⚠️ Disclaimer  
🚨 **Warning**: This repository is for **educational and research purposes only**. Running malware samples on a live system is highly dangerous. Always use an **isolated virtual machine (VM) or a secure sandbox environment**.  

---

## 📌 Key Findings  
✔ **AutoIt-based packing & obfuscation** 🏴‍☠️  
✔ **Registry manipulation for persistence** 🔄  
✔ **Stealing credentials from 50+ applications** 🔓  
✔ **Communicates with C2 servers via HTTP, SMTP, FTP, and Telegram** 🌐  
✔ **Detects virtual environments & debuggers to evade detection** 🕶️  

---

## 📖 Methodology  
This analysis was conducted using a combination of **static and dynamic analysis techniques**.  

### **🔬 Static Analysis Tools**  
- 🛠️ **VirusTotal** – Online malware detection  
- 🛠️ **PEStudio** – PE file analysis  
- 🛠️ **dnSpy** – .NET reverse engineering  
- 🛠️ **AutoIt Extractor** – AutoIt decompiler  

### **⚡ Dynamic Analysis Tools**  
- 🛠️ **ProcMon** – System process monitoring  
- 🛠️ **RegShot** – Registry modification detection  
- 🛠️ **Process Explorer** – Real-time process investigation  
- 🛠️ **PESieve** – Memory scanning and malware unpacking  

### For Detailed Analysis, Please refer to the [Tesla-Agnet-TrojanHorse/TeslaAgent Documentation.pdf](https://github.com/sakshat-bhattarai/Tesla-Agnet-TrojanHorse/blob/main/TeslaAgent%20Documentation.pdf)

### Malware Sample which was used in this project [Sample](https://bazaar.abuse.ch/sample/e17062f3e40417b32b67892e68cd134a6b5ea179e75182749ced9249fe049fa4)

