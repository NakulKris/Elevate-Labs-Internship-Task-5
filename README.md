# Task 5 — Capture and Analyze Network Traffic Using Wireshark

## 🔍 Overview
This task involved capturing live network traffic on the local machine using Wireshark and identifying the basic protocols observed during normal activity. The goal was to verify that packet capture works correctly, apply protocol filters, and document the traffic types detected.

---

## 🛠 Steps Performed

### 1. Installed Wireshark
- Installed Wireshark on the system.
- Launched the application and verified available network interfaces.

### 2. Started Live Capture
- Selected the active network adapter.
- Began recording traffic for roughly one minute while performing light browsing and network actions.

### 3. Generated Traffic
- Accessed common websites and performed basic network operations to ensure diverse packet generation.

### 4. Stopped Capture
- Stopped the capture session to begin protocol inspection.

### 5. Applied Protocol Filters
Used Wireshark display filters to isolate different traffic types:
- `http`
- `tcp`
- `udp`
- `dns`
- `icmp`

### 6. Identified Protocols
Observed and confirmed at least three distinct protocol categories present in the capture:
- **DNS** – domain lookup requests and responses.
- **TCP** – general web and application communication.
- **ICMP** – ping and diagnostic communication.

### 7. Exported the Capture
- Saved the full session as a `.pcapng` file (`Task5.pcapng`) for submission.

---

## 📑 Summary of Findings

| Protocol | Purpose Observed | Notes |
|---------|------------------|-------|
| **DNS** | Domain name resolutions | Expected during normal browsing |
| **TCP** | Web traffic, connection establishment | Majority of packets |
| **ICMP** | Network diagnostics | Normal baseline traffic |

The capture reflects routine device activity with no anomalies. The task goal — capturing and identifying core network protocols — was fully met.

---

## ✅ Conclusion

Live traffic capture was successfully completed, multiple protocol types were identified, and the pcap file was exported as required. This verifies correct Wireshark usage for basic packet observation and protocol filtering.
