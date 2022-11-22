# Upgrade WSL Ubuntu 20.04 to 22.04 LTS


RAW Sequence - TODO

```shell

sudo apt update && sudo apt upgrade

sudo apt autoremove

sudo apt dist-upgrade

sudo apt install update-manager-core 

grep -v ^# /etc/update-manager/release-upgrades # Ensure Prompt=lts 

sudo apt install update-manager-core

sudo do-release-upgrade -d

```
