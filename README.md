## Installation
1. Delete the default motd
```
sudo rm /etc/update-motd.d/*
```
2. Run the motd install script: 
```
bash <(curl -fsSL https://raw.githubusercontent.com/distillium/motd/main/install-motd.sh](https://raw.githubusercontent.com/blxckhundred/motd-fork/refs/heads/main/install-motd.sh)
```
if sudo:
```
curl -fsSL [https://raw.githubusercontent.com/distillium/motd/main/install-motd.sh](https://raw.githubusercontent.com/distillium/motd/main/install-motd.sh](https://raw.githubusercontent.com/blxckhundred/motd-fork/refs/heads/main/install-motd.sh) | sudo bash
```

## Commands

- `rw-motd` — manually display the current MOTD.

- `rw-motd-set` — open a menu to enable/disable MOTD info blocks.
