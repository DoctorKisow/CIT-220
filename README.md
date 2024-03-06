# CIT-220

**linux-lab.sh** - A script used to download, setup and grade the CIT-220 lab enviornment for my _CIT-220 Linux System Administration_ classes.<br />
Copyright &copy; (2022-2023) Dr. Matthew Kisow. All rights reserved.</br>
Dr. Matthew Kisow <mkisow@ccac.edu>

## Tasks
- [ ] LAB01-01 - Student Install
- [ ] LAB10-01 - SFTP in CHROOT JAIL (SEE LAB 29)
- [ ] LAB13-01 - (ssh) pr. 364-365, TCP WRAPPERS
- [ ] LAB17-01 - (lsmod)
- [ ] LAB23-01 - Network Troubleshooting
- [ ] LAB29-01 - Chroot on Apache Server
- [x] RESET MODULES FOR ALL LABS
- [ ] GRADING MODULES FOR ALL LABS

## Installation
1. Following the instructions for your distribution, install git.
2. Using the _mkdir_ command, create a directory called */Lab Files* at the root of the drive.
```shell
          cd /
          mkdir "/Lab Files"
```
3. Using the _curl_ command, download the **linux-lab** script executable.
```shell
         curl -s -L "https://github.com/DoctorKisow/CIT-220/raw/main/linux-labs" >> linux-labs
```
4. Using the _chmod_ command, change the permissions of the **linux-labs** script to _750_.
```shell
          chmod 750 linux-lab

```
5. Using the _linux-lab_ command, install the labs by issuing the **linux-lab** command using the _-i_ switch.
```shell
          bash linux-lab -i
```
6. Using the _chown_ command, change the ownership of the **linux-labs** script to _root:labusers1_.
```shell
          chown root:labusers1 linux-lab
```


## Script Notes
By typing _linux-lab_ with no options, or _linux-lab -h_ you can get help.

## Warning
This is a learning and teaching tool _ONLY_ and should _NOT_ be used in a _PRODUCTION_ enviornment!

## License
This work is licensed under the Creative Commons Attribution-NoDerivatives 4.0 International License. To view a copy of this license, visit http://creativecommons.org/licenses/by-nd/4.0/ or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.
