# 📱 Mobile Network Forensic & Traffic Analysis Lab

## 📌 Project Overview
This lab demonstrates the ability to perform deep packet inspection and forensic analysis on Android mobile devices. Using a **Redmi 9A** as the target endpoint, I established a secure bridge to capture real-time system logs and network traffic to identify potential security threats and unauthorized background activities.

## 🛠️ Tools & Technologies
*   **Packet Sniffer:** Wireshark
*   **Bridge Tools:** ADB (Android Debug Bridge) & Androiddump (Extcap)
*   **Endpoint:** Redmi 9A (MIUI Environment)
*   **Analysis Filters:** Advanced Display Filters for DNS, HTTP, and SELinux audits.

## 🔍 Key Findings from the Lab
During the analysis of the captured logs (as seen in the attached screenshots), several key security events were identified:

1.  **Unauthorized Access Attempts:** Detected multiple `Permission Denied` errors at the kernel level, indicating background processes attempting to bypass standard security protocols.
2.  **SELinux Audit:** Identified `avc: denied` events related to Xiaomi hardware interfaces, proving the effectiveness of the system's Mandatory Access Control (MAC).
3.  **App Behavior Monitoring:** Tracked background activities of high-privilege apps like `com.facebook.appmanager` and account synchronization processes for Telegram and WhatsApp.
4.  **System Integrity:** Spotted missing package errors for `com.google.android.art`, suggesting potential environment inconsistencies or post-update artifacts.

## 📸 Lab Evidence
*   **Interface Configuration:** Successful integration of ADB with Wireshark.
*   **Live Traffic Capture:** Monitoring real-time data flow from the mobile device.
*   **Filtering & Analysis:** Utilizing complex filters to isolate suspicious packets.

## 🚀 Professional Impact
This project showcases my readiness for a **SOC Analyst** or **Security Researcher** role, specifically in mobile endpoint security and incident response. It proves competence in setting up complex forensic environments and interpreting low-level system logs.
