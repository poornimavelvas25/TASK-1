# INTERVIEW QUESTIONS
1. What is an open port?

An open port is a network port on a device that is actively listening for incoming connections.
It means a service or application is running and ready to communicate with other systems over that port.

2. How does Nmap perform a TCP SYN scan?

In a TCP SYN scan, Nmap sends a SYN packet to a target port.
If it receives SYN-ACK, the port is open.
If it receives RST, the port is closed.
Nmap does not complete the full handshake, so it’s fast and stealthy.

3. What risks are associated with open ports?
   
Open ports can expose services to attackers. 
If a service is vulnerable or misconfigured, attackers can exploit it to gain unauthorized access, perform attacks, or steal data.

4. Difference between TCP and UDP scanning?
   
TCP scanning checks ports that use TCP and relies on handshake responses. It is more reliable.
UDP scanning checks UDP services, but it is slower and less reliable because UDP does not send clear responses.

5. How can open ports be secured?
   
Open ports can be secured by closing unused ports, using firewalls, applying patches, using strong authentication, and restricting access with IP rules.

6. Firewall's role regarding ports
   
A firewall controls which ports are allowed or blocked. It filters traffic based on rules and prevents unauthorized access to sensitive or unnecessary ports.

7. What is a port scan and why attackers perform it?
   
A port scan is the process of checking which ports are open on a system. Attackers use it for reconnaissance to find vulnerable services they can target.

8. How does Wireshark complement port scanning?
Wireshark captures and analyzes network traffic. It helps verify scan results by showing actual packets, responses, and suspicious activity during a port scan.
