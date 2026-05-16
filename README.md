# monikerlinktest
cve-2024-21413

1. set up tun0 or other tun(#) on router via openvpn on any ovpn file

2. install remmina if not yet done so

3. RDP to target desktop using remmina on the port your ovpn connected to (ip link delete the one that's down if duplicated)

4. follow exploit.py command to replace any placeholders

5. open a responder

6. run 'python3 exploit.py' and enter password

7. check responder terminal for user hash 
