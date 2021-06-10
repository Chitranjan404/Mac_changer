# Mac_changer
This software, written in Python 3, can modify the MAC address of your Linux device. Since it is changing mac address of a device, it requires sudo privileges to run.

# command to use the program-
- to bring up the help interface- python(or pyhton 3 in some cases) mac_changer --help(or -h)
- to change the mac address- pyhton mac_changer --interface(or -i) eth0/wlan0 --mac(or -m) 00:44:22:44:22:88(any mac of your choice).

# Key points.
1. Secure; Because the input is accepted in the form of a list, no input other than the mac and interface may be executed, preventing someone with ill intentions from executing a python command in the input.
2. A help screen has been created expressly to assist the user in writing the command. 
3. Instead of presenting a traceback when a user enters an incorrect mac or interface, it prompts the user to enter the right mac or interface.
4. Code that is easy to read and understand.
5. All interfaces, including eth0 and wlan0, can have their Mac addresses changed.
6. It was written using functions so that it may be reused multiple times.
7. A help interface has been created to assist the user in learning how to write the command for the first time.
