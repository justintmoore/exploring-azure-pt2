# Exploring Azure Part 2

 ### [YouTube Demonstration](https://youtu.be/AYW6kEUMDEI)

## Description
This will be a continuation of the previous Azure walkthrough. In this walkthrough, like in part 1 I will create a resource group that will house our resources. This time we will be creating 2 Virtual Machines (VMs), a virtual network, a corresponding subnet, where both VMs will be.

I will create a Windows 10 VM with remote desktop protocol enabled. The second VM I will create will be a Ubuntu Server 2022, with Remote Desktop Protocol enabled. After we will conform that both machines are in the same virtual network/subnet.

<b>Reminder!<b/> At the end of this lab do not delete these VMs, as we will use them in the next walkthrough


## Tools, Utilities, Services Used
- Microsoft Azure


## Environments Used 
- Windows 11


## Program walk-through  
- 










## Go to Part 3
<!--
- Create an Account
- While on Azure homepage, you will see Azure Services at the top of the window. There you will find "Resource Groups". If you don't see it, you can type in "Resource Groups" into the search bar.
  <img src="https://github.com/user-attachments/assets/faa7da2c-02d3-463e-bc77-cb7d4b41a0df" height="70%" width="70%" alt="home"/>
  
- Now click "Create". Choose your Resource Group name, and choose a "region", which is where the metadata or resource details of your resource group is located.  
  <img src="https://github.com/user-attachments/assets/bffb8cbc-1b10-4e49-a7ac-ee817365efc7" height="70%" width="70%" alt="rg1"/>  
  
- You can add tags to logically organize your resource groups. They consist of a key-value pair, but for now move on. Review the details of your resource group, and click "Review and Create".

- After resource group is deployed, we will create a Storage Account within the resource group.

- In the search bar above, type "storage account", after select "Create".
  <img src="https://github.com/user-attachments/assets/e74da62c-bb91-4295-9189-4b6cf378cf87" height="70%" width="70%" alt="rg1"/>

- You must declare which resource group you want to have this storage account, name your storage account (must be globally unique), change "Redundancy" to locally redudant storage (LRS). Now click "Create". 
  <img src="https://github.com/user-attachments/assets/7d1e045c-a4ab-40b2-b5fe-e9a1c6876b90" height="70%" width="70%" alt="rg1"/>

- Check to ensure that you have your resource group and storage account by navigating to your resource group, clicking it, and seeing whether or not your storage account is in there.  
  <img src="https://github.com/user-attachments/assets/383537df-eb7b-49c2-a676-cd5e2610d659" height="70%" width="70%" alt="checkstorage"/>

- Now for part one we will create a text file, save it to our desktop, then upload it into the storage account.

- Go to your "storage account", on the side there should be a drop down that reads "data storage". Click that and underneath choose "container".  
  <img src="https://github.com/user-attachments/assets/f99f54a2-db30-44b0-8dad-4a83d57dc71b" height="70%" width="70%" alt="container"/>

- Click "+ Container" at the top, and name your container. This will serve almost like a folder. Now click "Create".
  <img src="https://github.com/user-attachments/assets/a5af094f-aaad-4e99-b77b-a457eaabcb24" height="70%" width="70%" alt="createcontainer"/>

- Choose your storage container, and now upload the text file we created earlier.
  <img src="https://github.com/user-attachments/assets/969a99cd-9b9f-4796-a503-c018f07a5ad3" height="70%" width="70%" alt="upload"/>

- Once uploaded we can view the text file, edit it, save it, then download it so we can save it locally on our desktop. Open up the file on your desktop to see the changes.  
  <img src="https://github.com/user-attachments/assets/d8165b48-faae-4b6e-9af9-bc51181df4c3" height="70%" width="70%" alt="editdownload"/>  

- That ends this portion of the project. You can delete each resource individually, or you can delete the resource group entirely to get rid of everything within the resource group.
- To do this go to your Resource Group page, and click "delete resource group". This will prompt you to enter the resource groups name, and click "delete".
 <img src="https://github.com/user-attachments/assets/b26282f0-75cf-4b44-ba43-6c9401a9d55c" height="70%" width="70%" alt="delete"/>
 <img src="https://github.com/user-attachments/assets/799c9a8d-fd0d-4073-9618-5f3c1e0a544a" height="70%" width="70%" alt="delete"/>
 

