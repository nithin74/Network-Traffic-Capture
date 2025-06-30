# Task 5 - Network-Traffic-Capture
Capture live network packets and identify basic protocols and traffic types.
# 📌 Objective
Capture live network packets using Wireshark and identify basic network protocols in the traffic.
# 🧰 Tools Used
Wireshark: Network protocol analyzer for capturing and analyzing packets.
Operating System: [Your OS - e.g., Windows 10 / Ubuntu 22.04]
# 📦 Steps Performed
Installed Wireshark from https://www.wireshark.org/.
Started a live capture on the active interface (Wi-Fi/Ethernet).
Generated traffic by:
Browsing websites (e.g., example.com)
Running terminal commands (ping google.com)
Stopped the capture after approximately 1 minute.
Applied filters in Wireshark to analyze protocols.
Identified and noted down at least 3 distinct protocols.
Exported the capture as a .pcap file.
Compiled this short report.
#🔍 Protocols Identified
| Protocol | Description                      | Example Packet Info / Notes                      |
|----------|----------------------------------|--------------------------------------------------|
| TCP      | Transmission Control Protocol    | Handshake packets, reliable data transfer        |
| DNS      | Domain Name System               | DNS queries and responses                        |
| HTTP     | HyperText Transfer Protocol      | Web browsing requests/responses                  |
| ICMP     | Internet Control Message Protocol| Ping requests and replies                        |
| ARP      | Address Resolution Protocol      | Resolves IP addresses to MAC addresses           |
| HTTPS    | Secure HTTP over SSL/TLS         | Encrypted web traffic (port 443), TLS handshake  |



# 📸 Screenshots
🖥️ Live Capture in Progress
🗂️ Filtered DNS Traffic
📶 Protocol Hierarchy Display
# 📁 Files Included
traffic_capture.pcap: Raw packet capture file.
README.md: This report file.
# 🧠 Key Learnings
Understood how to use Wireshark to monitor real-time traffic.
Learned to apply protocol filters (e.g., http, dns, tcp) for better analysis.
Observed differences in how various protocols behave on the network.
# 🧪 Sample Filters Used
http
dns
tcp
icmp
