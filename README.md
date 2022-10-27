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

![Create-VM-win6](https://user-images.githubusercontent.com/116504189/198412140-5016d58b-87e7-4c0f-8fa7-16021d6c8da9.png)

For the size, we want to select something with at least more than one cpu. I choose more than one because it will move faster, and reduce the latency of the virtual machine's function. Now comes the username and password, I personally recommend writing these down for further use so that you do not forget. Once finished, you can click "review + create".

![Create-VM-win7](https://user-images.githubusercontent.com/116504189/198412695-d5b5af6e-6d6e-4aa3-a03c-d7f8bbe9b201.png)

Once we've received our "validation passed" screen, click "create". CONGRATS!! You've just created your Windows virtual machine :). You'll want to wait until everything is fully deployed before continuing any further. Look for these next pages.

![Create-VM-win8](https://user-images.githubusercontent.com/116504189/198413617-4be4837d-f277-472b-8ed4-60c94eafdde5.png)

![Create-VM-win9](https://user-images.githubusercontent.com/116504189/198413583-d6867683-6e41-48de-9b26-24a5d94a5e38.png)

![Create-Vm-win10](https://user-images.githubusercontent.com/116504189/198413647-78d92f8f-e672-4306-91a8-a71b83d889e0.png)

Let's go back to our virtual machine "overview", and copy our "public IP address", as well as our private IP address(scroll down further to "networking", and paste them onto our notepad (or write them down). 

![Create-VM-win11](https://user-images.githubusercontent.com/116504189/198414215-3579921b-409c-464a-968b-1e233777ff75.png)

![Create-VM-rd(private)](https://user-images.githubusercontent.com/116504189/198414236-b663353c-1731-47eb-84da-e7e30b64a64e.png)

THIRD SECTION: Remote Desktop Control

Now that we have our IP addresses written down, let's connect to our virtual machine! In the Windows searchbar, type "remote desktop connection".

![Create-VM-rd0](https://user-images.githubusercontent.com/116504189/198414477-2c42339b-0b20-4124-89d6-6513ef68d0d6.png)

We will now type in our PUBLIC IP address, and click "connect".

![Create-VM-rd1](https://user-images.githubusercontent.com/116504189/198414549-b8d5a9e7-9ee3-4b4e-84da-cf159f3cbab5.png)

Next, we will input our username, and password which we created in the previous section ( If you have other credentials, you will just select "use a different account).

![Create-VM-rd2](https://user-images.githubusercontent.com/116504189/198414746-eab37856-d49e-4620-adf2-1e3c6681ed0b.png)

![Create-VM-rd3](https://user-images.githubusercontent.com/116504189/198414753-70701186-72e2-4720-8462-d13b8a45fe28.png)

After entering your credentials, you will see a pop up. Simply click "yes" to connect.

![Create-VM-rd4](https://user-images.githubusercontent.com/116504189/198414837-b1da81a0-fb1b-4b20-93d0-74498b9dac80.png)

