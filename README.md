# CIT-220

**linux-lab.sh** - A script used to download, setup and grade the CIT-220 lab enviornment in my CIT-220 Linux System Administration classes.<br />
Copyright &copy; 2022-2023, Dr. Matthew Kisow <matthew.kisow@kisow.org>

## Tasks
- [ ] LAB01-01 - Student Install
- [ ] LAB12-02 - Disk Quotas
- [ ] LAB13-01 - (ssh)
- [ ] LAB17-01 - (lsmod)
- [ ] LAB29-01 - Chroot on Apache Server

## Installation
1. Following the instructions for your distribution, install git.
2. Using the _git clone_ command, clone **CIT-220** from this repository into your home directory.
```shell
          cd ~
          git clone https://github.com/DoctorKisow/CIT-220.git
```
3. Using the _chmod +x_ command, make the **linux-lab** script executable.
```shell
          chmod 770 linux-lab
```
4. using the _linux-lab_ command, check for script updates from the **linux-lab** using the -u switch.
```shell
          bash linux-lab -u
```
5. Using the _bash_ command, install **linux-lab** using the -i switch.
```shell
          bash linux-lab -i
```


## Script Notes
By typing _linux-lab_ with no options, or _linux-lab -h_ you can get help.

## Warning
Do not use this script in a _PRODUCTION_ enviornment with out testing and validating it first.

## License
License (GPL v3.0)

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program.  If not, see <http://www.gnu.org/licenses/>.
