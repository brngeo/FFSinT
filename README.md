
# fastfetch setup in terminal

Fastfetch is a fast, feature-rich, and performance-oriented command-line system information tool written primarily in C. It serves as a modern, maintained alternative to Neofetch, which is no longer actively updated, offering significantly faster execution times while displaying hardware and software details in a visually appealing format.


## Installation

To deploy this project run

```bash
  sudo apt install fastfetch
```
Path: \
/home/user/.config/fastfetch/ \
Go to the fastfetch directory
```bash
  cd /home/user/.config/fastfetch/
```
Backup the existing file
```bash
  mv config.jsonc config.jsonc.bak
```

Download the FFSinT repository
```bash
  sudo git clone https://github.com/fliqlo/FFSinT/
```
Locate the FFSinT folder, copy ascii.txt and config.jsonc \
to the fastfetch directory

```bash
  cd /home/user/(FFSinT path)
```
```bash
  cp ascii.txt && cp config.jsonc /home/user/.config/fastfetch/
```
Go to the .bashrc file and edit it and \
put this code in the last line 
```bash
  cd /home/user/
  ll
  micro .bashrc
```
```bash
  fastfetch -c "/home/user/.config/fastfetch/config.jsonc"
```
Don't forget to install a nerd font or meslo font. \
Your terminal is good to go. ;)
## Authors

- [@brayan](https://facebook.com/brn.geo04)
