# Experiment 1st: common-commands-in-Linux
group 6
## Purpose of the experiment
1.
## Experimental equipment
1.
## Experiment pre-study requirements
1.
## Experimental content
1.
## Experimental Procedure
### Use of the Linux operating system based on virtual machines
1.
### Use of commands related to files and directories
1.
### Use of commands related to Disk Management and maintenance
1.
### Use of system administration and setting commands
1.
### Use of network-related commands
#### 1.Displays information about the current network
Run the following command

`ifconfig`

The information of the current network can be displayed, and the operation result is shown in the figure

![img](./assets/5.5/info.png)

If the prompt as shown in the figure appears, you can run the command shown in the diagram to install the package and try again

`sudo apt install net-tools`

![img](./assets/5.5/install.png)

### 2.Set the IP address
Run the following command

`ifconfig enc33 192.168.1.10`

You can set the IP address of ENC33 to 192.168.1.10
If the following prompts appear

![img](./assets/5.5/error.png)

you can add sudo before the command to elevate the privilege, that is, run

`sudo ifconfig enc33 192.168.1.10`

After operation, the IP change is observable

![img](./assets/5.5/ip.png)

### Use of the Compress Backup command
1.
## Questions
1.
