
## Steps to Deploy HyperspaceWeb Application Objects

- login to BIG-IP ```https://10.1.1.6``` ```admin:admin.F5demo.com```
 
- Follow the below steps to deploy HyperspaceWeb objects on BIG-IP

- Make sure to Sync BIG-IP devices

![Do Manual Sync](../docs/sync2.png)

- Navigate to Apps--> Application Services --> ApplicationLX 
- Then Select F5 Application Service Templates

![Do Manual Sync](../docs/apps.png)

- Go down on the page and locate HyperspaceWeb_VS_HTTPS template

![Do Manual Sync](../docs/template.png)

- Click on the template and Hit Deploy

![Do Manual Sync](../docs/deploy.png)

- You should see sucess in the History as shown below
![Do Manual Sync](../docs/sucess.png)

- Navigate to Local Traffic tab on the left 
- Select Virtual server
- Select EpicHyperspace partition
![Do Manual Sync](../docs/partition.png)

- You should see the Virtual Server deployed

![Do Manual Sync](../docs/vs.png)

- Make sure you Sync the BIG-IP again navigating to Device Management
and Overview and click on Sync

![Do Manual Sync](../docs/sync2.png)

[GoTo Next Exercise1.3](../Exercise1.3/README.md)

[GoBack](../README.md)
