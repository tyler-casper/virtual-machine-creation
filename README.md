# Azure Virtual Machine Creation

![image](https://github.com/user-attachments/assets/e21474ed-4afe-4660-ba89-eeca9e121b27)


<h2>Summary</h2>

 This tutorial outlines the creation of the Microsoft Azure Virtual Machine.

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Resource Groups & Virtual Machines)

<h2>Operating Systems Used </h2>

- Windows 10

<h2>List of Prerequisites</h2>

- Microsoft Azure Subscription (Free or Paid)

<h2>Creation Steps</h2>

![image](https://github.com/user-attachments/assets/5e4ba72a-0a0f-4de8-b214-18a72d994da1)

First, we will make our way to the Azure home page. This can be done by typing in the URL, portal.azure.com

![image](https://github.com/user-attachments/assets/8d7f2325-6294-4900-87ec-7632a91de458)

We will then go to the search bar and type in "Resource Groups", and click on the following.

![image](https://github.com/user-attachments/assets/60f38e77-5140-4cde-8784-b9797bb5fe78)

We will then click on the blue "Create" box.

![image](https://github.com/user-attachments/assets/af635057-4866-4eb9-8103-bd59b2009d19)

From here, choose the Azure Subscription you will be using for this Resource Group. You will then name this Resource Group. For this example, I've named mine RG-Practical Assessment. You can also choose which region you would like this Resource Group to be located. Note that not all regions may be available to you if you are not using a paid subscription.

![image](https://github.com/user-attachments/assets/544421e6-0145-4b84-90f4-a9f6785d4c34)

Navigate to the bottom of the screen, and click on the box "Review + Create".

![image](https://github.com/user-attachments/assets/044d3d6f-3169-41ba-a8fe-8155f366c74a)

If you get a green checkmark and a "Validation passed" at the top of your screen, you are now able to create your Resource Group. Navigate back down to the bottom of your screen and click on the "Create" box.

![image](https://github.com/user-attachments/assets/b08cc4bc-4799-4f5a-8942-d5ed7f74d28a)

Afterwards you should have a screen that is similiar to this.

![image](https://github.com/user-attachments/assets/94857a5c-e1c6-46a0-b36c-b3a625c0b069)

Navigate back up to the search bar and type in, "Virtual Machines", and click on the following.

![image](https://github.com/user-attachments/assets/143b583f-99c0-4d61-946f-6fae70a0609e)

Here we will agin click on the blue "Create" box. This will open a drop down menu. Click on the "Azure Virtual Machine" choice.

![image](https://github.com/user-attachments/assets/452dfecb-41ee-4357-a4f5-822cfb4ab46b)

You will then be taken to a page that looks like this. Select which subscription you would like to use. Then select the Resource Group that we just created. This decides which resource group the Virtual Machine will be created in. 

![image](https://github.com/user-attachments/assets/5fe4d915-7ba8-4d0f-be72-570d6305d3cd)

Next, give your Virtual Machine a name. For this example, I've named mine VM-Practical-Assessment. You may also select which region to create your Virtual Machine in. 

![image](https://github.com/user-attachments/assets/ece48917-3e6e-4724-9b71-6f0e71941b26)

Now we can choose which architecture that we wish for our Virtual Machine to use. In this example, I've chosen a Windows 10 Pro version. You may also choose a Virtual Machine that runs on Linux if you so choose. Below that we can choose which size we want our Virtual Machine to be. Note, one that has more vcpus, the better the performance but it also increases the price.

![image](https://github.com/user-attachments/assets/bc49a73d-a2a6-48e2-801c-415ab18d1704)

From there, we will give our Virtual Machine a Username and Password. In this example, I've given my Virtual Machine the Username "labuser".

![image](https://github.com/user-attachments/assets/60daf2d1-3c5e-4b1c-8f56-fecb551dd46b)


Don't forget to check the "Licensing" box at the bottom of the page. It is very easy to miss, and leaving this box unchecked will not allow your Virtual Machine to be created.

![image](https://github.com/user-attachments/assets/01f49268-773e-4072-b8e4-4b3ebbf1129d)

From here, you should be ready. Click the blue "review + create" box at the bottom of your screen.

![image](https://github.com/user-attachments/assets/ca658fd4-3330-4783-b773-b63e63a60cd6)
![image](https://github.com/user-attachments/assets/965729ad-74c9-4f7c-a22a-988ff5062e42)

If you get a green check mark that says "Validation passed" next to it, your Virtual Machine is ready to be created. Click the blue "Create" box at the bottom of your screen, and watch your Virtual Machine be created.

![image](https://github.com/user-attachments/assets/ff24c463-9361-428b-bb8d-baab08e3cd69)
![image](https://github.com/user-attachments/assets/f1ec0fe3-56ad-4ca7-b443-a4365b2816e1)

Your next screen should show a "Deployment in progress", and after its done being created it will change to a "Your deployment is complete". Your Virtual Machine is now ready to go. Enjoy.



