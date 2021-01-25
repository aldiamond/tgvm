# tgvm
A simple terragrunt version manager for Linux.

All bash. Does not required elivated privileges. Just make sure `$HOME/bin` is on your path.

### Install

There is only one requirement: **bash**.


Run this in the terminal:

```
curl https://raw.githubusercontent.com/aldiamond/tgvm/main/setup | bash
```

### Usage

```
>tgvm --help

Simple Linux terragrunt version manager.
 
Usage:
    tfvm version                display current running version of terragrunt
    tfvm list                   list installed versions of terragrunt
    tfvm install {{version}}    install terragrunt version
    tfvm set {{version}}        set terragrunt version
```
