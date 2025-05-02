# NAME:SABARINATH.R
# REGISTER NO:212223100048

# Network-traffic-capture-and-analysis-with-Wireshark
## AIM:
To capture and analyze network traffic using Wireshark in order to observe protocols, packets, and potential anomalies.

## DESIGN STEPS:
### Step 1:
Install Wireshark using the command:

### Step 2:
Launch Wireshark and select the appropriate network interface for live traffic capture.

### Step 3:
Start the capture, apply filters (like http, tcp, ip.addr == x.x.x.x) to analyze specific traffic, and stop the capture after observing relevant data.

## PROCEDURE:
Open Wireshark and Select a Network Interface • Launch Wireshark. • Select an active interface (like Wi-Fi or Ethernet) to start capturing packets.<br/>

Start Capturing Packets • Click the blue shark fin icon or double-click the interface. • Wireshark will start capturing all real-time traffic.<br/>

Apply Filters to Focus on Specific Traffic • Use filters like http, ip.addr == 192.168.1.1, or tcp.port == 80 in the top filter bar to narrow down results.<br/>

Analyze Packet Details • Click on a packet to view its detailed breakdown including frame, Ethernet, IP, TCP/UDP layers, and data payload.<br/>

Export or Save the Capture • Go to File > Save As to store the capture in .pcap format for future analysis.<br/>

## OUTPUT:
# Open Wireshark and Select a Network Interface 
![Screenshot 2025-04-28 102150](https://github.com/user-attachments/assets/d58486ef-f9e4-4a8a-bbc4-b2c64e35e218)

# Start Capturing Packets
![Screenshot 2025-04-28 102222](https://github.com/user-attachments/assets/f3305695-8fda-42d9-9c50-05f5c30a74ee)

# Apply Filters to Focus on Specific Traffic
![Screenshot 2025-04-28 102059](https://github.com/user-attachments/assets/3f2524ef-83d0-4732-8c29-9bef04c05e88)  

# Analyze Packet Details

![Screenshot 2025-04-28 102222](https://github.com/user-attachments/assets/0be516a9-f78e-4ebf-9033-2f7171484ab4)

![Screenshot 2025-04-28 102336](https://github.com/user-attachments/assets/ff380c07-ab45-45d7-8874-6781e71f8e53)

# save and export the capture
![Screenshot 2025-04-28 102415](https://github.com/user-attachments/assets/66c208c0-791f-467a-b2e3-3f4cf6dbb2ec)

## RESULT:
Network traffic was successfully captured and analyzed using Wireshark.
