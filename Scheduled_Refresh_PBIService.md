

Scheduled refresh has been disabled.


Data source errorScheduled refresh is disabled because at least one data source is missing credentials. To start the refresh again, go to this dataset's settings page and enter credentials for all data sources. Then reactivate scheduled refresh.


## You must have administrator acess into workspace to set the credentials into gateway which has configured.
<img src="https://user-images.githubusercontent.com/118057504/217490809-72d4af87-7b0c-4a92-a0e7-dad90fb6ff91.png" width="450" height="450">

## Use a gateway
There are five main steps for using a gateway:

### 1 Download and install the gateway on a local computer.
 https://learn.microsoft.com/en-us/data-integration/gateway/service-gateway-install
 You need to sign in with either a work account or a school account. This account is an organization account. 
 
 <img src="https://user-images.githubusercontent.com/118057504/217493005-8dbb20af-d132-4d1c-b66d-87f634d130eb.png" width="450" height="450">
 
 Select Register a new gateway on this computer > Next.
 
<img src="https://user-images.githubusercontent.com/118057504/217493083-1d408ce7-94fb-4f47-b3f5-1d8e2fd7190c.png" width="450" height="450">

 Enter a name for the gateway. The name must be unique across the tenant. Also enter a recovery key. You'll need this key if you ever want to recover or move your gateway. Select Configure.

<img src="https://user-images.githubusercontent.com/118057504/217493778-606f55ce-1a2c-4eb6-a472-9722ff5875f2.png" width="450" height="450">
 
<img src="https://user-images.githubusercontent.com/118057504/217493846-04ca2ab9-9237-424d-8fcf-876b3ea740b9.png" width="450" height="450">
 
 Now that you've installed a gateway, you can add another gateway to create a cluster.




 ### 2 Configure the gateway based on your firewall and other network requirements.
 https://learn.microsoft.com/en-us/data-integration/gateway/service-gateway-app
 
 To open the on-premises data gateway app:

1 On the machine where the gateway is running, enter gateway in Windows search.

2 Select the On-premises data gateway app.

<img src="https://user-images.githubusercontent.com/118057504/217496554-d87dbb5f-493d-49c5-8308-6577fe2b7c54.png" width="450" height="250">

<img src="https://user-images.githubusercontent.com/118057504/217496772-22bd68e9-2656-4b7d-9299-12ca6ebd09d0.png" width="450" height="450">
<img src="https://user-images.githubusercontent.com/118057504/217497159-231b9d81-1fa5-4432-8729-d089cdd4b25d.png" width="450" height="450">

<img src="https://user-images.githubusercontent.com/118057504/217497763-71b53125-b372-430f-b3db-ca7c64eeceec.png" width="450" height="450">

On-premises data gateway app features
After you sign in to your Office 365 account, you have access to the following features in the on-premises data gateway app.


 ### 3 Add gateway admins who can also manage and administer other network requirements.
 https://learn.microsoft.com/en-us/data-integration/gateway/service-gateway-manage
 Note

Manage gateways won't show up until you're the admin of at least one gateway. You become an admin either by being added as an admin or because you installed and configured a gateway.
 
 
 ### 4 Use the gateway to refresh an on-premises data source.
 
 https://learn.microsoft.com/en-us/power-bi/connect-data/service-gateway-sql-tutorial
 
 ### 5 Troubleshoot issues with the gateway.
 
 https://learn.microsoft.com/en-us/power-bi/connect-data/service-gateway-onprem-tshoot

