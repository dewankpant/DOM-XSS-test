# CVE-2017-16567

# Exploit Title: Logitech Media Server : Persistent Cross Site Scripting(XSS)
# Shodan Dork: Search Logitech Media Server
# Date: 11/03/2017
# Exploit Author: Dewank Pant
# Vendor Homepage: www.logitech.com
# Software Link: [download link if available]
# Version: 7.9.0
# Tested on: Windows 10, Linux
# CVE : Applied For.
 
 
 
POC:
 
Access and go to the favorites tab and add a new favorite.
Add script as the value of the field.
Payload : <script> alert(1)</script>
Script saved and gives a pop-up to user every time they access that page.
Therefore, Persistent XSS.
