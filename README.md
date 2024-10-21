# IT-Security

This repository provides a comprehensive overview of various **IT-Security measures** that can be implemented to enhance system security. While the documentation is primarily written in German, an English translation will be provided at a later time.

## Cisco Packet Tracer

**Cisco Packet Tracer** is a tool used to design, visualize, and simulate network topologies, enabling users to verify aspects like **network reliability** and **security**. In this folder, you will find simple network setups created with Cisco Packet Tracer. For more information about the tool, visit the official [Cisco Packet Tracer Tool Page](https://www.netacad.com/cisco-packet-tracer).

<div style="display: flex; justify-content: center; gap: 20px">
  <img src="https://parity.org/wp-content/uploads/2023/02/cisco-logo-white.png" alt="Cisco Logo" width="300"/>
  <img src="https://www.computernetworkingnotes.com/wp-content/uploads/ccna-study-guide/images/csg132-01-cisco-packet-tracer.png" alt="Cisco Packet Tracer" width="300"/>
</div>

## Monitoring

**Monitoring** is essential for tracking system activity and identifying potential security threats. In this exercise, we focus on **Input Capture**, a technique that captures input data like keystrokes.

Tools such as [**E-Guard**](https://github.com/aelder202/E-Guard) help detect if malicious software, such as _keyloggers_, has been installed to capture keystrokes and send them to an **SMTP server**. E-Guard flags any processes that communicate via SMTP, allowing for the identification and disruption of these connections.

Tech Stack:

- **E-Guard**
- **Python**
- **Outlook**

## SSL Certification

Data encryption is critical to prevent sensitive information from being intercepted during transmission (e.g., to prevent **Man-in-the-Middle attacks**). In this sub-project, an **SSL/TLS certificate** is created for a simple website hosted via XAMPP, ensuring that data is encrypted during transmission.

## Technical Policy

Creating and enforcing **technical policies** and conducting regular **security audits** help reduce vulnerabilities and lower the risk of attacks. This sub-project includes sample policies and audit processes aimed at securing systems and devices.

## Threat Modelling

All systems are vulnerable to potential threats. Through **Threat Modelling**, both **internal** and **externally accessible systems** (such as servers, sensors, APIs, etc.) can be analyzed for potential risks. This sub-project involves using the **Microsoft Threat Modelling Tool** to document and analyze common vulnerabilities, providing insight into how to mitigate them.

<div style="display: flex; justify-content: center; gap: 20px">
  <img src="https://info.threatmodeler.com/hs-fs/hubfs/Microsoft%20Threat%20Modeling%20Tool.webp?width=768&height=768&name=Microsoft%20Threat%20Modeling%20Tool.webp" alt="Cisco Packet Tracer" width="300"/>
</div>

## Windows Hardening

The objective of this project is to **secure and regulate Windows systems**. By setting up a **Windows 10 server** and leveraging **Microsoft's Active Directory**, user roles are created to control access and ensure better system security.

---

This repository provides the foundational steps for improving IT security across various domains, from network reliability and threat detection to encryption and system hardening.
