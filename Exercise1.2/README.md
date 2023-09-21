
## Steps to Deploy HyperspaceWeb Application Objects

- Follow the below steps to deploy HyperspaceWeb onjects on BIG-IP

- Make sure to Sync BIG-IP devices

![Do Manual Sync](../docs/sync2.png)

- Navigate to Application Services --> ApplicationLX 
- Then Select F5 Application Service Templates

![Do Manual Sync](../docs/apps.png)

- Go down on the page and locate HyperspaceWeb_VS_HTTPS template

![Do Manual Sync](../docs/template.png)

- Click on the template and Hit Deploy

![Do Manual Sync](../docs/Deploy.png)

- You should see sucess in the History as shown below
![Do Manual Sync](../docs/sucess.png)

- Select EpicHyperspace partition
![Do Manual Sync](../docs/partition.png)

- You should the Virtual Server deployed

![Do Manual Sync](../docs/vs.png)
- RDP into Windows Jump box using ```external_user:admin.F5demo.com```

- Make sure you Sync the BIG-IP again navigating to Device Management
and Overview and click on Sync

![Do Manual Sync](../docs/sync2.png)
[GoBack](../README.md)
