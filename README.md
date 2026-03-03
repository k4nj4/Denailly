```
root@kali:~# whoami
 _      ___       _   ___ 
| |    /   |     (_) /   |
| | __/ /| |_ __  _ / /| |
| |/ / /_| | '_ \| / /_| |
|   <\___  | | | | \___  |
|_|\_\   |_/_| |_| |   |_/
                _/ |      
               |__/       
```
## Offensive Security Analyst

```
root@kali:~# id

uid=0(root) gid=0(root) groups=0(root),1337(infosec),8080(web-hackers)
```

```
root@kali:~# systemctl status brain.service

● brain.service - Continuous Learning Engine
   Loaded: loaded (/etc/systemd/system/brain.service; enabled)
   Active: active (running) since Sun 2024-01-01 00:00:00 UTC; 24h ago
   Main PID: 1337 (mind)
   Tasks: 3 (limit: 32768)
   Status: "Scanning for vulnerabilities..."
   CGroup: /system.slice/brain.service
           ├─1337 Pentesting & Automation
           ├─1338 Binary Exploitation
           └─1339 Cloud Security Architecture
```
```
root@kali:~# ls -la /opt/skills/

total 42
drwxr-xr-x 2 root root 4096 Jan  1 00:00 .
drwxr-xr-x 3 root root 4096 Jan  1 00:00 ..
-rwxr-xr-x 1 root root 1024 Jan  1 00:00 bash
-rwxr-xr-x 1 root root 2048 Jan  1 00:00 c-sharp
-rwxr-xr-x 1 root root 2048 Jan  1 00:00 javascript
-rwxr-xr-x 1 root root 4096 Jan  1 00:00 python
-rwxr-xr-x 1 root root 1024 Jan  1 00:00 react
-rwxr-xr-x 1 root root 2048 Jan  1 00:00 typescript
```
```
root@kali:~# echo $ARSENAL_PATH

/usr/bin/nmap:/opt/burpsuite:/opt/metasploit:/usr/local/bin/wireshark:/opt/ghidra
```
```
root@kali:~# ./connect.sh --verbose

[+] Initiating secure handshake...
[+] Connections established:
```
LinkedIn  <-- TCP 443 (Encrypted)
Email <-- TCP 25 (SMTP)

`root@kali:~# _`
