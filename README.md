# Install and Run a Virtual Machine

## Purpose

This project is to demonstrate my knowlege of Virtual Machines(VMs). VMs are an important part of work in cybersecurity. 
VMs allow the user to create a virtual computer seperate from their personal machine. This can allow the user to run
different operating systems, open possible malicious content or conduct ethical hacking while remaining anonymous. 

## Steps

1. Download and install VM software
When doing my research on which software to use, I found the Oracle Virtual Box. Virtual Box is open source and free.
I downloaded Virtual Box directly from the Oracle website.
![Screenshot (1)](https://github.com/user-attachments/assets/8ab02630-16e7-4ded-b14b-52919fd674a4)
Once I downloaded the software, I installed it on my personal
computer using the Setup Wizard. I used all default settings for ease of use.  
![Screenshot (2)](https://github.com/user-attachments/assets/20834593-54c0-416a-b560-677b7135033f)

2. Dowload Operating System Installer
When booting a virtual machine, they are not pre-equipped with an operating system. This requires you to download an operating system
and install it onto the VM. I conducted research and decided to use Kali Linux on my first VM. My purpose for using a VM is for cybersecurity.
Kali is several cybersecurity tools pre-installed. These include Metasploit, Nmap, Burpsuite, Hydra and others. I went to Kali.org and
downloaded the Kali Linux installer. I originally picked the 64-bit for the increase performance. I had to later switch to using the 32-bit due to compatiblity issues.

3. Create and configure your Virtual Machine
Open Oracle Virtual Box. Once open, click "Add" to create a new VM.
![Screenshot (6)](https://github.com/user-attachments/assets/17ee921b-8175-496f-acad-a7daf0bb1687)
Clicking "Add" will open up the window to name and configure your VM. In the name section you will decide what to name your machine.
In the type box, you will find your operating system type. I used Linux and picked "Linux" in the section.
Under the subtype, you will pick the operating system distribution. Kali Linux was not an option. I selected Ubuntu because Kali was not an option.
Kali is based on Debian and Ubuntu. The next section is the version. I used the Ubuntu 32-bit as my version.
![Screenshot (7)](https://github.com/user-attachments/assets/8dd1c507-d088-4de5-aa06-ef37ef0318d4)
Once this is complete, a window will open to configure the hardware. The green area is what is available from the computer to use to create the VM.
For the amount of "Base Memory", my system had approximately I had approximately 2000 MB available. Since I plan create a second machine to hack into in
the future, I only used half of the memory available for this machine. The next section is the number of CPUs to use. My computer has 4 cores but only allows
for the use of 2. Again, since I plan on using a second VM for hacking, I only used 1 CPU/core.
![Screenshot (8)](https://github.com/user-attachments/assets/85737d9a-b8b0-4784-b000-0adb130f9b86)
Completing this section then leads you to the disk size. I did not expect to need more the 10GB of space. I moved the slider to allow for the 10GB of disk space.
![Screenshot (9)](https://github.com/user-attachments/assets/b662f3e3-4d0f-4d3a-a554-cb00c90a8432)
Once completing this, your VM has been created.

4. Install the Operating System
Your VM will be listed on the left side of the window. Click and highlight the VM you wish to use and hit start. This will open a prompt indicating your VM does not have an operating system. Click to indicate you wish to install an OS. This will open another small window which allows you to search for a file. Click the folder button and search for the OS installer file. Double-click the installer file and click to run the install. Follow the installer and pick the setting according to your preference. This will include your location, language, username and password, etc. 
![Screenshot (12)](https://github.com/user-attachments/assets/b7aabb72-5bba-46c7-bd85-7d38224b8e04)
![Screenshot (33)](https://github.com/user-attachments/assets/e2ada319-82a6-4a30-9eff-b255787e2319)

5. Use your Virtual Machine
After setup is complete, you can login to your machine.
![Screenshot (38)](https://github.com/user-attachments/assets/a1ffef2e-65ec-4bd4-b0c3-d04688a9a3d4)
![Screenshot (39)](https://github.com/user-attachments/assets/f195263f-5cc3-4c94-8cc0-18c3489546a8)

## Issues

During my creation of my virtual machine, I did run into a few issues, which became learning points. First, I initially downloaded the 64-bit version of Kali. I did to get the better performance. Once I attempted to install Kali on the VM, the setup would crash. I conducted research and found a setting needed to be changed in the BIOS. I went to change the setting in the BIOS and found it was only an Intel CPU setting. I found my CPU was an AMD CPU. I downloaded a 32-bit version of Kali and found it worked. I continued to research how to troubleshoot this issue. I found the Hypervision feature needed to be turned off and was off on my system. I checked to see if my processor was a 64-bit processor and it was. At this time, I have not found a solution to use the 64-bit version but will continue to research and update this project. 

During my research of the CPU, I found my laptop only had 4GB of RAM. I found this was not ideal for running a VM and nearly impossible to run 2 VMs for simulated attacks. 

