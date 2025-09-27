Cybersecurity Live Project – The Tech Academy

This repository documents my work during the Cyber Security Boot Camp’s live project. The project simulated real-world environments where I applied industry-standard tools and methodologies to analyze malicious traffic, exploit vulnerable applications, and produce professional incident reports.

Objectives

Build and manage secure virtual environments for testing.

Perform penetration testing on intentionally vulnerable applications.

Analyze malicious network traffic and identify indicators of compromise.

Develop professional documentation of findings in standardized reports.

Tools & Technologies

Virtualization: VirtualBox (Kali Linux guest OS)

Containerization: Docker (OWASP Juice Shop deployment)

Network & Traffic Analysis: Wireshark, TShark

Web Application Security Testing: Burp Suite, browser DevTools

Forensic & Reporting: Standardized incident report templates

Key Tasks & Examples
1. Environment Setup

Installed and configured Kali Linux in VirtualBox, resolving BIOS virtualization issues.

Deployed OWASP Juice Shop with Docker, setting up a controlled environment for penetration testing.

2. Web Application Security Testing

Intercepted and manipulated HTTP requests with Burp Suite to:

Gain unauthorized access to another user’s shopping basket.

Perform a 0-star review injection attack.

Execute a brute-force attack on the admin login using the best1050.txt wordlist, successfully resetting the admin password.

Exploit hidden files via null byte injection to retrieve sensitive JSON documents.

3. Network Traffic & Malware Analysis

Analyzed provided PCAP files using Wireshark and TShark to:

Identify the infected host (192.168.138.158) communicating with suspicious external domains.

Trace malware beaconing activity and unauthorized data exfiltration.

Extract forensic details such as IP addresses, malicious domains, and timestamps of compromise.

Documented findings in structured incident reports for instructor review.

Reporting & Deliverables

Created professional Incident Reports with the following format:

Executive Summary: Overview of the incident and results.

Methodology: Steps taken, tools used, filters applied.

Observations: Indicators of compromise, artifacts, attacker behavior.

Conclusion: Lessons learned and recommendations.

Submitted reports with supporting screenshots and evidence to instructors.

Skills Strengthened

Virtualization & container management.

Penetration testing and vulnerability exploitation.

Malware and traffic forensics.

Professional technical documentation and communication.

Problem-solving in real-world, adversarial scenarios.
