# Threader3000 
### Multi-threaded Python Port Scanner with Nmap integration for use on Linux or Windows

Threader3000 is a script written in Python3 that allows multi-threaded port scanning.  The program is interactive and simply requires you to run it to begin.  Once started, you will be asked to input an IP address or a FQDN as Threader3000 does resolve hostnames.  A full port scan can take as little as 15 seconds, but at max should take less than 1 minute 30 seconds depending on your internet connection.

## Requirements
Python3 must be installed on your system in order to function
Pip3 for installation via PyPi repository

## Installation
**Installation via Pip**

```bash 
pip3 install threader3000
```

Run by typing:
```bash
threader3000
```

**Install via Git**

```bash
git clone https://github.com/dievus/threader3000.git #to save the program to your machine, or utilize the download option
```

You can add Threader3000 to run from any directory by adding a symbolic link:

```bash
sudo ln -s $(pwd)/threader3000.py /usr/local/bin/threader3000
```


This tool, when used correctly, helped me pass the OSCP exam. The OSCP is all about time management and enumeration. I give you a tool that is quick and conducts good single target scanning.  It's up to you to use it.

**Can I make pull requests with changes that I think are best for Threader3000?**

You can, but these will likely be denied. Threader3000 is a tool I wrote to meet my needs in the field, and I've simply shared it with everyone. If you find an issue that causes significant issues, please report it, however changes to code on how a user thinks it should be better written or how the user feels it should function will be denied.  
