# Introduction

This document will provide an overview of useful commands in Linux/Bash. If an example is required then it will provided below the command.

| **File** | **Example Usage** | **Definition** |
|:-----:|:----:|:-----:|
|```fstab```  | /dev/xfgh /dev/new | This will attach a drive so the OS recognises it, in the example the drive name |



| **Command** | **Example Usage** | **Definition** |
|:-----------:|:-----------------:|:--------------:|
| ```mksf.ext4 ``` | ```mksf.ext4 /dev/xfgh | This will apply 4096 byte file system to an attached drive |

```fstab``` (ubuntu)
This is a file that can be located in the /etc folder, this is useful when mounting permanent drives to the system. Typically it will form the format:
(device_name) (mounting_location) 

It is important to remember that the new drive should have file system in order to be utilised correctly by the operating system.
To do this use the following command ```mksf.ext4 (device_name)```,


