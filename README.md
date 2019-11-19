These are just SafeMode9 binaries, compiled from the original [GodMode9](https://github.com/d0k3/GodMode9) code.

If you want SafeMode9 downloads, please head to the Releases tab, or click [here](https://github.com/jbmagination/SafeMode9/releases).

# How to compile SafeMode9 yourself

## Linux (preferred)
If you don't use Linux, you can use distributions like [Arch Linux](https://archlinux.org) or [Ubuntu](https://ubuntu.com). They're both entirely free.
1. Install the latest version of Python [here](https://python.org)
2. Install [devkitPRO pacman](https://devkitpro.org/wiki/devkitPro_pacman) (read carefully)
3. Run either `sudo pacman -S 3ds-dev` or `sudo dkp-pacman -S 3ds-dev`
4. Run either `sudo pacman -S devkit-env` or `sudo dkp-pacman -S devkit-env`
5. Download [p7zip](https://https://sourceforge.net/projects/p7zip/files/p7zip/16.02/p7zip_16.02_src_all.tar.bz2/download) and extract the .tar.bz2
6. In the terminal, go to the p7zip directory and run `make all`
7. 
