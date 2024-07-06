# ROS-AI-week-2-task-1
ROS AI week 2 samrt methods internship 
task 1: install ubuntu, ROS noetic, and ROS2 foxy


## Installing ubuntu 
Ubuntu can be downloaded in virtual box or directly in windows 
Working on Ubuntu in VirtualBox and using Ubuntu as a terminal in Windows (WSL) both have their advantages and considerations. 

### A comparison between them:
1.	Isolation and System Resources:
- VirtualBox: Running Ubuntu in VirtualBox provides complete isolation from the Windows host system. It allows you to have a separate virtual machine with its own resources like CPU, memory, and disk space. This can be beneficial when you need a dedicated and independent environment for development or testing.
- WSL: Using Ubuntu as a terminal in Windows (WSL) allows you to leverage the Windows operating system's resources without the need for a separate virtual machine. It shares the same kernel as Windows, enabling faster performance and efficient resource utilization.
2.	Ease of Setup and Maintenance:
- VirtualBox: Setting up and configuring a virtual machine in VirtualBox requires additional installation steps, including downloading the Ubuntu ISO file, creating a virtual machine, and allocating necessary resources. Maintenance involves managing the virtual machine itself, including updates, backups, and snapshots.
- WSL: Ubuntu as a terminal in Windows (WSL) can be installed directly from the Microsoft Store, making the setup process relatively straightforward. Maintenance is simplified as Ubuntu runs within the Windows environment, and updates can be managed through standard Ubuntu package management tools.
3.	Integration with Windows Ecosystem:
- VirtualBox: While running Ubuntu in VirtualBox provides isolation, it may require additional configurations to enable seamless integration between the guest OS (Ubuntu) and the host OS (Windows). Features like shared folders, clipboard sharing, and USB device access may require additional setup and configuration.
- WSL: Ubuntu as a terminal in Windows (WSL) offers better integration with the Windows ecosystem. You can access Windows files directly from the Ubuntu terminal, easily share clipboard contents, and utilize Windows applications for development tasks that don't require a Linux environment.
4.	Performance:
- VirtualBox: Running Ubuntu in VirtualBox incurs some performance overhead due to the virtualization layer. Depending on the hardware resources allocated and the host system's performance, there may be a slight impact on CPU, memory, and disk performance.
- WSL: Using Ubuntu as a terminal in Windows (WSL) provides better performance as it runs directly on the Windows kernel. The performance difference between WSL and running Ubuntu natively on hardware is minimal for most development tasks.

Considering these factors, the choice between working on Ubuntu in VirtualBox and using Ubuntu as a terminal in Windows (WSL) depends on your specific requirements:
- Choose VirtualBox if you need complete isolation, independent system resources, or specific hardware configurations.
- Choose WSL if you want seamless integration with the Windows ecosystem, better performance, and easier setup and maintenance.

## Install Ubuntu terminal in Windows:
1.	Visit the website Linux WSL for Development Environment for detailed instructions [ubuntu terminal in windows](https://dev.to/wiscer/linux-wsl-for-development-environment-1ad2).
2.	The guide explains how to enable WSL on your Windows machine by going to the Windows Features settings and enabling "Windows Subsystem for Linux."
3.	After enabling WSL, you can install the Ubuntu distribution from the Microsoft Store.
4.	Once Ubuntu is installed, you can launch the Ubuntu terminal and follow the on-screen instructions to set up your username and password.

## Installing ROS Noetic
1.	Visit the ROS Noetic Installation Guide on the ROS Wiki [ROS noetic](https://wiki.ros.org/noetic/Installation/Ubuntu).
2.	The guide provides detailed instructions for installing ROS Noetic on Ubuntu. It includes steps for setting up your sources.list, adding the ROS repository keys, and installing the ROS packages.
3.	Choose the appropriate installation method based on your specific requirements.
4.	Follow the guide

## Installing ROS2 Foxy
1.	Visit the ROS2 Foxy Installation Guide. [ROS2 foxy](https://docs.ros.org/en/foxy/Installation/Ubuntu-Install-Debians.html)
2.	The guide provides instructions for installing ROS2 Foxy on different operating systems. Choose the instructions specific to your operating system.
3.	The guide covers various installation methods and provides the necessary commands to install ROS2 Foxy.
4.	Follow the guide
