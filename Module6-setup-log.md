# CSN190-Assignment6.2
Wireshark Project – Network Intrusion Detection &amp; Response

---

### Project Overview
This repository contains my completed work for **Assignment 6.2: Setup and Deploy First Project**.  
The project demonstrates the process of cloning a GitHub cybersecurity project, setting it up locally, and analyzing network data using Wireshark.

I cloned the repository **Incident-Response-Projects-for-Beginners** and worked on **Project 3: Network Intrusion Detection and Response**.  
The main goal was to analyze network traffic, identify the top talker (145.254.160.237), and visualize HTTP activity using Wireshark’s filters and I/O Graph.

---

### Tools Used
- Visual Studio Code  
- Git  
- Wireshark  
- GitHub Copilot (AI Assistant)

---

### What I Learned
- How to clone a project from GitHub and explore it locally.  
- How to analyze `.pcap` files using Wireshark.  
- How to identify suspicious traffic using filters and graphs.  
- How AI tools can help cybersecurity professionals troubleshoot faster.  

---

### Repository Contents
| File | Description |
|------|--------------|
| `Module6-setup-log.md` | Step-by-step documentation and notes |
| `wireshark_screenshot.png` | Screenshot of filtered traffic and graph |
| `http.cap` | Sample capture file analyzed in Wireshark |
| `README.md` | This summary file |

---

## Brief Report – Assignment 6.2

For this project, I cloned the GitHub repository **“Incident-Response-Projects-for-Beginners”**  
(https://github.com/0xrajneesh/Incident-Response-Projects-for-Beginners).  
I focused on **Project 3: Network Intrusion Detection and Response**, which demonstrates how to analyze network traffic and identify possible intrusions.  

After installing **Git**, **Visual Studio Code**, and **Wireshark** on my Windows computer,  
I cloned the repository into my CSN190 folder and opened the sample capture file `http.cap` in Wireshark.  
I applied filters such as `http` and `ip.addr == 145.254.160.237 && http` to locate the top talker and visualize activity through the I/O Graph.  

At first, I wasn’t sure which IP address to analyze, but using **Statistics → Endpoints → IPv4** helped me identify that 145.254.160.237 had the highest packet count.  
Once filtered, the graph clearly showed HTTP traffic spikes.  
Through this process, I learned how to use Wireshark to isolate suspicious network behavior and understand data flows.  

The **AI agent** in VS Code guided my setup, explained filters, and simplified troubleshooting.  
I also realized how combining **AI tools with cybersecurity software** creates a strong advantage for modern cyber professionals—  
it speeds up analysis, problem-solving, and decision-making.

---


---

### 🔗 Original GitHub Project
[Incident-Response-Projects-for-Beginners](https://github.com/0xrajneesh/Incident-Response-Projects-for-Beginners)
