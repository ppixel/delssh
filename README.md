# DelSSH
DelSSH is a small script for the Linux Bash with that you can delete an entry from your SSH known_hosts. Right now there is no more functionality, but I plan to add more features. For example I want to implement a DNS resolve, delete entries from other users (sudo required),... .

## Requirements
The following programs are required:
- sed
- grep

## Installation
Simply download the file delss and put it in a folder from your $PATH variable.

## Usage
```bash
delssh -e <hostname or ip> [-dhnv]
```
Please not, that -n dont work yet and you can only put a single hostname or IP-Address yet.


## Tested
I wrote and tested that script with following components:
- OS: CentOS Stream release 9
- Bash: 5.1.8(1)-release (x86_64-redhat-linux-gnu)
- Sed: (GNU sed) 4.8
- Grep: (GNU grep) 3.6