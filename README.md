### BreadcrumbsROS-Installation-based-on-Virtual-Machine

## I. Download VirtualBox
Download Ubuntu Desktop from the official web site (https://ubuntu.com/download/desktop).

First, go to the official web site and click **'check out our alternative downloads'**.

![Image text](https://github.com/cyiwen316/ROS-Installation-based-on-Virtual-Machine/blob/main/Image/Ubuntu20.04-1.png)

Then, go down and click **'Ubuntu 20.04 LTS (Focal Fossa)'**.

![Image text](https://github.com/cyiwen316/ROS-Installation-based-on-Virtual-Machine/blob/main/Image/Ubuntu20.04-3.png)

Finally, 


# Why VirtualBox?
When using a traditional you need to install the operating system on a physical machine for evaluating software that cannot be installed on your current operating system. Oracle VirtualBox is what you need in this case, instead of reinstalling software on your physical machine. VirtualBox is designed to run virtual machines on your physical machine without reinstalling your OS that is running on a physical machine. One more VirtualBox advantage is that this product can be installed for free.

A virtual machine (VM) works much like a physical one. An OS and applications installed inside a VM “think” that they are running on a regular physical machine since emulated hardware is used for running VMs on VirtualBox. Virtual machines are isolated from each other and from the host operating system. Thus, you can perform your tests in isolated virtual machines without any concerns of damaging your host operating system or other virtual machines.

VirtualBox supports a long list of host and guest operating systems. A host OS is the operating system installed on a physical machine, on which VirtualBox is installed. A guest OS is an operating system installed on a virtual machine running inside VirtualBox. VirtualBox can be installed on Windows, Linux, macOS, Solaris, and FreeBSD. On VirtualBox you can run VMs with Windows, Linux, macOS, Solaris, FreeBSD, Novell Netware, and other operating systems.

Go to the official web site (Link: https://www.virtualbox.org/wiki/Downloads) to download the VirtualBox installer for your operating system. See in the figure below:

![Image text](https://github.com/cyiwen316/Virtual-Machine-Installation/blob/main/Image/VirtualBox.png)

# Run the installer and define the installation options

1. Run the VirtualBox installer. The installation wizard that has a GUI (graphical user interface) should appear.
   
2. Select the manner in which you want features to be installed, clicking on the installation directory and installed components—you can leave the default values. Then tick the checkboxes near shortcut options and file associations.

3. Confirm installation of VirtualBox network interfaces (click Yes).

4. On the Ready to Install Screen, hit Install to start the installation process.

5. After finishing installation, you can tick the checkbox for starting VirtualBox after installation.

# Deploying a New VM
Once you have installed VirtualBox, open the application. You can see the graphical user interface of VirtualBox which is unified for all supported host operating systems. You can also use the command line interface and VBoxManage if needed. In the current example VirtualBox is set up on Windows.

# Creating a Virtual Machine
Click **Machine** > **New** or hit the icon with the blue star to create a new virtual machine in VirtualBox GUI.

![Image text](https://github.com/cyiwen316/ROS-Installation-based-on-Virtual-Machine/blob/main/How-to-setup-VirtualBox-%E2%80%93-Creating-a-new-VM-1.webp)

Specify name, Machine Folder (to save),Type and version for your virtual machine  and click on **Next**.

![Image text](https://github.com/cyiwen316/ROS-Installation-based-on-Virtual-Machine/blob/main/Image/5-12.png)

Here, we have to choose the base memory based on your host system RAM size. It is highly recommended to not choose less than 1GB (if possibly choose more than _25GB_).specify RAM _2048_ and click on **Next**.

![Image text](https://github.com/cyiwen316/ROS-Installation-based-on-Virtual-Machine/blob/main/Image/6-12.png)

> [!CAUTION]
Ubuntu recommends at least 25GB of free storage for smooth running.




















