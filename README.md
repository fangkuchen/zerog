This repository has been archived because I switched back to Arch. Feel free to fork the script if it is useful to you.

---

# ZEROG
Simple Parabola GNU/Linux-libre post-install script

## Dependencies

This script is written for the OpenRC version of Parabola. It assumes that
the nonsystemd repo is already enabled and elogind/libelogind is installed.

## Usage

Install Parabola on your system then run:

```
    curl -O https://raw.githubusercontent.com/m4k3l/zerog/master/zerog
    chmod +x ./zerog
    sudo ./zerog
```

Make sure your pacman mirrors are working before running the script.

## Customization

You can change the source for the progs.list, the dotfiles and suckless repo by
editing the corresponding variables at the beginning of the script


## Troubleshooting

The script will create a logfile (/tmp/zerog.log). In case you run into any
trouble you will find the stderror output of whatever command failed as well as
the names of any programs that could not be installed there.

## Credits

This script is inspired by [LARBS](https://larbs.xyz)
