# WSL_Setup_guide
Easy and well defined repo to show how to setup WSL in win 10/win 11 

Step 1

Open Poweshell with admin rights
![image](https://user-images.githubusercontent.com/41202066/175859763-221f4c46-f83c-4b6c-83ce-3a26eacbee3e.png)

Paste the commands shown below one by one:

Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux
![image](https://user-images.githubusercontent.com/41202066/175860069-ba164b62-bd86-477e-98a8-67f574588980.png)

Then reboot the pc

Step 2:

In order to install Ubuntu in a non windows drive(Other than C:/ drive), Open Powershell from a folder as shown
![image](https://user-images.githubusercontent.com/41202066/175860514-6719e2cb-164b-4c04-b04c-3770b14dcae1.png)


To install various distros:
Ubuntu 20.04 - https://aka.ms/wslubuntu2004
Ubuntu 20.04 ARM - https://aka.ms/wslubuntu2004arm
Ubuntu 18.04 - https://aka.ms/wsl-ubuntu-1804
Ubuntu 18.04 ARM - https://aka.ms/wsl-ubuntu-1804-arm
Ubuntu 16.04 - https://aka.ms/wsl-ubuntu-1604

I am installing Ubuntu 20.04

Invoke-WebRequest -Uri https://aka.ms/wslubuntu2004 -OutFile Ubuntu.appx -UseBasicParsing
![image](https://user-images.githubusercontent.com/41202066/175860263-0e5f373d-2eb9-4024-956c-5c0001d1504a.png)

This will download Ubuntu 20.04 distro and save it under the name “Ubuntu.appx”

