# Cyber-Portfolio


Week 10 – SOC Lab Deployment, Network Reconnaissance & Log Analysis
This week marked a major transition from environment setup into practical cybersecurity operations. I successfully built and utilized a functional home SOC lab integrating both offensive and defensive tools.

On the offensive side, I used Kali Linux to perform internal reconnaissance using Nmap. The scan confirmed host availability within the lab network and provided insight into basic network behavior.

To analyze network-level activity, I used Wireshark to capture live traffic during scanning. Using filters such as ARP, I was able to observe device communication and understand how systems discover and interact with each other on the network.

On the defensive side, I configured Splunk to ingest Windows Event Logs from the host machine. I verified log ingestion by querying Application and Security logs, gaining visibility into system activity and event generation.

To further test detection capability, I generated user and system activity (application launches and interactions) and analyzed corresponding logs in Splunk. This introduced the concept of correlating actions with logged events.

Key achievements this week:

Successfully deployed and operated a Kali Linux attacker environment
Performed network reconnaissance using Nmap
Captured and analyzed network traffic using Wireshark
Configured Splunk SIEM to ingest Windows Event Logs
Queried and investigated system activity through log analysis
Next Week Plan
Improve log visibility (enable and troubleshoot missing System logs)
Generate and detect specific security events (e.g., failed logins)
Begin structured threat detection use cases in Splunk
Enhance documentation and publish first cybersecurity project on GitHub
###Screenshots

Kali environment01-Kali-running png<img width="1916" height="1037" alt="Screenshot 2026-04-27 124204" src="https://github.com/user-attachments/assets/902bfce9-1a89-478f-8f1c-fe2b16e95050" />


Nmap reconnaissance04-nmap-scan png<img width="757" height="553" alt="photo_5769402309019373270_x" src="https://github.com/user-attachments/assets/4b3a5e5e-4c63-459b-8426-c7a9e1042f3a" />


Wireshark network traffic03-Wireshark-capture png<img width="1918" height="971" alt="Screenshot 2026-04-22 123222" src="https://github.com/user-attachments/assets/ce6b2657-e69e-4583-b42f-a0fed18d9848" />


Working Splunk02-Splunk-dashboard png<img width="1129" height="802" alt="Screenshot 2026-04-22 125404" src="https://github.com/user-attachments/assets/d0bd0d55-6ae7-45f2-8ce0-16078e579a77" />


Key Takeaway
Cybersecurity is not just about running tools, but about understanding and connecting attacker activity, network behavior, and system logs. This week established the foundation for real-world detection and analysis workflows.
