## Cmdkey.exe

* Functions: Credentials

```
cmdkey /list
```

Acknowledgements:
* 

Code sample:
* 

Resources:
* https://www.peew.pw/blog/2017/11/26/exploring-cmdkey-an-edge-case-for-privilege-escalation

Full path:
```
c:\windows\system32\cmdkey.exe
c:\windows\sysWOW64\cmdkey.exe
```

Notes:
* To execute commands with cached credentials locally, use the runas command with the savecreds flag.

```
runas /savecred /user:COMPUTER_OR_DOMAIN_NAME\Victim "ping 10.10.14.8"
```

Detection:


 
