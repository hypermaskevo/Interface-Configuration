# Interface-Configuration
This lab focuses on basic interface configuration in Cisco Packet Tracer. The following tasks were performed:
![image](https://github.com/user-attachments/assets/8ea650fa-4c17-42d3-a341-48ce82ff9f83)
1. **Configure hostnames** for all devices:
   - `R1`, `SW1`, and `SW2`

2. **Set IP addresses** for:
   - **Router R1**
   - **PC1, PC2, PC3, PC4**

3. **Manually configure speed and duplex** on interfaces connected to networking devices (e.g. switches and routers).

4. **Add interface descriptions**:
   - Interfaces were labeled to indicate purpose (e.g. `## to end hosts ##`, `## not in use ##`).

5. **Disable unused interfaces**:
   - All FastEthernet ports not connected to devices were administratively shut down to increase security and reduce errors.

---

## ⚙️ Device Summary

| Device | Hostname | Interfaces Configured |
|--------|----------|------------------------|
| Router | R1       | G0/0, G0/1, G0/2       |
| Switch | SW1      | Fa0/1 – Fa0/4, G0/1    |
| Switch | SW2      | Fa0/1 – Fa0/4, G0/2    |
| PCs    | PC1–PC4  | Fa0 NICs               |

---

## 🖥️ CLI Commands Snapshot (SW2)

```bash
SW2(config-if-range)# do sh int status
# Output shows interfaces labeled, disabled if unused
