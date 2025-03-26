# Performing-Penetration-Testing
Scenario
In this lab, you will learn about some aspects of penetration testing.

As a security team member of Structureality Inc, you are working to improve your organization's security stance. Part of that process is understanding the vulnerabilities, weaknesses, and exploitation points present in the organization's IT infrastructure. One common technique to discover those issues is through penetration testing. There are several phases of penetration testing: reconnaissance, scanning, vulnerability detection, gaining access, and post-exploit activities.

If you have worked through all of the labs before this one, then you have already performed tasks common to many of these phases:

Reconnaissance phase: Assisted Lab - Performing reconnaissance
Scanning phase: Assisted Lab - Finding open service ports
Vulnerability detection phase: Assisted Lab - Performing vulnerability scans
Gaining access phase: Assisted Lab - Exploiting and detecting SQLi, Assisted Lab - Understanding On-Path Attacks
During the post-exploit activities phase, a penetration tester may perform privilege escalation, establish persistence, simulate data exfiltration, plant remote control tools, alter security configurations, perform additional data mining, destroy evidence, and even plant misleading evidence. However, these activities are not covered in Security+ labs. If you are interested in penetration testing, consider the CompTIA PenTest+ training, labs, and certification.

This lab focuses on activities that could be performed during the gaining access phase. A penetration tester can use a never-ending collection of potential attacks and exploitations to stress test their client's environment.

In this lab, you will perform directory traversal, command injection, file upload exploitation, and injecting a web shell.

Understand your environment
You will be working from a virtual machine named KALI, hosting Kali Linux, and a virtual machine named LAMP, hosting Ubuntu Server and supporting a vulnerable website
