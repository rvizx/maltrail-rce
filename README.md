# MalTrail - Command Injection / RCE

MalTrail - Command Injection / RCE PoC Exploit

![alt text](https://rvizx.github.io/maltrail-rce/img.png?raw=true)

MalTrail version `0.53` doesn't have proper validation in `username` parameter, which leads to unauthenticated command injection.

# Usage

```
git clone https://github.com/rvizx/maltrail-rce
cd maltrail-rce
chmod +x exploit.sh 
```

```
./exploit.sh <target_url> <attacker_ip>
```

# notes

https://huntr.dev/bounties/be3c5204-fbd9-448d-b97c-96a8d2941e87/
