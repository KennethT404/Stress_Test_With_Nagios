# Stress_Test_With_Nagios

Goal is to be able to examine stress tests on an EC2 on Nagios. Configuring nagios to monitor the EC2 will be done with anisble 

For the full details on how to do so, look [here](https://github.com/KennethT404/Stress_Test_With_Nagios/blob/main/Stress%20Monitoring%20with%20Nagios%20on%20EC2.pdf)

[Nagios](https://www.nagios.org/) is a monitoring tool that gives visibility to the statistics of a machine. Statisics being CPU usage, RAM usage, and Storage usage. This particularly popular with server monitoring. 

For this tutorial, I used nagios to monitor an EC2. I also conducted stress tests to demonstrrate how it would look on the Nagios UI when a part of your machine is under heavy load. 

Ansible was used to add the machine I wanted to monitor to Nagios and the Nagios UI. Ansible is an open source provisioning software that allows for setups in unix-like machiens in a single yaml file rather than having to execute a myriad of commands and using different tools to do the same thing an ansible playbook file can accomplish.
