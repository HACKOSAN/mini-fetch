# mini-fetch

### A very minimal fetch program written in C 

##

# Requirements

## 1. git 
## 2. make => base-devel

## 3. any nerd font available at *https://www.nerdfonts.com*
# Installation
```sh
git clone https://github.com/HACKOSAN/mini-fetch.git

mv mini-fetch .config/

cd .config/mini-fetch

sudo make 

sudo mv minifetch /bin 

alias minifetch='minifetch -c -b -n'
```
# Usage

```sh
❯ minifetch --help
Usage: minifetch
        -c --color       : enables colors
        -b --colorbars   : shows color bars, best used with -c
        -f --foreground  : use foreground colors for color bars
        -n --nerd        : use nerd font icons
        -h --12hour      : use 12 hour time instead of 24 hour time
        -d --noday       : don't show day of the week in time (e.g Thu)
        -o --filesystems : show all mounted file systems instead of just root



```

# Preview
```sh
❯ minifetch
 distro ~ Ubuntu 20.04.4 LTS
     os ~ Linux x86_64 5.10.16.3-microsoft-standard-WSL2
   user ~ hacko
   host ~ Mohammed-MSI
  shell ~ bash
 locale ~ C.UTF-8
    tty ~ /dev/pts/0
   date ~ Thu 18.08.2022
   time ~ 08.28.12
battery ~ BAT1 Discharging 81%
 uptime ~ 3m 32s
   proc ~ 183
    ram ~ 164.87M / 12.25G
   swap ~ 0 / 4.00G
   root ~ /dev/sdb
  inode ~ 84.33K / 16.00M
  block ~ 2.28G / 250.98G
```
### i didn't add icons and color bars for minimalism 
### you can add them by excuting "*minifetch -c -b -n*"

## and thats all !!


