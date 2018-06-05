# Largefile

## Download
* https://git-lfs.github.com/

## Install
* https://github.com/git-lfs/git-lfs/wiki/Installation

### Ubuntu
Similar to Debian 7, Ubuntu 12 and similar Wheezy versions need to have a PPA repo installed to get git >= 1.8.2  

```sudo apt-get install software-properties-common``` to install add-apt-repository  
(or ```sudo apt-get install python-software-properties``` if you are on Ubuntu <= 12.04)  

```
sudo add-apt-repository ppa:git-core/ppa
```

The curl script below calls apt-get update, if you aren't using it, don't forget to call apt-get update before installing git-lfs.  

```
curl -s https://packagecloud.io/install/repositories/github/git-lfs/script.deb.sh | sudo bash
sudo apt-get install git-lfs
git lfs install
```
