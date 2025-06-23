# Task 1: Scan Your Local Network for Open Ports

After working through this task, I’ve got a much better grasp of how network scanning works and why it matters for security. Here’s a quick summary of what stood out to me:

---

## Key Concepts I Explored

- **Port Scanning:**  
  I learned how port scanning helps you discover which services/devices are active on your network.

- **TCP SYN Scan:**  
  The `-sS` option in Nmap does a SYN scan, which is fast and doesn’t complete the full handshake, making it less likely to be noticed.

- **IP Ranges & Subnets:**  
  Figuring out my local IP and subnet (`10.0.2.0/24`) helped me understand how devices are grouped and addressed on a network.

- **Open Ports & Security:**  
  Every open port is a potential entry point. In my scan, only the DNS port (53) was open on one device, which is pretty normal. But if you see something unexpected, it’s a red flag.

---

## My Takeaways

- Just running a simple scan can reveal a lot about your network’s security posture.
- Nmap is powerful, but also easy to use once you get the hang of it.
- I think understanding what’s happening on your own network is the first step to keeping it secure.

---

For the full step-by-step process and screenshots, open this file [`workflow.md`](workflow.md).  
Scan results are in [`result.txt`](result.txt).
