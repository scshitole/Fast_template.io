
## Steps to Deploy InterConnect_Backgroud Application Objects

- login to BIG-IP ```https://10.1.1.6``` ```admin:admin.F5demo.com```
 
- Follow the below steps to deploy InterConnect_Backgroud onjects on BIG-IP

- Make sure to Sync BIG-IP devices

![Do Manual Sync](../docs/sync2.png)

- Navigate to Application Services --> ApplicationLX 
- Then Select F5 Application Service Templates

![Do Manual Sync](../docs/apps.png)

- Go down on the page and locate InterConnect_Backgroud_VS_HTTPS template

![Do Manual Sync](../docs/template2.png)

- Click on the template and Hit Deploy

![Do Manual Sync](../docs/deploy2.png)

- You should see sucess in the History as shown below
![Do Manual Sync](../docs/sucess2.png)

- Select EpicHyperspace partition
![Do Manual Sync](../docs/partition2.png)

- You should the Virtual Server deployed

![Do Manual Sync](../docs/vs2.png)

- Make sure you Sync the BIG-IP again navigating to Device Management
and Overview and click on Sync

![Do Manual Sync](../docs/sync2.png)

[GoTo Next Exercise1.4](../Exercise1.4/README.md)


[GoBack](../README.md)
