# Task 4: Setup and Use a Firewall on Windows/Linux

In this task, I learned how to set up and manage a firewall on my Linux system using UFW (Uncomplicated Firewall). I explored how to install, enable, and configure firewall rules to control network traffic, and tested the effectiveness of these rules.

---

## Key Concepts I Explored

- **Firewall Basics:**  
  A firewall acts as a barrier between trusted and untrusted networks, filtering traffic based on defined rules.

- **UFW (Uncomplicated Firewall):**  
  UFW provides a simple command-line interface for managing firewall rules on Linux.

- **Blocking Insecure Services:**  
  I blocked inbound traffic on port 23 (Telnet), which is considered insecure, to prevent unauthorized remote access.

- **Allowing Essential Services:**  
  I allowed inbound traffic on port 22 (SSH) to enable secure remote access.

- **Testing and Managing Rules:**  
  Used `nmap` to verify blocked ports and learned how to list, add, and remove firewall rules dynamically.

---

## My Takeaways

- Firewalls are essential for protecting systems from unauthorized access and attacks.
- Blocking unused or insecure ports (like Telnet) reduces the attack surface.
- Allowing only necessary services (like SSH) helps maintain both security and usability.
- Regularly reviewing and updating firewall rules is important for ongoing protection.

---

For detailed steps, screenshots, and exported firewall rules, see:

- [workflow.md](workflow.md) : step-by-step process with images
- [ufw_rules.txt](ufw_rules.txt) : exported firewall rules after configuration
