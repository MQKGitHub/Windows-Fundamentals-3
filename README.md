## 🛡️ Windows Fundamentals 3

**Room:** [Windows Fundamentals 3 — TryHackMe](https://tryhackme.com/room/windowsfundamentals3xzx)  
**Status:** ✅ Completed  
**Date:** *(29 April 2025)*  

### 🎯 Objective  
To explore the core security features built into the Windows operating system, including tools like Windows Defender, BitLocker, and the firewall. The aim was to understand how Windows protects against threats and how users can manage these security settings effectively.

---

### 🗝️ Key Concepts  
- **Windows Updates** — Microsoft's patching service that keeps the OS secure and up-to-date.  
- **Windows Security** — Central hub for managing antivirus, firewall, and other protective features.  
- **Defender Antivirus** — Real-time threat detection and protection built into Windows.  
- **Firewall & Network Profiles** — Controls traffic via port filtering based on network type.  
- **App & Browser Control** — SmartScreen and exploit protection for safer application use.  
- **Device Security** — TPM, memory integrity, and core isolation for hardware-level protection.  
- **BitLocker** — Drive encryption feature protecting data from theft or tampering.  
- **Volume Shadow Copy** — Backup and recovery feature using restore points and snapshots.

---

### 🛠️ Tools Used  
- Windows Defender Security Centre — Used to view and configure antivirus, firewall, and app control.  
- WF.msc — Used to open advanced Windows Firewall settings.  

---

### ⚠️ Challenges Faced  
- Understanding the differences between firewall profiles (domain, private, public) took a bit of reading.  
- Getting familiar with the status indicators in Windows Security (green, yellow, red) was key to grasping the current protection status.  
- BitLocker was not available in the VM, so it had to be studied through documentation and external examples.

---

### 🧠 What I Learned  
- Learned how to use Windows Defender to scan, quarantine, and exclude files.  
- Gained a solid understanding of how Windows categorises network profiles and applies firewall rules accordingly.  
- Discovered how VSS (Volume Shadow Copy) works and how it's targeted by ransomware.

---

### 🌐 Real-World Application  
> Features like BitLocker and TPM are used in real-world enterprise environments to secure laptops and workstations. Defender and SmartScreen help protect against malware and phishing in both personal and business settings.

---

### 💭 Reflections:  
- It was interesting to see how much functionality is built into Windows for free — especially Defender and firewall settings.  
- I’d like to explore BitLocker more hands-on using a Windows Pro edition VM.  
- The most memorable takeaway: Windows security is layered — and it's easy to overlook just how much it does behind the scenes.
