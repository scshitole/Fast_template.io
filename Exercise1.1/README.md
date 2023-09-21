
The following components have been included in your lab environment:

- F5 BIG-IP VE (bigipA)
- F5 BIG-IP VE (bigipB)
- Windows Jumphost
- Ubuntu LAMP Server

| Host | Management IP | username:password |
|----------|----------|----------|
| bigipA | 10.1.1.5 | admin:admin.F5demo.com and/or root:default |
| bigipB | 10.1.1.6 | admin:admin.F5demo.com and/or root:default|
| Windows Jumpbox | 10.1.1.7 | external_user:admin.F5demo.com |


- RDP into Windows Jump box using ```external_user:admin.F5demo.com```

![RDP into Windows Machine](../docs/rdp.png)

- open the Google Chrome browser in the Windows jump box 
- Login to bigipB using ``` https://10.1.1.6```
- Login to bigipA using ```https://10.1.1.15```

- If you see the BIG-IPs are not sync, then go to Device Overview 
- Do Manual Sync as shown below

![Do Manual Sync](../docs/sync.png)


[GoTo Next Exercise1.2](../Exercise1.2/README.md)

[GoBack](../README.md)
