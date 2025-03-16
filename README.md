# ctf-writeups

This repository contains detailed reports and solutions for various  Capture The Flag (CTF) challenges I have participated in. Each report  outlines the challenges, tools used, methodologies, and solutions, along with personal reflections and risk assessments.

## Table of Contents

- About CTF Writeups
- CTF Reports
  - CTF 1 - Conducted by Team222
  - CTF 2 - Conducted by Team222
- Future CTF Writeups
- Tools Used

## About CTF Writeups

Capture The Flag (CTF) challenges are  cybersecurity competitions where participants are tasked with solving a series of security-related tasks to find "flags" hidden in systems, applications, or networks. These writeups document my journey through various CTF  challenges, highlighting the techniques, tools, and methodologies involved in solving them.

## CTF Reports

Below are the CTF writeups included in this  repository. Each report provides an overview of the challenges,  solutions, and key takeaways.

### CTF 1 - Conducted by Team222

- **Date**: April 21, 2024
- **Team Members**: Mohnish Sharma, Tam Tin (Ambrose) Tang, Micheal Zanbaka, Santosh Aryal
- **Flags Captured**: 3 out of 5
- **Challenges**:
  - **Yellow Pages**: Explored base32 encoding and NIS-related vulnerabilities.
  - **Smoke Signals**: Investigated Linux pipes and signals (unsolved).
  - **Attribution**: Extracted metadata from files using extended attributes.
  - **Call of Cthulhu**: Analysed background processes in Linux to find hidden flags.
  - **Othello**: Attempted to bypass login restrictions (unsolved).

[View Full Report](https://github.com/mohnish-sharma/ctf-writeups/blob/main/CTF%201.pdf)

------

### CTF 2 - Conducted by Team222

- **Date**: May 12, 2024
- **Team Members**: Mohnish Sharma, Tam Tin (Ambrose) Tang, Micheal Zanbaka, Santosh Aryal
- **Flags Captured**: 4 out of 5
- **Challenges**:
  - **Find Me!**: Explored directory traversal and broken access control.
  - **Nom nom**: Decoded browser cookies to retrieve the flag.
  - **Fuel Injection**: Exploited SQL injection vulnerabilities using `sqlmap`.
  - **Toolkit**: Brute-forced a login page (using `hydra`) and extracted metadata from an image.
  - **What Lies Beneath**: Investigated HTML injection and hidden directories (unsolved).

[View Full Report](https://github.com/mohnish-sharma/ctf-writeups/blob/main/CTF%202.pdf)

### Future CTF Writeups

This section will be updated with  additional CTF writeups as I participate in more challenges. Stay tuned  for more insights and solutions!



## Tools Used

- **[Apache Guacamole](https://guacamole.apache.org/)**: For remote access to virtual environments.
- **[Firefox Developer Tools](https://firefox-source-docs.mozilla.org/devtools-user/)**: For inspecting web pages and analysing network traffic.
- **[Gobuster](https://www.kali.org/tools/gobuster/)**: For directory and file brute-forcing.
- **[SQLMap](https://sqlmap.org/)**: For detecting and exploiting SQL injection vulnerabilities.
- **[Hydra](https://www.kali.org/tools/hydra/)**: For brute-forcing login pages.
- **[CyberChef](https://gchq.github.io/CyberChef/)**: For encoding, decoding, and data manipulation.
- **[Telnet](https://linux.die.net/man/1/telnet)**: For connecting to remote servers in CTF 1.