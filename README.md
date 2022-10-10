# Spymap
Web vulnerability scanner

|Spymap|vulns|
|----|----|
|XSS| ✔️ |
|xee| ✔️ |
|Sql injection| ✔️ |
|Cross-site request forgery| ✔️ |
|Broken Authentication| ✔️ |


-----
* Host name
* Banner grabbing[TCP]
* OS detection
* Firewall detection
* Platform: Windows, Mac OS, Linux

# Usage
* -u url
* -p port
* -oD os detect
* -fD firewall detect

```bash
┌──(root㉿kali)-[~]
└─$ python3 main.py --help
```
```bash
┌──(root㉿kali)-[~]
└─$ python3 main.py -u https://github.com/ -p 22,80
```
```bash
┌──(root㉿kali)-[~]
└─$ python3 main.py -u https://github.com/ -p 22,80 -oD -fD 
```
