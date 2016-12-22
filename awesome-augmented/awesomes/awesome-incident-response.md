<h1>
 awesome-incident-response
</h1>
<p>
 A curated list of tools and resources for security incident response, aimed to help security analysts and
 <a href="http://www.acronymfinder.com/Digital-Forensics%2c-Incident-Response-(DFIR).html">
  DFIR
 </a>
 teams.
</p>
<p>
 <a href="https://github.com/sindresorhus/awesome">
  <img alt="Awesome" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg"/>
 </a>
</p>
<ul>
 <li>
  <a href="#disk-image-creation-tools">
   Disk Image Creation Tools
  </a>
 </li>
 <li>
  <a href="#memory-analysis-tools">
   Memory Analysis Tools
  </a>
 </li>
 <li>
  <a href="#memory-imaging-tools">
   Memory Imaging Tools
  </a>
 </li>
 <li>
  <a href="#process-dump-tools">
   Process Dump Tools
  </a>
 </li>
 <li>
  <a href="#timeline-tools">
   Timeline tools
  </a>
 </li>
 <li>
  <a href="#log-analysis-tools">
   Log Analysis Tools
  </a>
 </li>
 <li>
  <a href="#all-in-one-tools">
   All in one tools
  </a>
 </li>
 <li>
  <a href="#incident-management">
   Incident Management
  </a>
 </li>
 <li>
  <a href="#evidence-collection">
   Evidence Collection
  </a>
 </li>
 <li>
  <a href="#windows-evidence-collection">
   Windows Evidence Collection
  </a>
 </li>
 <li>
  <a href="#osx-evidence-collection">
   OSX Evidence Collection
  </a>
 </li>
 <li>
  <a href="#linux-evidence-collection">
   Linux Evidence Collection
  </a>
 </li>
 <li>
  <a href="#sandboxingreversing-tools">
   Sandboxing/reversing tools
  </a>
 </li>
 <li>
  <a href="#linux-distributions">
   Linux Distributions
  </a>
 </li>
 <li>
  <a href="#other-tools">
   Other tools
  </a>
 </li>
 <li>
  <a href="#videos">
   Videos
  </a>
 </li>
 <li>
  <a href="#books">
   Books
  </a>
 </li>
 <li>
  <a href="#playbooks">
   Playbooks
  </a>
 </li>
 <li>
  <a href="#communities">
   Communities
  </a>
 </li>
</ul>
<h2>
 IR tools Collection
</h2>
<h3>
 Disk Image Creation Tools
</h3>
<ul>
 <li>
  <a href="http://www.forensicimager.com/">
   GetData Forensic Imager
  </a>
  - GetData Forensic Imager is a Windows based program that will acquire, convert, or verify a forensic image in one of the following common forensic file formats
 </li>
 <li>
  <a href="http://guymager.sourceforge.net">
   Guymager
  </a>
  - Guymager is a free forensic imager for media acquisition on Linux
 </li>
 <li>
  <a href="http://accessdata.com/product-download/?/support/adownloads#FTKImager">
   AccessData FTK Imager
  </a>
  - AccessData FTK Imager is a forensics tool whose main purpose is to preview recoverable data from a disk of any kind. FTK Imager can also acquire live memory and paging file on 32bit and 64bit systems
 </li>
</ul>
<h3>
 Memory Analysis Tools
</h3>
<ul>
 <li>
  <a href="https://github.com/volatilityfoundation/volatility">
   Volatility
  </a>
  - An advanced memory forensics framework
  <sup>
   &#9733 950, pushed 4 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/JamesHabben/evolve">
   Evolve
  </a>
  - Web interface for the Volatility Memory Forensics Framework
  <sup>
   &#9733 137, pushed 79 days ago
  </sup>
 </li>
 <li>
  <a href="http://www.windowsscope.com/index.php?page=shop.product_details&flypage=flypage.tpl&product_id=35&category_id=3&option=com_virtuemart">
   WindowsSCOPE
  </a>
  - another memory forensics and reverse engineering tool used for analyzing volatile memory. It is basically used for reverse engineering of malwares. It provides the capability of analyzing the Windows kernel, drivers, DLLs, virtual and physical memory
 </li>
 <li>
  <a href="http://www.countertack.com/responder-pro">
   Responder PRO
  </a>
  - Responder PRO is the industry standard physical memory and automated malware analysis solution
 </li>
 <li>
  <a href="http://www.gmgsystemsinc.com/knttools/">
   KnTList
  </a>
  - Computer memory analysis tools
 </li>
 <li>
  <a href="http://www.rekall-forensic.com/">
   Rekall
  </a>
  - Open source tool (and library) for the extraction of digital artifacts from volatile memory (RAM) samples
 </li>
 <li>
  <a href="https://www.fireeye.com/services/freeware/memoryze.html">
   Memoryze
  </a>
  - Memoryze by Mandiant is a free memory forensic software that helps incident responders find evil in live memory. Memoryze can acquire and/or analyze memory images, and on live systems, can include the paging file in its analysis
 </li>
 <li>
  <a href="https://www.fireeye.com/services/freeware/memoryze-for-the-mac.html">
   Memoryze for Mac
  </a>
  - Memoryze for Mac is Memoryze but then for Macs. A lower number of features, however
 </li>
</ul>
<h3>
 Memory Imaging Tools
</h3>
<ul>
 <li>
  <a href="http://www.osforensics.com/">
   OSForensics
  </a>
  - OSForensics can acquire live memory on 32bit and 64bit systems. A dump of an individual process’s memory space or physical memory dump can be done
 </li>
 <li>
  <a href="http://belkasoft.com/ram-capturer">
   Belkasoft Live RAM Capturer
  </a>
  - A tiny free forensic tool to reliably extract the entire content of the computer’s volatile memory – even if protected by an active anti-debugging or anti-dumping system
 </li>
</ul>
<h3>
 Process Dump Tools
</h3>
<ul>
 <li>
  <a href="http://www.ntsecurity.nu/toolbox/pmdump/">
   PMDump
  </a>
  - PMDump is a tool that lets you dump the memory contents of a process to a file without stopping the process
 </li>
 <li>
  <a href="http://www.microsoft.com/en-us/download/details.aspx?id=4060">
   Microsoft User Mode Process Dumper
  </a>
  - The User Mode Process Dumper (userdump) dumps any running Win32 processes memory image on the fly
 </li>
</ul>
<h3>
 Timeline tools
</h3>
<ul>
 <li>
  <a href="https://github.com/log2timeline/plaso">
   Plaso
  </a>
  -  a Python-based backend engine for the tool log2timeline
  <sup>
   &#9733 184, pushed 2 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/google/timesketch">
   Timesketch
  </a>
  - open source tool for collaborative forensic timeline analysis
  <sup>
   &#9733 320, pushed 43 days ago
  </sup>
 </li>
 <li>
  <a href="https://www.fireeye.com/services/freeware/highlighter.html">
   Highlighter
  </a>
  - Free Tool available from Fire/Mandiant that will depict log/text file that can highlight areas on the graphic, that corresponded to a key word or phrase. Good for time lining an infection and what was done post compromise
 </li>
</ul>
<h3>
 Log Analysis Tools
</h3>
<ul>
 <li>
  <a href="https://github.com/jensvoid/lorg">
   Lorg
  </a>
  - a tool for advanced HTTPD logfile security analysis and forensics
  <sup>
   &#9733 63, pushed 141 days ago
  </sup>
 </li>
</ul>
<h3>
 All in one Tools
</h3>
<ul>
 <li>
  <a href="http://www.x-ways.net/forensics/">
   X-Ways Forensics
  </a>
  - X-Ways is a forensics tool for Disk cloning and imaging. It can be used to find deleted files and disk analysis
 </li>
 <li>
  <a href="http://www.sleuthkit.org">
   The Sleuth Kit & Autopsy
  </a>
  - The Sleuth Kit is a Unix and Windows based tool which helps in forensic analysis of computers. It comes with various tools which helps in digital forensics. These tools help in analyzing disk images, performing in-depth analysis of file systems, and various other things
 </li>
 <li>
  <a href="http://sourceforge.net/projects/ocfa/">
   Open Computer Forensics Architecture
  </a>
  - Open Computer Forensics Architecture (OCFA) is another popular distributed open-source computer forensics framework. This framework was built on Linux platform and uses postgreSQL database for storing data
 </li>
 <li>
  <a href="http://www.arxsys.fr/discover/">
   Digital Forensics Framework
  </a>
  - DFF is an Open Source computer forensics platform built on top of a dedicated Application Programming Interface (API). DFF proposes an alternative to the aging digital forensics solutions used today. Designed for simple use and automation, the DFF interface guides the user through the main steps of a digital investigation so it can be used by both professional and non-expert to quickly and easily conduct a digital investigations and perform incident response
 </li>
 <li>
  <a href="https://osquery.io/">
   Osquery
  </a>
  - with osquery you can easily ask questions about your Linux and OSX infrastructure. Whether your goal is intrusion detection, infrastructure reliability, or compliance, osquery gives you the ability to empower and inform a broad set of organizations within your company. Queries in the
  <em>
   incident-response pack
  </em>
  help you detect and respond to breaches
 </li>
 <li>
  <a href="https://github.com/mozilla/MozDef">
   MozDef
  </a>
  - The Mozilla Defense Platform (MozDef) seeks to automate the security incident handling process and facilitate the real-time activities of incident handlers
  <sup>
   &#9733 1020, pushed 15 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/google/grr">
   GRR Rapid Response
  </a>
  - GRR Rapid Response is an incident response framework focused on remote live forensics. It consists of a python agent (client) that is installed on target systems, and a python server infrastructure that can manage and talk to the agent
  <sup>
   &#9733 1180, pushed 11 days ago
  </sup>
 </li>
 <li>
  <a href="http://mig.mozilla.org/">
   MIG
  </a>
  - Mozilla Investigator (MIG) is a platform to perform investigative surgery on remote endpoints. It enables investigators to obtain information from large numbers of systems in parallel, thus accelerating investigation of incidents and day-to-day operations security
 </li>
 <li>
  <a href="https://github.com/Netflix/Fido">
   FIDO
  </a>
  - Fully Integrated Defense Operation (FIDO) by Netflix is an orchestration layer used to automate the incident response process by evaluating, assessing and responding to malware. FIDO’s primary purpose is to handle the heavy manual effort needed to evaluate threats coming from today's security stack and the large number of alerts generated by them
  <sup>
   &#9733 636, pushed 21 days ago
  </sup>
 </li>
 <li>
  <a href="https://www.fireeye.com/services/freeware/redline.html">
   Redline
  </a>
  - provides host investigative capabilities to users to find signs of malicious activity through memory and file analysis, and the development of a threat assessment profile
 </li>
 <li>
  <a href="https://github.com/mephux/envdb">
   Envdb
  </a>
  - Envdb turns your production, dev, cloud, etc environments into a database cluster you can search using osquery as the foundation. It wraps the osquery process with a (cluster) node agent that can communicate back to a central location
  <sup>
   &#9733 501, pushed 356 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/refractionpoint/limacharlie">
   Limacharlie
  </a>
  - an endpoint security platform. It is itself a collection of small projects all working together, and gives you a cross-platform (Windows, OSX, Linux, Android and iOS) low-level environment allowing you to manage and push additional modules into memory to extend its functionality
  <sup>
   &#9733 82, pushed 2 days ago
  </sup>
 </li>
 <li>
  <a href="https://belkasoft.com/ec">
   Belkasoft Evidence Center
  </a>
  -  The toolkit will quickly extract digital evidence from multiple sources by analyzing hard drives, drive images, memory dumps, iOS, Blackberry and Android backups, UFED, JTAG and chip-off dumps
 </li>
 <li>
  <a href="https://github.com/byt3smith/CIRTKit">
   CIRTkit
  </a>
  - CIRTKit is not just a collection of tools, but also a framework to aid in the ongoing unification of Incident Response and Forensics investigation processes
  <sup>
   &#9733 5, pushed 96 days ago
  </sup>
 </li>
</ul>
<h3>
 Incident Management
</h3>
<ul>
 <li>
  <a href="https://github.com/certsocietegenerale/FIR/">
   FIR
  </a>
  - Fast Incident Response (FIR) is an cybersecurity incident management platform designed with agility and speed in mind. It allows for easy creation, tracking, and reporting of cybersecurity incidents and is useful for CSIRTs, CERTs and SOCs alike
 </li>
 <li>
  <a href="http://getscot.sandia.gov/">
   SCOT
  </a>
  - Sandia Cyber Omni Tracker (SCOT) is an Incident Response collaboration and knowledge capture tool focused on flexibility and ease of use. Our goal is to add value to the incident response process without burdening the user
 </li>
 <li>
  <a href="https://www.bestpractical.com/rtir/">
   RTIR
  </a>
  - Request Tracker for Incident Response (RTIR) is the premier open source incident handling system targeted for computer security teams. We worked with over a dozen CERT and CSIRT teams around the world to help you handle the ever-increasing volume of incident reports. RTIR builds on all the features of Request Tracker
 </li>
 <li>
  <a href="https://github.com/defpoint/threat_note">
   threat_note
  </a>
  - A lightweight investigation notebook that allows security researchers the ability to register and retrieve indicators related to their research
  <sup>
   &#9733 152, pushed 35 days ago
  </sup>
 </li>
</ul>
<h3>
 Evidence Collection
</h3>
<ul>
 <li>
  <a href="https://www.brimorlabs.com/tools/">
   Live Response Collection
  </a>
  - The Live Response collection by BriMor Labs is an automated tool that collects volatile data from Windows, OSX, and *nix based operating systems
 </li>
 <li>
  <a href="https://github.com/simsong/bulk_extractor">
   bulk
   <em>
    extractor
   </em>
  </a>
  - bulk
  <sup>
   &#9733 164, pushed 13 days ago
  </sup>
 </li>
</ul>
extractor is a computer forensics tool that scans a disk image, a file, or a directory of files and extracts useful information without parsing the file system or file system structures. Because of ignoring the file system structure, the program distinguishes itself in terms of speed and thoroughness
<li>
 <a href="https://github.com/rough007/CDQR">
  Cold Disk Quick Response
 </a>
 - uses a streamlined list of parsers to quickly analyze a forenisic image file (dd, E01, .vmdk, etc) and output nine reports
 <sup>
  &#9733 28, pushed 19 days ago
 </sup>
</li>
<h3>
 Windows Evidence Collection
</h3>
<ul>
 <li>
  <a href="https://github.com/jipegit/FECT">
   FECT
  </a>
  - Fast Evidence Collector Toolkit (FECT) is a light incident response toolkit to collect evidences on a suspicious Windows computer. Basically it is intended to be used by non-tech savvy people working with a journeyman Incident Handler
  <sup>
   &#9733 18, pushed 607 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/gfoss/PSRecon/">
   PSRecon
  </a>
  - PSRecon gathers data from a remote Windows host using PowerShell (v2 or later), organizes the data into folders, hashes all extracted data, hashes PowerShell and various system properties, and sends the data off to the security team. The data can be pushed to a share, sent over email, or retained locally
 </li>
 <li>
  <a href="https://github.com/SekoiaLab/Fastir_Collector">
   FastIR Collector
  </a>
  - FastIR Collector is a tool that collects different artefacts on live Windows systems and records the results in csv files. With the analyses of these artefacts, an early compromise can be detected
  <sup>
   &#9733 193, pushed 15 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/OMENScan/AChoir">
   AChoir
  </a>
  - Achoir is a framework/scripting tool to standardize and simplify the process of scripting live acquisition utilities for Windows
  <sup>
   &#9733 38, pushed 45 days ago
  </sup>
 </li>
 <li>
  <a href="https://code.google.com/p/regripper/wiki/RegRipper">
   RegRipper
  </a>
  - Regripper is an open source tool, written in Perl, for extracting/parsing information (keys, values, data) from the Registry and presenting it for analysis
 </li>
 <li>
  <a href="https://www.fireeye.com/services/freeware/ioc-finder.html">
   IOC Finder
  </a>
  - IOC Finder is a free tool from Mandiant for collecting host system data and reporting the presence of Indicators of Compromise (IOCs). Support for Windows only
 </li>
 <li>
  <a href="http://www.crowdstrike.com/community-tools/">
   Crowd Response
  </a>
  - Crowd Response by CrowdStrike is a lightweight Windows console application designed to aid in the gathering of system information for incident response and security engagements. It features numerous modules and output formats
 </li>
 <li>
  <a href="https://github.com/Neo23x0/Loki">
   LOKI
  </a>
  - Loki is a free IR scanner for scanning endpoint with yara rules and other indicators(IOCs)
  <sup>
   &#9733 345, pushed 3 days ago
  </sup>
 </li>
 <li>
  <a href="https://code.google.com/p/triage-ir/">
   TRIAGE-IR
  </a>
  - Triage-IR is a IR collector for Windows
 </li>
 <li>
  <a href="https://github.com/Invoke-IR/PowerForensics">
   PowerForensics
  </a>
  - Live disk forensics platform, using PowerShell
  <sup>
   &#9733 287, pushed 75 days ago
  </sup>
 </li>
 <li>
  <a href="http://binaryforay.blogspot.co.il/p/software.html">
   Binaryforay
  </a>
  - list of free tools for win forensics (http://binaryforay.blogspot.co.il/)
 </li>
</ul>
<h3>
 OSX Evidence Collection
</h3>
<ul>
 <li>
  <a href="https://github.com/jipegit/OSXAuditor">
   OSX Auditor
  </a>
  - OSX Auditor is a free Mac OS X computer forensics tool
  <sup>
   &#9733 2578, pushed 33 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/yelp/osxcollector">
   OSX Collector
  </a>
  - An OSX Auditor offshoot for live response
  <sup>
   &#9733 838, pushed 5 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/synack/knockknock">
   Knockknock
  </a>
  - Displays persistent items(scripts, commands, binaries, etc.) that are set to execute automatically on OSX
  <sup>
   &#9733 563, pushed 77 days ago
  </sup>
 </li>
</ul>
<h3>
 Linux Evidence Collection
</h3>
<ul>
 <li>
  <a href="https://github.com/SekoiaLab/Fastir_Collector_Linux">
   FastIR Collector Linux
  </a>
  - FastIR for Linux collects different artefacts on live Linux and records the results in csv files.
  <sup>
   &#9733 27, pushed 66 days ago
  </sup>
 </li>
</ul>
<h3>
 Sandboxing/reversing tools
</h3>
<ul>
 <li>
  <a href="https://github.com/cuckoobox">
   Cuckoo
  </a>
  - Open Source Highly configurable sandboxing tool
 </li>
 <li>
  <a href="https://github.com/spender-sandbox/cuckoo-modified">
   Cuckoo-modified
  </a>
  - Heavily modified Cuckoo fork developed by community
  <sup>
   &#9733 91, pushed 4 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/KoreLogicSecurity/mastiff">
   Mastiff
  </a>
  - MASTIFF is a static analysis framework that automates the process of extracting key characteristics from a number of different file formats.
  <sup>
   &#9733 56, pushed 92 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/viper-framework/viper">
   Viper
  </a>
  - Viper is a python based binary analysis and management framework, that works well with Cuckoo and YARA.
  <sup>
   &#9733 713, pushed 4 days ago
  </sup>
 </li>
 <li>
  <a href="https://www.virustotal.com">
   Virustotal
  </a>
  - Virustotal, a subsidiary of Google, is a free online service that analyzes files and URLs enabling the identification of viruses, worms, trojans and other kinds of malicious content detected by antivirus engines and website scanners
 </li>
 <li>
  <a href="https://malwr.com">
   Malwr
  </a>
  - Malwr is a free online malware analysis service and community, which is powered by the Cuckoo Sandbox
 </li>
 <li>
  <a href="https://www.hybrid-analysis.com/">
   Hybrid-Analysis
  </a>
  - Hybrid-Analysis is a free powerful online sandbox by Payload Security
 </li>
</ul>
<h3>
 Linux Distributions
</h3>
<ul>
 <li>
  <a href="https://github.com/Security-Onion-Solutions/security-onion">
   Security Onion
  </a>
  - Security Onion is a special Linux distro aimed at network security monitoring featuring advanced analysis tools
  <sup>
   &#9733 287, pushed 36 days ago
  </sup>
 </li>
 <li>
  <a href="http://digital-forensics.sans.org/community/downloads">
   SIFT Workstation
  </a>
  - The SANS Investigative Forensic Toolkit (SIFT) Workstation demonstrates that advanced incident response capabilities and deep dive digital forensic techniques to intrusions can be accomplished using cutting-edge open-source tools that are freely available and frequently updated.
 </li>
 <li>
  <a href="http://www.caine-live.net/index.html">
   CAINE
  </a>
  - The Computer Aided Investigative Environment (CAINE) contains numerous tools that help investigators during their analysis, including forensic evidence collection
 </li>
 <li>
  <a href="http://www.deftlinux.net/">
   DEFT
  </a>
  - The Digital Evidence & Forensics Toolkit (DEFT) is a Linux distribution made for computer forensic evidence collection. It comes bundled with the Digital Advanced Response Toolkit (DART) for Windows. A light version of DEFT, called DEFT Zero, is also available, which is focused primarily on forensically sound evidence collection
 </li>
 <li>
  <a href="https://forensics.cert.org/#ADIA">
   ADIA
  </a>
  - The Appliance for Digital Investigation and Analysis (ADIA) is a VMware-based appliance used for digital investigation and acquisition and is built entirely from public domain software. Among the tools contained in ADIA are Autopsy, the Sleuth Kit, the Digital Forensics Framework, log2timeline, Xplico, and Wireshark. Most of the system maintenance uses Webmin. It is designed for small-to-medium sized digital investigations and acquisitions. The appliance runs under Linux, Windows, and Mac OS. Both i386 (32-bit) and x86_64 (64-bit) versions are available.
 </li>
</ul>
<h3>
 Other Tools
</h3>
<ul>
 <li>
  <a href="https://github.com/obsidianforensics/hindsight">
   Hindsight
  </a>
  - Internet history forensics for Google Chrome/Chromium
  <sup>
   &#9733 76, pushed 2 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/davehull/Kansa/">
   Kansa
  </a>
  - Kansa is a modular incident response framework in Powershell.
 </li>
 <li>
  <a href="https://www.percona.com/doc/percona-toolkit/2.2/pt-stalk.html">
   Stalk
  </a>
  - Collect forensic data about MySQL when problems occur
 </li>
 <li>
  <a href="http://dnsminer.net/">
   DNS Miner
  </a>
  - DNS Miner is a semi-automatic incident response and threat intelligence tool for small, over worked security teams. Specific incident reponse features include a DNS sinkhole and historical analysis of DNS traffic against newly arriving data, e.g. suspicious domain lists
 </li>
 <li>
  <a href="https://github.com/CIRCL/traceroute-circl">
   traceroute-circl
  </a>
  - traceroute-circl is an extended traceroute to support the activities of CSIRT (or CERT) operators. Usually CSIRT team have to handle incidents based on IP addresses received. Created by Computer Emergency Responce Center Luxembourg
  <sup>
   &#9733 19, pushed 379 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/Neo23x0/Fenrir">
   Fenrir
  </a>
  - Fenrir is a simple IOC scanner. It allows scanning any Linux/Unix/OSX system for IOCs in plain bash. Created by the creators of THOR and LOKI
  <sup>
   &#9733 39, pushed 76 days ago
  </sup>
 </li>
 <li>
  <a href="https://github.com/google/stenographer">
   Stenographer
  </a>
  - Stenographer is a packet capture solution which aims to quickly spool all packets to disk, then provide simple, fast access to subsets of those packets. It stores as much history as it possible, managing disk usage, and deleting when disk limits are hit. It's ideal for capturing the traffic just before and during an incident, without the need explicit need to store all of the network traffic
  <sup>
   &#9733 836, pushed 1 days ago
  </sup>
 </li>
 <li>
  <a href="https://crits.github.io/">
   Crits
  </a>
  - a web-based tool which combines an analytic engine with a cyber threat database
 </li>
 <li>
  <a href="https://github.com/aboutsecurity/rastrea2r">
   rastrea2r
  </a>
  - allows one to scan disks and memory for IOCs using YARA on Windows, Linux and OS X.
  <sup>
   &#9733 23, pushed 15 days ago
  </sup>
 </li>
</ul>
<h3>
 Videos
</h3>
<ul>
 <li>
  <a href="https://www.demisto.com/category/videos/">
   Demisto IR video resources
  </a>
  - Video Resources for Incident Response and Forensics Tools
 </li>
 <li>
  <a href="https://www.youtube.com/watch?v=bDcx4UNpKNc">
   The Future of Incident Response
  </a>
  - Presented by Bruce Schneier at OWASP AppSecUSA 2015
 </li>
</ul>
<h3>
 Books
</h3>
<ul>
 <li>
  <a href="http://www.amazon.com/gp/product/1593275099">
   The Practice of Network Security Monitoring: Understanding Incident Detection and Response
  </a>
  - Richard Bejtlich's book on IR
 </li>
</ul>
<h3>
 Intro to IR
</h3>
<ul>
 <li>
  <a href="http://sroberts.github.io/2016/01/11/introduction-to-dfir-the-beginning/">
   Dfir intro
  </a>
  - By Scott J. Roberts
 </li>
</ul>
<h3>
 Playbooks
</h3>
<ul>
 <li>
  <a href="https://www.demisto.com/category/playbooks/">
   Demisto Playbooks Collection
  </a>
  - Playbooks collection
 </li>
 <li>
  <a href="https://www.incidentresponse.com/playbooks/">
   IR Workflow Gallery
  </a>
  - Different generic incident response workflows, e.g. for malware outbreak, data theft, unauthorized access,... Every workflow constists of seven steps: prepare, detect, analyze, contain, eradicate, recover, post-incident handling. The workflows are online available or for download.
 </li>
</ul>
<h3>
 Communities
</h3>
<ul>
 <li>
  <a href="https://dfircommunity.slack.com">
   Slack DFIR channel
  </a>
  - Slack DFIR Communitiy channel -
  <a href="https://rishi28.typeform.com/to/sTbTI8">
   Signup here
  </a>
 </li>
 <li>
  <a href="https://lists.sans.org/mailman/listinfo/dfir">
   Sans DFIR mailing list
  </a>
  - Mailing list by SANS for DFIR
 </li>
</ul>
