# BASH Scripting Lab – Bash Script to Test Network Connections

## Objective

The objective of this Bash shell scripting lab is to develop practical skills in network troubleshooting and automation using Bash scripting. By creating a network connectivity check script, you learn to automate repetitive tasks, analyse network issues, and apply logical conditions for decision-making.

### Job Skills Learned

- Linux System Administration
- Bash Shell Scripting
- Network Troubleshooting and Analysis
- Automation and Efficiency


### Tools Used

- Linux Terminal Command Line Interface (CLI)
- Bash Shell
- Networking Commands: ping, ifconfig
- VMware Tools: Linux VM

*ref: Diagram:
![image](https://github.com/user-attachments/assets/d0c59b9e-c69b-49e7-b57a-3a9b8727056c)
 


### STEPS

This Bash script checks the network connectivity to a specified IP address or hostname using the ping command. The objective of the script is to verify network connectivity by pinging a target IP address or hostname (provided as an argument). It sends 3 ping requests and checks if there is 100% packet loss to determine if the target is unreachable.
![image](https://github.com/user-attachments/assets/4003b486-b396-4700-9b60-f84f95c01642)
 

## How It Works:
1.	The script stores the result of ping -c 3 $1 in the output variable, where $1 is the first argument passed to the script (an IP address or hostname).
2.	It checks if the output contains the phrase "100% packet loss".
o	If true, it prints "The network connection to <target> is not working."
o	Otherwise, it prints "The network connection to <target> is working."
## Example Usage:
![image](https://github.com/user-attachments/assets/307f6bf3-a73f-4878-bbb7-59c80ab9d38e)
![image](https://github.com/user-attachments/assets/5d9224b5-adc3-4ac9-8012-e8d351682f40)

 
## Practical Application:
•	Troubleshooting network connectivity issues
•	Quickly verifying the reachability of critical servers or network devices.
![image](https://github.com/user-attachments/assets/c4d7b0bd-dd64-405b-9f02-578f153b0333)


 
