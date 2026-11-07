# Wireshark SOC Labs — Packet Analysis & Threat Detection

## 📌 Overview
This repository documents my completed hands-on challenges from the **Wireshark SOC Lab** series by Network Walks. The labs focus on real-world network packet inspection, anomaly detection, payload analysis, and identifying threat actor tactics using Wireshark.

All labs were completed with a **100% score**.

---

## 🧪 Completed Labs & Key Objectives

### 🔹 Lab 3: Identify the Attacker's IP
- **Focus:** SYN scan detection & network reconnaissance.
- **Key Deliverables:** Analyzed PCAP files to filter TCP SYN packets, identified source/target IP addresses, mapped probed ports, and isolated open vs. closed port responses.

### 🔹 Lab 4: Follow TCP Stream (Part 1)
- **Focus:** Stream reassembly & chat inspection.
- **Key Deliverables:** Reassembled TCP streams to inspect unencrypted chat conversations, identified stream numbers, extracted temporary credentials, and recovered Wi-Fi configuration details.

### 🔹 Lab 5: Follow TCP Stream (Part 2)
- **Focus:** HTTP traffic analysis & artifact recovery.
- **Key Deliverables:** Tracked HTTP request/response flows, identified hidden pages, extracted code words, located backup server details, and analyzed file download paths.

### 🔹 Lab 6: HTTP Plain Text Credentials
- **Focus:** Unencrypted credential exposure.
- **Key Deliverables:** Filtered HTTP POST requests to capture plaintext usernames and passwords, analyzed authentication flow failures, and documented mitigation recommendations (enforcing HTTPS/TLS).

### 🔹 Lab 7: Brute Force Catch
- **Focus:** Password spraying & brute-force detection.
- **Key Deliverables:** Identified high-frequency failed login attempts (HTTP status codes), isolated successful login events, identified target user accounts, and extracted compromised credentials.

### 🔹 Lab 8: VoIP Call Replay
- **Focus:** Telephony protocol security.
- **Key Deliverables:** Analyzed SIP and RTP traffic, identified call setup protocols, verified caller IDs and audio codecs, and performed audio stream extraction/replay.

---

## 🛠️ Tools & Technologies
- **Traffic Analysis:** Wireshark
- **Protocols Analyzed:** TCP, UDP, HTTP, SIP, RTP
- **Concepts Covered:** Packet Filtering, Stream Reassembly, Brute-Force Analysis, Credential Recovery, VoIP Inspection

---

## 📁 Evidence & Verification
Lab completion screenshots verifying 100% completion scores across all modules are included in the `/screenshots` folder.
