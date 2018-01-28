# MBR Partitions

Here you can find a python script that can extract partitions information from MBR.

I added 3 files to play with and test the provided script: one mbr sector, one ebr sector and 
a complete hard disk image containing both primary and extended partitions.

To run the script simply send the file path or linux disk file (such as /dev/sda) as the first argument.

`python read-partitions-info.py mbr.img`

Please note that I didn't check all the conditions that can happen and just wanted a simple script that can work like `fdisk -l`
