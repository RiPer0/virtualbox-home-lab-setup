# virtualbox-home-lab-setup
This repository helps setup your VirtualBox and create virtual machines for home labs!

## Step 1 - Download Virtual Box (VB) 
Thanks to technology of VirtualBox we can create more virtual machines on our computer with minimal configuration.  
More information about VirtualBox [here](https://www.geeksforgeeks.org/cloud-computing/what-is-virtualbox/)  
Now it's time to install our [VirtualBox](https://www.virtualbox.org/wiki/Downloads) there you can find links for you operating system I will be using windows for the guide. 

<img src="https://github.com/RiPer0/virtualbox-home-lab-setup/blob/main/Assets/ss1_clean.jpg">  
After download, installing it is fairly easy just continue with installation by clicking next, then install and you are all set with VB for now.  
<img src="https://github.com/RiPer0/virtualbox-home-lab-setup/blob/main/Assets/ss2_clean.jpg">  

## Step 2 - ISO images Linux/Windows
Now for ISO images most popular operating systems are Linux and Windows so we will focus on those:
 - Linux have a lot of distributions so we will cover only Ubuntu latest version but process of installation different distros look similar - ISO image of [Ubuntu](https://ubuntu.com/download/desktop)  
<img src="https://github.com/RiPer0/virtualbox-home-lab-setup/blob/main/Assets/ss3_clean.jpg">

 - Windows have a different type of installation so firstly we need to download [Media Creation Tool](https://www.microsoft.com/en-us/software-download/windows10)  
<img src="https://github.com/RiPer0/virtualbox-home-lab-setup/blob/main/Assets/ss4_clean.jpg">  
Now we can launch the application and choose ISO image and then which version of Windows to choose.
<img src="https://github.com/RiPer0/virtualbox-home-lab-setup/blob/main/Assets/ss5_clean.jpg">  
I will choose Windows 10 after that we just continue installation and we should get our ISO image.

## Step 3 - Creating virtual machines (VM) on VB
Now we can start your VB and start to create our first virtual machines!

 We click new in main page at top left then we should be see this window.    
 <img src="https://github.com/RiPer0/virtualbox-home-lab-setup/blob/main/Assets/ss6_clean.jpg">  
  Then you can see few options as VM name or folder we will focus on ISO image because you can name your VM however you like.  
  I will choose for my first system a Windows, click arrow on right side and then click other and search for Windows ISO and select it, be sure to **check Proceed with Unattended Installation.**  
  
  <img src="https://github.com/RiPer0/virtualbox-home-lab-setup/blob/main/Assets/ss7_clean.jpg">  
  Now we move to OS installation where we need to specify your user and password.
  <img src="https://github.com/RiPer0/virtualbox-home-lab-setup/blob/main/Assets/ss8_clean.jpg">   
  
  Next is hardware of machines and disc space **check Requirements tab below for that information.**  
  <img src="https://github.com/RiPer0/virtualbox-home-lab-setup/blob/main/Assets/ss9_clean.jpg">  
  and for disc space  
  <img src="https://github.com/RiPer0/virtualbox-home-lab-setup/blob/main/Assets/ss10_clean.jpg">  
  Press finish and you are all set with VM let VirtualBox take care of installation for you.
  ## Step 4 - Enjoy your home lab!
  That guide shows only creation of VM using windows because ubuntu looks the same with changes to hardware part.  
  Hope you liked my guide and have fun creating your home lab!
  
## Requirements
Set your VM with **recommended requirements** when creating new machines for better performance.  
Ubuntu: https://phoenixnap.com/kb/ubuntu-system-requirements  
Windows: https://support.microsoft.com/en-us/windows/experience/windows-10-system-requirements  

  
