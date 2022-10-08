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
* Platform: Windows, Mac OS, Linux

# Usage
* -u url
* -p port
* -vS vulnerability scan

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
└─$ python3 main.py -vS -u https://github.com/ -p 22,80 
```
