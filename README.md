README.txt
===========

Student: 22I-2291  
Name: Abdur Rehman   
Course/Lab: Network & Cybersecurity Tools Practical  
Declaration:  
All tests were performed only on authorized machines including:
- Kali Linux (attacker machine)
- Metasploitable2 (local vulnerable lab VM)
- Wireshark
No real-world, third-party, or unauthorized systems were scanned, probed, or attacked.

---------------------------------------------------------
List of Targets Tested
---------------------------------------------------------
1. Metasploitable2 VM  
   - IP: <Metasploitable_IP>  
   - Purpose: Vulnerability scanning, password hash extraction, service enumeration.


   - Purpose: Web content discovery, OSINT-style info gathering.

2. Local Kali Interfaces   
   - Purpose: Packet capture testing using Wireshark and tcpdump.

---------------------------------------------------------
Tools & Tests Performed
---------------------------------------------------------

1. **OSINT & Footprinting – theHarvester**  
   - Used to gather publicly available information on authorized lab domains.

2. **Web Content Discovery – dirb / gobuster**  
 
   - Only local VMs were used.

3. **Host & Service Enumeration – nmap**  
   - Identified open ports and running services on Metasploitable2 and DVWA.  
   - Full TCP/UDP scans performed only on authorized machines.

4. **TLS/SSL Analysis – sslyze / sslscan**  
   - Tested HTTPS endpoints for security configuration issues.  
   - Only lab-hosted web services analyzed.

5. **Password Cracking – hashcat**  
   - Cracked local/authorized password hashes extracted from Metasploitable2.  
   - Wordlist used: rockyou.txt.  
   - Output saved to: hashcat_cracked_22i-2291_Rehman.txt

6. **Packet Capture & Analysis – Wireshark**  
   - Captured traffic between Kali and local target machines.  
   - Focused on plaintext credentials, insecure protocols, and network behavior.  
   - PCAP file: pcap_22i-2291_Rehman.pcap

---------------------------------------------------------
End of README
---------------------------------------------------------
