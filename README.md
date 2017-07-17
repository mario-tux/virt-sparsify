# Ubuntu tools
This is a docker container with tools not available in Mac OS X and scripts to execute them.

## Installation
```
docker pull vitkhab/ubuntu-tools
git clone git@github.com:vitkhab/docker-ubuntu-tools.git
ln -s $(realpath docker-ubuntu-tools/scripts/*) /usr/local/bin
```

## Usage
### virt-sparsify
#### Example
```
virt-sparsify --convert qcow2 --compress input.raw output.img
```
