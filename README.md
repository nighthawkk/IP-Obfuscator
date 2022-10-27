# IP Obfuscator
Simple script you can use to convert and obfuscate any IP address of any host.

## Usage
```
usage: python3 IP_obfuscator.py <ip>

```

## Example
```
$ python3 IP_obfuscator.py 127.0.0.1
Entered IP:  127.0.0.1
[~] Obfuscated IPs:

[+] http://2130706433
[+] http://0x7f000001
[+] http://017700000001

[+] http://0177.00.00.01
[+] http://00000000177.000000000.000000000.000000001
[+] http://0x7f.0x0.0x0.0x1
[+] http://0x000000007f.0x000000000.0x000000000.0x000000001

[+] http://0x7f.0x0.0x0.1
[+] http://0x7f.0x0.0.1
[+] http://0x7f.0.0.1
[+] http://127.0x0.0x0.0x1
[+] http://127.0.0x0.0x1
[+] http://127.0.0.0x1

[+] http://0177.00.00.1
[+] http://0177.00.0.1
[+] http://0177.0.0.1
[+] http://127.00.00.01
[+] http://127.0.00.01
[+] http://127.0.0.01

[+] http://0x7f.0x0.1
[+] http://0x7f.1
[+] http://0177.00.1
[+] http://0177.1
[+] http://0x7f.00.1
[+] http://0177.0x0.1

IPv4 mapped IPv6 addresses:
[+] http://::ffff:7f000001
[+] http://0:0:0:0:0:ffff:7f000001
[+] http://0000:0000:0000:0000:0000:ffff:7f000001
[+] http://0000:0000:0000:0000:0000:ffff:127.0.0.1

```
