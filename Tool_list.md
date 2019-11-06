# CTF TOOL LIST
An ever-expanding list of tools that are helpful in CTF competition challenges.





## COMMANDLINE TEXT MANIPULATION
### grep
### strings
- Really handy for findng text embeded inside files, etc.
### tail
### head
### tr
### cut
### sed
### awk
### xxd
- The xxd command in Linux lets you create a hexdump or do the reverse. 
### jq 
- [website](https://stedolan.github.io/jq/)
- A lightweight and flexible command-line JSON processor. You can use it to slice and filter and map and transform structured data with the same ease that sed, awk, grep and friends let you play with text.

## CRYPTO
## cyberchef
- [website](https://gchq.github.io/CyberChef/)
## factordb
- [website](http://factordb.com)

## PASSWORD CRACKING
### johntheripper


## REVERSE ENGINEERING
### radare2
- [website](https://www.radare.org/r/)
- portable reversing framework that an be used for dissasembly, debugging, forensics, patching, analysis, and exploitation
### hopper
- [website](https://www.hopperapp.com/)
-  Hopper Disassembler, the reverse engineering tool that lets you disassemble, decompile and debug your applications. 
### binary ninja 
- [website](https://binary.ninja/)
### ghidra
- [website](https://ghidra-sre.org/)
- A software reverse engineering (SRE) suite of tools developed by NSA's Research Directorate
### IDA
- [website](https://www.hex-rays.com/products/ida/index.shtml)
### dmesg
### ltrace 
- Debugging program to track runtime library calls in dynamically linked programs
### strace 
- [website](https://strace.io/)
- Diagnostic, debugging and instructional userspace utility for Linux. It is used to monitor and tamper with interactions between processes and the Linux kernel, which include system calls, signal deliveries, and changes of process state.
### gdb
### peda for gdb
### edb
- [github](https://github.com/eteran/edb-debugger)
- A cross platform AArch32/x86/x86-64 debugger. 
### OllyDbg 
- [website](http://www.ollydbg.de/)
### qira
- [website](https://qira.me/)
- A timeless debugger. All state is tracked while a program is running, so you can debug in the past.
- Can be integrated with IDA.
### nasm
### ROPgadget
- [github](https://github.com/JonathanSalwan/ROPgadget)
- This tool lets you search binaries to facilitate in ROP exploitation. 
### binwalk
- [github](https://github.com/ReFirmLabs/binwalk)
- Binwalk is a fast, easy to use tool for analyzing, reverse engineering, and extracting firmware images.
### dd
- Can be used to extract userful parts from binary files, really handy when reversing firmware for example.
### QEMU
- [website](https://www.qemu.org/)
- A generic and open source machine emulator and virtualizer.

## FORENSICS
### exiftool
### file
### foremost
### fsck
### ghex
### hexedit
### zsteg 
  - [github](https://github.com/zed-0xff/zsteg)
### Autopsy 
  - [website](https://www.autopsy.com/)
  - the premier end-to-end open source digital forensics platform. Built by Basis Technology with the core features you expect in commercial forensic tools, Autopsy is a fast, thorough, and efficient hard drive investigation solution that evolves with your needs.
### EnCase Forensic 
  - [website](https://www.guidancesoftware.com/encase-forensic?cmpid=nav_r)
  - EnCase Forensic enables you to quickly search, identify, and prioritize potential evidence, in computers and mobile devices, to determine whether further investigation is warranted. 
### Pftriage
  - [github](https://github.com/idiom/pftriage)
  - a tool to help analyze files during malware triage. It allows an analyst to quickly view and extract properties of a file to help during the triage process. The tool also has an analyze function which can detect common malicious indicators used by malware.


### NETWORK
### wireshark
### network miner
### tcpdump
### ngrep
  - [github](https://github.com/jpr5/ngrep)
- ngrep is like GNU grep applied to the network layer. 
### scapy
- [website](https://scapy.net/)
- Scapy is a powerful Python-based interactive packet manipulation program and library.

## WEB 

### chrome
- the chrome browser in general seems to have a lot better support and better interfaces for poking at websites(this is obviously anecdotal)
### browser addons
- editthiscookie ([chrome](https://chrome.google.com/webstore/detail/editthiscookie/fngmhnnpilhplaeedifhccceomclgfbg?hl=en))
- wappalyzer ([firefox](https://addons.mozilla.org/en-US/firefox/addon/wappalyzer/)/[chrome](https://chrome.google.com/webstore/detail/wappalyzer/gppongmhjkpfnbhagpmjfkannfbllamg))
- imacros ([firefox](https://addons.mozilla.org/en-US/firefox/addon/imacros-for-firefox/)/[chrome](https://chrome.google.com/webstore/detail/imacros-for-chrome/cplklnmnlbnpmjogncfgfijoopmnlemp?hl=en))
### burp
- [website](https://portswigger.net/burp)
- Graphical tool for testing Web application security.
### postman
- [website](https://www.getpostman.com/)
- A collaboration platform for API development. Explore the API by sending it different kinds of data to see what values are returned. Automate manual tests and integrate them into your CI/CD pipeline to ensure that any code changes won't break the API in production.

## PWN/EXPLOIT

### shell-storm
- Has code to get shell on nearly any architecture and OS.
- [website](http://shell-storm.org/)


## PROGRAMMING

### PYTHON
- pwn tools
