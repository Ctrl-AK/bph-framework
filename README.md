# BLACKPHENIX - MALWARE ANALYSIS &amp; AUTOMATION FRAMEWORK

BLACKPHENIX is an open source malware analysis automation framework composed of several services, scripts, plug-ins, and tools and is based on a Command-and-Control (C&C) architecture

## Features
- Easy Installation & Deployment
- Python automation modules for malware analysis tools 
- Virtual Machine Management
- Scripting support (BPH Scripts)
- Internet emulation 
- Traffic redirection
- TOR support

## Requirements
1.  Windows 7/10 (Host-Machine) with VirtualBox installed
2.  Windows VM (Guest) installed and in operation
    - .NET FRamework (latest version)
3.  Ubuntu x64 VM (BPH Controller / C&C Server)
    - Iptables, dnsmasq installed
    - BurpSuite Free version installed

## Usage
python <bph_script> <sample_file>
