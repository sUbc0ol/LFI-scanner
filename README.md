# LFI-scanner
# Simple Local File Inclusion Vulnerability Scanner
# by r0otz-ee
# Version 1.0 
 
# ASCII FOR BREAKFAST
 
# ---------- [Description]
# This tool helps you to find LFI (Local File Inclusion) vulnerabilities.
 
# ---------- [Features]
# - This time with working random user agents ^_^
# - Checks if a connection to the target can be established
# - Some error handling
# - Scans an URL for LFI vulnerabilities
# - Finds out how a possible LFI vulnerability can be exploited (e.g. directory depth)
# - Supports nullbytes
# - Supports common *nix targets, but no Windows systems.
# - Creates a small log file.
# Supports no SEO URLs, such as www.example.com/local-news/
# But in most cases it is possible to find out the real URL and pass it to this script.
 
# ---------- [Usage example]
# ./lfi_scanner.py --url="http://www.example.com/page.php?url=main"
 
# ---------- [Known issues]
# - This tool is only able to find "simple" LFI vulnerabilities, but not complex ones.
# - Like most other LFI scanners, this tool here also has trouble with
#   handling certain server responses. So this tool does not work with every website.
 
# ---------- [Tested with]
# Targets: Apache2 servers and PHP websites, various Linux systems
# Script platform: Ubuntu Lucid Lynx and Python 2.6.5
 
# ---------- [Notes]
# - This tool was developed using a Python 2.6.5 interpreter.
# - I admit: This tool is a little bit slow and not very efficient (too many variables etc.). Sorry about that :P
# - Modify, distribute, share and copy this code in any way you like!
# - Please note that this tool was created and published for educational purposes only, e.g. for pentesting
#   your own website. Do not use it in an illegal way and always know + respect your local laws.
#   I am not responsible if you cause any damage with it.
 
# ---------- [Changelog]
# - Version 1.0 :
#    - Initial release
 
# Power to the lulz!
