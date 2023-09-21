
The following components have been included in your lab environment:

- F5 BIG-IP VE (bigipA)
- F5 BIG-IP VE (bigipB)
- Windows Jumphost
- Ubuntu LAMP Server

- RDP into Windows Jump box using ```external_user:admin.F5demo.com```

![RDP into Windows Machine](../docs/rdp.png)

- Now login into the BIG-IP using Access --> Web Shell on bigipA & bigipB
- Login to bigipA using ```admin:admin.F5demo.com and/or root:default```
- Login to bigipB using ```admin:admin.F5demo.com and/or root:default```

![Login into bigipA & bigipB](../docs/accessbigip.png)

- If you see the BIG-IPs are not sync, then go to Device Overview 
- Do Manual Sync as shown below

![Do Manual Sync](../docs/sync.png)
