# Creating-Windows-VM-with-Microsoft-Azure
Hello Guys, Today I will be showing you how to create, and ping commands in a virtual machine using Microsoft Azure

SECTION 1: Create a Resource Group

![Az_Net_1](https://user-images.githubusercontent.com/116504189/198410583-f6f9db82-89ba-4eba-92ff-cb99ffee8281.jpeg)

We will begin by going to "portal.azure.com". Next, we will search for "resource group" in the azure searchbar (the icon will look like a blue cube).

![Create-VM-rg2](https://user-images.githubusercontent.com/116504189/198410787-704b7f7c-5d5e-47bd-b0e7-45dfb9cfd54f.png)

Once clicked, you will notice that the section is empty. Let's fix that, click on "create".

![Create-VM-rg3](https://user-images.githubusercontent.com/116504189/198410887-3ffca5ae-06cd-4576-bb57-b3a890d3b2c9.png)

What we will focus on is the name of the resource group. This name can literally be anything you want it to be (I would suggest something like "vm-lab" if you have multiple resource groups). When you've typed the desired name, click "review + create" at the bottom.

![Create-VM-rg4](https://user-images.githubusercontent.com/116504189/198411157-8bee2b52-4327-4de4-893f-db4030d4aaac.png)

After that, we should see the next screen say "validation passed", this means that our resource group has been created. :)

![Create-VM-rg5](https://user-images.githubusercontent.com/116504189/198411328-9f1e4ba0-ec09-4b74-8db0-2c5c2a68ac50.png)

SECTION 2: Creating a Virtual Machine

![Create-VM-win1](https://user-images.githubusercontent.com/116504189/198411433-dfa57b0d-ba21-4ae5-ad39-0a4040590d76.png)

Next, we will create a virtual machine for our research group. We will type in "virtual machine" in the azure searchbar, and click on the icon that looks like a blue monitor.

![Create-VM-win2](https://user-images.githubusercontent.com/116504189/198411591-afbd537f-84f5-47d8-ab62-777ed9165d16.png)

Once you have clicked that, we can see that our section is virtually (badum pshhhhh) empty. Go ahead and click on "create".

![Create-VM-win3](https://user-images.githubusercontent.com/116504189/198411708-27179017-9131-4739-a993-72efa347dc38.png)

For the research group tab, we will select the resource group we had previously made.

![Create-VM-win5](https://user-images.githubusercontent.com/116504189/198411885-7a3c36d1-b623-4c9a-a0e8-7f50dc06f2dc.png)

This part of the section, we will only focus on the "image", we will be working with a window, so let's select "windows 10".

