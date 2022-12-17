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

## and thats all !!


