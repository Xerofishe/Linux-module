# Linux-module

This is a simple Linux kernel module written in C programming language that lists all the currently running processes in the system and their corresponding states.

1. Execute the 'make' command to create the .ko file:
```
make
```
2. Insert module into the kernel using insmod:
```
sudo insmod processmod.ko
```
3. To check if the kernel module is inserted into the kernel at runtime execute the lsmod command:
```
lsmod
```
4. The module prints its output to the kernel log. You can view this using the dmesg command:
```
sudo dmesg
```
