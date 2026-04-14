# 👋 Hi, I'm Supakron Krommarin (ศุภกร กรมรินทร์)

> **Student ID:** 673380061-4 | **Khon Kaen University, Faculty of Science**
> 🎓 CCNA: Introduction to Networks — Cisco Networking Academy *(Completed 31 Mar 2026)*

---

## 🧠 About Me

สวัสดีครับ! ผมเป็นนักศึกษาสาขาวิทยาการคอมพิวเตอร์ที่มีความสนใจด้านเครือข่ายคอมพิวเตอร์ (Computer Networks), โครงสร้างพื้นฐานระบบ (Infrastructure), และสถาปัตยกรรม Microservices ในชีวิตประจำวัน ผมใช้เครือข่ายเพื่อการทำงาน การเรียน และการพัฒนาตัวเอง

---

## 🏆 Certification

| Certificate | Provider | Date |
|---|---|---|
| 🥇 **CCNA: Introduction to Networks** | Cisco Networking Academy @ KKU | 31 Mar 2026 |

**Cert ID:** `d1bfb960-7fca-4fcf-97d3-ccf9e65738ba`

---

## 📚 Labs & Assignments

### 🔬 Lab Work

| Lab | Topic | Key Skills |
|---|---|---|
| **LAB 1** | Complete Lab-Focused Teaching Package | OSI Model, ARP, Encapsulation, Ping, Troubleshooting |
| **LAB 2** | Secure & Scalable VLAN Design (Router-on-a-Stick) | VLANs, 802.1Q Trunking, Subnetting /26, Inter-VLAN Routing |
| **Lab 3** | MIME File Transfer over Router-on-a-Stick + Wireshark | VLAN, TCP, MIME, Wireshark Packet Analysis |
| **Lab 4** | Simulated Internet with Stateful vs Stateless Services | NAT, Static Routing, Stateless/Stateful APIs, Podman, IaC |
| **LAB 5** | Internet Edge + ISP Serial WAN + Microservices | NAT Overload, Serial WAN, FastAPI Microservices, Enterprise Routing |

---

### 📝 Assignments

| Assignment | Topic | Description |
|---|---|---|
| **Assignment 1** | Computer Networks in Daily Life | เรียงความเกี่ยวกับเครือข่ายในชีวิตประจำวัน: Wi-Fi, Line, Google Maps, Gaming |
| **Assignment 2** | Network Topology Design | ออกแบบ 3 เครือข่าย: Point-to-Point, LAN with Switch, Routed Multi-LAN |
| **Assignment 4** | TCP/UDP Protocol Analysis | Multiplexing, TCP Handshake, FTP/DNS/Email Traffic via Cisco Packet Tracer |

---

## 🛠️ Technical Skills

### Networking
```
✅ VLAN Configuration & Trunking (802.1Q)
✅ Router-on-a-Stick (Inter-VLAN Routing)
✅ Static Routing & Default Routes
✅ NAT / NAT Overload (PAT)
✅ Serial WAN (ISP /30 links)
✅ DHCP Configuration
✅ TCP/IP, UDP, ARP, ICMP, DNS, HTTP, FTP, SMTP, POP3
✅ Cisco IOS CLI (show ip route, show ip nat translations, etc.)
✅ Wireshark Packet Analysis
✅ Cisco Packet Tracer Simulation
```

### Software & Tools
```
✅ Python (FastAPI Microservices)
✅ Podman / Docker (Container Deployment)
✅ Infrastructure as Code (IaC) — manage.py CLI
✅ VS Code
✅ Git & GitHub
```

---

## 🗺️ Network Topologies I've Built

### Lab 1 — Basic LAN
```
R1 (192.168.1.1)
 |
S1 (192.168.1.2)
 ├── PC1 (192.168.1.10)
 └── PC2 (192.168.1.11)
```

### Lab 2 — Router-on-a-Stick VLAN
```
R1 G0/0 (802.1Q Trunk)
 |
S1
 ├── Fa0/1 → PC-A (VLAN 10 — USERS)
 ├── Fa0/2 → PC-B (VLAN 20 — SERVERS)
 └── Fa0/3 → PC-C (VLAN 99 — MANAGEMENT)
```

### Lab 5 — Enterprise Edge + ISP Serial WAN
```
INTERNET
 |
R1 G0/0 [DHCP, NAT Outside]
R1 G0/1 → LAN A (192.168.10.0/24) → ServerA [Microservices]
R1 S0/0/0 ──── 100.10.10.0/30 (ISP) ──── R2 S0/0/0
                                           R2 G0/1 → LAN B (192.168.20.0/24) → ServerB [Microservices]
```

---

## 🧪 Microservices Architecture (Lab 4 & 5)

Deployed **FastAPI-based microservices** across two LAN sites connected via WAN:

| Service | Port | Description |
|---|---|---|
| Upload Service | 8000 | รับไฟล์ upload |
| Processing Service | 8001 | ประมวลผลไฟล์ |
| AI Service | 8002 | วิเคราะห์ด้วย AI |
| Gateway | 9000 | Orchestration |

**Cross-site test:** `ClientA → R1 → Serial ISP → R2 → ServerB`

---

## 👥 Team Projects

หลายแล็บเป็นงานกลุ่ม 5 คน:

| Student ID | Name |
|---|---|
| 673380036-3 | ณภัทร อรัญพูล |
| 673380043-6 | ธนินธร อันทรบุตร |
| **673380061-4** | **ศุภกร กรมรินทร์ (Me)** |
| 673380267-4 | ณัชพล เพ็งพล |
| 673380268-2 | ณัฐกรณ์ อันธิสาร |

---

## 💡 Key Concepts Learned

- **OSI Model** — เข้าใจการทำงานของแต่ละ Layer ตั้งแต่ Physical ถึง Application
- **TCP vs UDP** — ความแตกต่างด้านความเชื่อถือได้และ Use Cases
- **Multiplexing** — การส่งข้อมูลหลายโปรโตคอลผ่าน Port Numbers
- **VLANs & Security** — การแยก Broadcast Domain และรักษาความปลอดภัย
- **NAT** — การแปล Private IP → Public IP ด้วย PAT/Overload
- **Stateless vs Stateful** — ความแตกต่างของ API ที่จำและไม่จำ session
- **MIME Protocol** — การระบุชนิดข้อมูลใน Application Layer

---

## 📊 Course Progress

```
LAB 1  ████████████████████ ✅ Complete
LAB 2  ████████████████████ ✅ Complete
LAB 3  ████████████████████ ✅ Complete
LAB 4  ████████████████████ ✅ Complete
LAB 5  ████████████████████ ✅ Complete
Assignment 1  ████████████████████ ✅ Complete
Assignment 2  ████████████████████ ✅ Complete
Assignment 4  ████████████████████ ✅ Complete
CCNA Cert     ████████████████████ ✅ Earned
```

---

## 📬 Contact

- 🏫 **University:** Khon Kaen University, Faculty of Science
- 📧 **Email:** supakron-k@kkumail.com
- 🎓 **Program:** CCNA: Introduction to Networks — Cisco Networking Academy

---

<div align="center">

*"เครือข่ายคอมพิวเตอร์เป็นส่วนสำคัญที่ทำให้การทำงาน การเรียน การสื่อสาร และการเล่นเกมเป็นไปอย่างสะดวก รวดเร็ว และมีประสิทธิภาพในชีวิตประจำวัน"*

**— Supakron Krommarin, Assignment 1**

</div>
