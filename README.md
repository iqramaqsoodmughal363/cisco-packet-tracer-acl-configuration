# 🛡️ Cisco Packet Tracer: ACL Configuration

<p align="center">
  <b>Securing network traffic using Access Control Lists on Cisco IOS.</b>
</p>

<p align="center">
  <em>"A hands-on lab log demonstrating the configuration of interfaces and Access Control Lists (ACLs) on a Cisco 2911 Router using Cisco IOS."</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Made%20with-%E2%9D%A4%EF%B8%8F-red" alt="Made with Love">
  <img src="https://img.shields.io/badge/Tool-Cisco%20Packet%20Tracer-blue" alt="Tool">
  <img src="https://img.shields.io/badge/Domain-Network%20Security-green" alt="Domain">
  <img src="https://img.shields.io/badge/Status-Complete-success" alt="Status">
</p>

---

## 📋 Overview

This repository contains a text-based log (`ACL in packet tracer.txt`) of a Cisco Router configuration. It demonstrates how to set up a basic network topology, assign IP addresses to Gigabit Ethernet interfaces, and secure the network using Access Control Lists (ACLs).

---

## ✨ Key Configurations Shown

* **Initial Setup:** Bypassing the initial configuration dialog and entering the CLI.
* **Interface Configuration:** Assigning IP addresses (`192.168.1.1` and `10.0.0.1`) to `GigabitEthernet 0/0` and `0/1`.
* **Bringing Interfaces Up:** Using the `no shutdown` command to activate the ports.
* **ACL Logic:** (Based on the file context) Implementing rules to permit or deny specific traffic between the LAN and WAN.

---

## 📂 File Structure

```text
cisco-packet-tracer-acl-configuration/
│
├── 📄 ACL in packet tracer.txt    # Router configuration log
└── 📄 README.md                   # This file
```

---

## 🚀 How to Use

1. **Open Cisco Packet Tracer:** Launch the application.
2. **Add a Router:** Drag and drop a **Cisco 2911** router into the workspace.
3. **Access the CLI:** Click the router, go to the **CLI** tab.
4. **Apply the Commands:**
   Copy the commands from the `.txt` file and paste them into the CLI.
   ```bash
   enable
   configure terminal
   interface GigabitEthernet 0/0
   ip address 192.168.1.1 255.255.255.0
   no shutdown
   ```

---

## 🎯 Key Takeaways

* **Interface Configuration:** Essential for connecting routers to different network segments.
* **Network Security:** ACLs are the first line of defense in Cisco networking, allowing administrators to filter traffic based on IP addresses and protocols.
* **IOS Navigation:** Mastery of moving between User EXEC, Privileged EXEC, and Global Configuration modes.

---

## 👩‍💻 Author

**Iqra Maqsood Mughal**

*Software Engineer · Full-Stack Developer · Code Craftsman · Android App Developer · Problem Solver 🚀*

```javascript
const codeIsLife = "Code is life";
while (true) { 
    learn(); 
    build(); 
    innovate(); 
}
```

---

## 📅 Date

October 26, 2026

---

## 📄 License

This material is intended for educational and personal study purposes.
