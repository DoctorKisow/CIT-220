# CIT-220

**linux-lab.sh** - A script used to download, setup and grade the CIT-220 lab enviornment for my _CIT-220 Linux System Administration_ classes.<br />
Copyright &copy; 2022-2023, Dr. Matthew Kisow <mkisow@ccac.edu>

## Tasks
- [ ] LAB01-01 - Student Install
- [ ] LAB07-01 - RESET AND GRADING MODULE
- [ ] LAB13-01 - (ssh)
- [ ] LAB17-01 - (lsmod)
- [ ] LAB23-01 - Network Troubleshooting
- [ ] LAB29-01 - Chroot on Apache Server

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
License (GPL v3.0)

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program.  If not, see <http://www.gnu.org/licenses/>.
