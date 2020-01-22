# Overview
This repo is to test individual ansible setups. I will not be creating whole environments here and each test may repeat code contained within other test folders.

## Testing Platform
My testing platform is GCP hosted Ubuntu:18.04 minimal.

## Software Versions
I will be using either the default ansible version for Ubuntu:18.04 or the latest stable version accessible by running:

```bash
sudo apt install software-properties-common -y
sudo apt-add-repository --yes --update ppa:ansible/ansible
sudo apt update
sudo apt install ansible -y
```
