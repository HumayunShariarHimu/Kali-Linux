# Kali-Linux

> A curated and organized collection of resources related to **Kali-Linux**.

**Maintained by [Humayun Shariar Himu](https://github.com/HumayunShariarHimu)**

# Kali Linux Tools Documentation

![YouTube Channel Subscribers](https://img.shields.io/youtube/channel/subscribers/UClhKVCHjOxBTNM50lOBTgoA)
![Discord](https://img.shields.io/discord/1163365511309049948)

# Contact With Me:

    <img src="https://img.shields.io/static/v1?message=Youtube&logo=youtube&label=&color=FF0000&logoColor=white&labelColor=&style=for-the-badge" height="27" alt="youtube logo"  />
  </a>
    <img src="https://img.shields.io/static/v1?message=Instagram&logo=instagram&label=&color=E4405F&logoColor=white&labelColor=&style=for-the-badge" height="27" alt="instagram logo"  />
  </a>
    <img src="https://img.shields.io/static/v1?message=Twitch&logo=twitch&label=&color=9146FF&logoColor=white&labelColor=&style=for-the-badge" height="27" alt="twitch logo"  />
  </a>
    <img src="https://img.shields.io/static/v1?message=Proton%20Mail&logo=protonmail&label=&color=7341FF&logoColor=white&labelColor=&style=for-the-badge" height="27" alt="proton mail logo"  />
  </a>
    <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="27" alt="linkedin logo"  />
  </a>
    <img src="https://img.shields.io/static/v1?message=Twitter&logo=twitter&label=&color=1DA1F2&logoColor=white&labelColor=&style=for-the-badge" height="27" alt="twitter logo"  />
  </a>

# 💰 You can help me by Donating
  

**A guide to using Kali Linux tools for web penetration testing, ethical hacking, forensics, and bug bounty. Covers setup, key tools, methodologies, and best practices. Optimized for security professionals.**

> [!Note]
> This project is intended for educational and ethical purposes only. Unauthorized use, distribution, or modification of these tools without proper consent is prohibited. By using this repository, you agree to comply with all applicable laws and ethical guidelines. The author is not responsible for any misuse or damage caused by the tools provided herein.

## 1. Information Gathering

This phase involves collecting as much data as possible about a target system or network.

### 1.1. DNS Analysis
Tools for enumerating DNS records and identifying subdomains.

- [**gobuster**](https://github.com/OJ/gobuster): A multi-purpose tool for brute-forcing URIs (directories and files), DNS subdomains, and virtual host names.
- [**shuffledns**](https://github.com/projectdiscovery/shuffledns): A wrapper around massdns that enumerates subdomains using a wordlist and various resolvers.

### 1.2. OSINT Analysis
Open-Source Intelligence (OSINT) tools for gathering information from publicly available sources.

### 1.3. Live Host & Route Analysis
Tools for identifying live systems on a network and analyzing network paths.

- [**httprobe**](https://github.com/tomnomnom/httprobe): A tool to probe for working HTTP and HTTPS servers from a list of hosts.
- [**naabu**](https://github.com/projectdiscovery/naabu): A fast port scanner written in Go that focuses on accuracy and simplicity.

### 1.4. Service & Protocol Analysis
Specialized tools for enumerating and analyzing specific network services.

### 1.5. SSL/TLS Analysis
Tools for auditing and analyzing SSL/TLS configurations and certificates.

### 1.6. IDS/IPS Identification
Tools for detecting the presence of intrusion detection and prevention systems.

### 1.7. General & Auxiliary Tools

## 2. Vulnerability Analysis

Tools for identifying security weaknesses and potential vulnerabilities in systems and applications.

- [**legion**](https://github.com/carlospolop/legion): An automated, semi-automated, and fully automated network penetration testing framework, aiding in discovery and vulnerability scanning.
- [**vuls**](https://github.com/future-architect/vuls): A vulnerability scanner for Linux and FreeBSD, written in Go, with agentless architecture.
- [**clamav**](https://www.clamav.net/): An open-source antivirus engine for detecting trojans, viruses, malware, and other malicious threats.
- [**openvas**](https://www.greenbone.net/en/): A full-featured vulnerability scanner that includes a comprehensive set of network vulnerability tests.

## 3. Web Application Analysis

This section focuses on tools for assessing and attacking web applications.

### 3.1. Directory & File Discovery
- [**gobuster**](https://github.com/OJ/gobuster): A multi-purpose brute-force tool for finding hidden directories, files, DNS subdomains, and virtual hosts.
- [**feroxbuster**](https://github.com/epi052/feroxbuster): A fast, simple, and recursive content discovery tool written in Rust.
- [**kiterunner**](https://github.com/assetnote/kiterunner): A contextual content discovery tool that uses common API paths and file extensions.

### 3.2. Content & Technology Identification

### 3.3. Vulnerability Scanning & Exploitation
- [**jwt_tool**](https://github.com/ticarpi/jwt_tool): A toolkit for testing, attacking, and debugging JSON Web Tokens.
- [**corsy**](https://github.com/s0md3v/Corsy): A CORS misconfiguration scanner that identifies insecure cross-origin resource sharing policies.
- [**graphqlmap**](https://github.com/swisskyrepo/GraphQLmap): A scripting engine to interact with a GraphQL endpoint for security testing purposes.

### 3.4. WebDAV Analysis

### 3.5. Post-Exploitation & Backdoors

## 4. Password Attacks

Tools for auditing password security through various attack vectors.

### 4.1. Online Attacks
- [**patator**](https://github.com/lanjelot/patator): A multi-purpose brute-forcing tool with a modular design for various protocols and services.
- [**crowbar**](https://github.com/galkan/crowbar): A brute-forcing tool that supports OpenVPN, RDP, SSH, and VNC protocols with a focus on reliability.
- [**keimpx**](https://github.com/inquisb/keimpx): A tool to check valid credentials across a network via SMB, RDP, and HTTP.

### 4.2. Offline Attacks

### 4.3. Wordlist Generation & Profiling
- [**seclists**](https://github.com/danielmiessler/SecLists): A comprehensive collection of multiple types of lists used during security assessments, including usernames, passwords, URLs, and fuzzing payloads.
- [**probable-wordlists**](https://github.com/berzerk0/Probable-Wordlists): A collection of curated and sorted password dictionaries based on real-world data.

### 4.4. "Passing the Hash" & Lateral Movement
- [**sprayhound**](https://github.com/Hackndo/sprayhound): A password spraying tool integrated with BloodHound for Active Directory reconnaissance.

## 5. Wireless Attacks

This category covers tools for auditing and attacking wireless networks.

- [**mdk4**](https://github.com/aircrack-ng/mdk4): A proof-of-concept tool to exploit common IEEE 802.11 protocol weaknesses.
- [**horst**](https://github.com/br101/horst): A wireless network analysis tool that works as a spectrum analyzer and packet sniffer.

## 6. Sniffing & Spoofing

These tools are used to intercept, manipulate, and analyze network traffic.

## 7. Exploitation Tools

Tools for developing, executing, and managing exploits against vulnerable targets.

- [**msfpc**](https://github.com/g0tmi1k/msfpc): The Metasploit Payload Creator, a quick way to generate various Meterpreter reverse shells.

## 8. Post-Exploitation & Tunneling

Tools used after initial access to maintain persistence, move laterally, and exfiltrate data.

- [**exe2hex**](https://github.com/g0tmi1k/exe2hex): A tool for converting executable files into a hexadecimal representation that can be pasted into a shell.
- [**empire**](https://github.com/BC-SECURITY/Empire): A post-exploitation framework that uses PowerShell agents without powershell.exe.
- [**pwncat**](https://github.com/calebstewart/pwncat): A netcat-like tool with advanced features like auto-completion and scriptable interaction.
- [**chisel**](https://github.com/jpillora/chisel): A fast TCP tunnel over HTTP, useful for tunneling through firewalls.
- [**ligolo-ng**](https://github.com/nicocha30/ligolo-ng): An advanced tunneling tool that creates a network tunnel from a reverse connection.

## 9. Reverse Engineering

Tools for analyzing and understanding the inner workings of software binaries.

- **clang++**: The C++ compiler front end of the Clang project.
- [**ghidra**](https://github.com/NationalSecurityAgency/ghidra): A software reverse engineering (SRE) suite of tools developed by the NSA, supporting a wide range of processors and executables.
- [**gdb**](https://www.sourceware.org/gdb/): The GNU Project debugger, allowing you to see what is going on 'inside' a program while it executes.
- [**ida-free**](https://hex-rays.com/ida-free/): The freeware version of IDA Pro, a powerful disassembler and debugger.
- [**x64dbg**](https://github.com/x64dbg/x64dbg): An open-source Windows debugger for 64-bit applications.
- [**ollydbg**](http://www.ollydbg.de/): A 32-bit assembler-level debugger for Windows with a focus on binary code analysis.
- [**cutter**](https://github.com/rizinorg/cutter): A GUI for radare2, making reverse engineering more accessible.
- [**angr**](https://github.com/angr/angr): A platform-agnostic binary analysis framework developed at UCSB's Seclab.

## 10. Forensics

Tools for investigating, analyzing, and recovering data from digital media.

- [**dcfldd**](https://github.com/resurrecting-open-source-projects/dcfldd): An enhanced version of dd with features useful for forensics and security.
- [**regripper**](https://github.com/keydet89/RegRipper3.0): A tool for extracting and analyzing Windows registry data.
- [**xplico**](https://github.com/xplico/xplico): A network forensics analysis tool that reconstructs the contents of captured data.

## 11. Mobile Security

Tools for analyzing and testing mobile applications and devices.

- [**dex2jar**](https://github.com/pxb1988/dex2jar): A tool to convert Android .dex files to .class files (JAR format).
- [**androguard**](https://github.com/androguard/androguard): A full Python tool for reverse engineering Android applications.
- [**adb**](https://developer.android.com/studio/command-line/adb): The Android Debug Bridge, a versatile command-line tool for communicating with Android devices.

## 12. Cloud Security

Tools for auditing and securing cloud infrastructure.

- [**cloudsploit**](https://github.com/aquasecurity/cloudsploit): A cloud security scanning tool for AWS, Azure, and Google Cloud.
- [**cloudsplaining**](https://github.com/salesforce/cloudsplaining): An AWS IAM security assessment tool that identifies violations of least privilege.
- [**falco**](https://github.com/falcosecurity/falco): A cloud-native runtime security project for Kubernetes and container environments.

## 13. Container Security

Specialized tools for container security assessment.

- [**grype**](https://github.com/anchore/grype): A vulnerability scanner for container images and filesystems.
- [**dockle**](https://github.com/goodwithtech/dockle): A container image linter for security, helping to identify best practice violations.
- [**kubeaudit**](https://github.com/Shopify/kubeaudit): A command-line tool to audit Kubernetes clusters for security issues.
- [**kubesec**](https://github.com/controlplaneio/kubesec): A security risk analysis tool for Kubernetes resources.

## 14. Physical Security/Hardware Hacking

Tools for testing physical security devices and hardware.

- [**wifipumpkin3**](https://github.com/P0cL4bs/wifipumpkin3): A powerful framework for creating rogue access points and MITM attacks.
- [**fluxion**](https://github.com/FluxionNetwork/fluxion): A tool for creating evil twin attacks to capture WPA handshakes.
- [**wifiphisher**](https://github.com/wifiphisher/wifiphisher): A rogue Access Point framework for conducting red team engagements.
- [**proxmark3**](https://github.com/Proxmark/proxmark3): A RFID/NFC cloning and analysis tool.
- [**hcitool**](http://www.bluez.org/): A Bluetooth testing tool included in the BlueZ package.
- [**ubertooth**](https://github.com/greatscottgadgets/ubertooth): An open-source 2.4 GHz wireless development platform for Bluetooth experimentation.

## 15. Steganography

Tools for hiding and discovering hidden data within files.

- [**steghide**](https://github.com/StefanoDeVuono/steghide): A steganography program that hides data in various image and audio files.
- [**zsteg**](https://github.com/zed-0xff/zsteg): A tool for detecting steganography in PNG and BMP files.
- [**stegsolve**](https://github.com/zardus/ctf-tools/tree/master/stegsolve): A tool for solving steganography challenges by applying various transformations.
- [**outguess**](https://github.com/crorvick/outguess): A steganography tool for hiding data in the redundant bits of data sources.
- [**stegdetect**](https://github.com/abeluck/stegdetect): An automated tool for detecting steganographic content in image files.

## 16. Anonymity & Privacy

Tools for maintaining anonymity during security assessments.

- [**torbrowser-launcher**](https://github.com/micahflee/torbrowser-launcher): A tool to download and launch the Tor Browser Bundle.
- [**torsocks**](https://github.com/dgoulet/torsocks): A wrapper to safely torify applications.
- [**nyx**](https://github.com/torproject/nyx): A command-line monitor for the Tor status and bandwidth usage.
- [**onionprobe**](https://github.com/athoune/onionprobe): A tool for monitoring the status of Onion services.
- [**anonsurf**](https://github.com/Und3rf10w/kali-anonsurf): A tool for anonymizing the entire system by routing traffic through Tor.

## 17. Reporting Tools

Tools to assist in documenting findings and creating professional penetration test reports.

- [**dradis**](https://github.com/dradis/dradis-ce): A collaboration and reporting platform for security assessments.
- [**faraday**](https://github.com/infobyte/faraday): An integrated pentest environment that helps with collaboration and reporting.
- [**serpico**](https://github.com/SerpicoProject/Serpico): A penetration testing collaboration and reporting tool.

## 18. Social Engineering

Tools focused on human interaction and deception to gain access.

- [**msfpc**](https://github.com/g0tmi1k/msfpc): (Also in Exploitation Tools) The Metasploit Payload Creator, used to generate payloads for social engineering campaigns.
- [**gophish**](https://github.com/gophish/gophish): An open-source phishing framework that makes it easy to launch and track phishing campaigns.
- [**kingphisher**](https://github.com/securestate/king-phisher): A tool for creating and managing multiple simultaneous phishing attacks.
- [**evilginx2**](https://github.com/kgretzky/evilginx2): A man-in-the-middle attack framework for phishing credentials and session cookies with 2FA bypass.
- [**modlishka**](https://github.com/drk1wi/Modlishka): A flexible and powerful reverse proxy for phishing campaigns.
- [**hiddeneye**](https://github.com/DarkSecDevelopers/HiddenEye): A phishing tool with modern techniques and security bypass methods.
- [**blackeye**](https://github.com/An0nUD4Y/blackeye): A phishing toolkit with many website templates.

## 19. Custom Wordlists & Dictionaries

Comprehensive collections for password attacks and content discovery.

- [**seclists**](https://github.com/danielmiessler/SecLists): The most comprehensive collection of wordlists for security assessments.
- [**probable-wordlists**](https://github.com/berzerk0/Probable-Wordlists): A collection of curated and sorted password dictionaries based on real-world data.
- [**fuzzdb**](https://github.com/fuzzdb-project/fuzzdb): A dictionary of attack patterns and discovery wordlists for fuzzing.
- [**rockyou**](https://github.com/brannondorsey/naive-hashcat/releases/download/data/rockyou.txt): The famous RockYou password wordlist from the 2009 data breach.
- [**assetnote-wordlists**](https://github.com/assetnote/wordlists): A collection of wordlists for content discovery and subdomain enumeration.

---

## 📖 More Guides & Resources

<p align="center">
</p>

---
