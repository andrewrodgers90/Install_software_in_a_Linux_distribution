# Install software in a Linux distribution

## Scenario

Your role as a security analyst requires that you have the Suricata and tcpdump network security applications installed on your system.

In this scenario, you have to install, uninstall, and reinstall these applications on your Linux Bash shell. You also need to confirm that you’ve installed them correctly.

Here’s how you'll do this: First, you’ll confirm that APT is installed on your Linux Bash shell. Next, you’ll use APT to install the Suricata application and confirm that it is installed. Then, you’ll uninstall the Suricata application and confirm this as well. Next, you’ll install the tcpdump application and list the applications currently installed. Finally, you’ll reinstall the Suricata application and confirm that both applications are installed.

### Task 1: Ensure that APT is installed
![img_1](https://github.com/andrewrodgers90/Install_software_in_a_Linux_distribution/assets/132149730/49da8f4f-4656-4b4b-b322-1dd4ee393b71)

### Task 2: Install and unistall the Suricata application

#### i. Use the APT package manager to install the Suricate Application
![img_2](https://github.com/andrewrodgers90/Install_software_in_a_Linux_distribution/assets/132149730/3da75341-32f2-4e89-8bd5-e091a3360231)
<br>
The 'sudo' command is used here to temporarily elevate user privileges, granting permission to download Suricata.

#### ii. Verify that Suricata is installed
![img_4](https://github.com/andrewrodgers90/Install_software_in_a_Linux_distribution/assets/132149730/54902637-c0f9-4d97-a308-624b503d4c4c)
<br>
Running the 'suricata' command lists basic version and usage information. 

#### iii. Use the APT package manager to uninstall Suricata
![img_5](https://github.com/andrewrodgers90/Install_software_in_a_Linux_distribution/assets/132149730/206088a6-0f30-4251-a0e3-12ec9ee0fcff)

#### iv. Verify that Suricata has been uninstalled
![img_6](https://github.com/andrewrodgers90/Install_software_in_a_Linux_distribution/assets/132149730/730f335d-df03-4bf1-971a-77f301bcce9e)
<br>
This message indicates that Suricata can't be found anymore.

### Task 3: Install the tcpdump application
![img_7](https://github.com/andrewrodgers90/Install_software_in_a_Linux_distribution/assets/132149730/f1ec849f-2ea6-4b77-89d0-7b8f55bdf2d7)

### Task 4: List the installed applications
![img_8](https://github.com/andrewrodgers90/Install_software_in_a_Linux_distribution/assets/132149730/0bc9ca3b-7a8c-4076-b5d9-4fe14cb1fa8d)
<br>
This command produces a list of installed applications. It also includes applications that were not explicitly installed by the user.
<br>
<br>
![img_9](https://github.com/andrewrodgers90/Install_software_in_a_Linux_distribution/assets/132149730/f8ec232b-8832-46a0-8914-31e4a576cc44)
<br>
The resulting output lists 'tcpdump' as an installed program.

### Task 5: Reinstall Suricata and confirm both applications are installed
![img_2](https://github.com/andrewrodgers90/Install_software_in_a_Linux_distribution/assets/132149730/3da75341-32f2-4e89-8bd5-e091a3360231)
<br>
![img_10](https://github.com/andrewrodgers90/Install_software_in_a_Linux_distribution/assets/132149730/2a8ab2ae-e4fa-4c67-b405-a10455e74ce1)
<br>
The output of the command 'apt list --installed' shows that both suricata and tcpdump are now installed.
