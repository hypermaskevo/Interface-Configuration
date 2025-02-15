# Cisco Packet Tracer Lab - Interface Configuration

## Description
This lab is a network simulation created in **Cisco Packet Tracer**, focusing on configuring network interfaces, assigning IP addresses, and optimizing connectivity settings.

### Devices Used:
- **Cisco 2911 Router** (R1)
- **Cisco 2960 Switches** (SW1, SW2)
- **PCs** (PC1, PC2, PC3, PC4)

### Network Structure:
- **Single subnet with assigned IP range:**
  - **172.16.0.0/16** (R1, SW1, SW2, and PCs)
- **All interfaces configured for proper communication**

## Objectives
- Configure the **hostname** of R1, SW1, and SW2.
- Assign and configure the **correct IPv4 addresses** on R1, PC1, PC2, PC3, and PC4.
- Manually configure **speed and duplex** on interfaces connected to networking devices.
- Set **interface descriptions** for clarity.
- Disable any **unused interfaces**.

## Setup Instructions
1. Open the **.pkt** file in Cisco Packet Tracer.
2. Configure the **hostname** of R1, SW1, and SW2.
3. Assign the correct **IPv4 addresses** to all devices.
4. Adjust **speed and duplex settings** where necessary.
5. Use `show ip interface brief` to verify interface status.
6. Configure interface **descriptions** for documentation.
7. Disable interfaces that are **not connected**.
8. Save the configuration and verify using `show running-config`.
9. Test connectivity by **pinging PC1, PC2, PC3, and PC4**.

## Screenshot
![Interface Conf](https://github.com/user-attachments/assets/b0863ea4-ee91-46d2-b7cb-6c3c88a6ea20)


## Notes
- Ensure that each PC’s **default gateway is set correctly**.
- If pings fail, check **IP configurations, duplex settings, and cable connections**.

## Author
Created for educational purposes in **Cisco Networking Labs**.

