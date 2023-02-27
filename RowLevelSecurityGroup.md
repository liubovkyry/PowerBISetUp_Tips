In Power BI.com, you can assign Office 365 security groups to roles in addition to users. Setting up roles still has to be done through Power BI Desktop.

![image](https://user-images.githubusercontent.com/118057504/221595449-cd5961d1-a4bd-4f4a-8fbf-1585a04bdd84.png)

I've set up three roles related to a branches' region location. Now I'll go over to my Office 365 Admin center. In Active teams and groups, I've set up user-defined groups within Microsoft 365, Distribution list, Mail-enabled, and Security, all prefixed with SAM. In Power BI.com, go to the dataset in question, click on more options, and select security. If there are no roles defined in your dataset, you'll get this message about Row-Level Security being defined in Power BI Desktop. The roles you have defined will appear under Row-Level Security, and you add users and groups to those roles here. When I start to type in the add people or groups field, users to add appear as you'd expect. If I start to type SAM, the user groups I defined within Office 365 also appear, except for the group created under Microsoft 365. As I assign users or groups to the roles, the assigned count in brackets next to the roles increase.


![image](https://user-images.githubusercontent.com/118057504/221595601-de570d7a-761c-4d55-b4e7-3d3c718f6a3b.png)
![image](https://user-images.githubusercontent.com/118057504/221595821-8c724b50-608a-4415-8da3-188b8332e141.png)
![image](https://user-images.githubusercontent.com/118057504/221595924-ae04e9bf-80ac-4dc5-8631-3f552e5c9382.png)
![image](https://user-images.githubusercontent.com/118057504/221595983-87dd8da5-0648-409d-8b77-4aff6605dd04.png)
