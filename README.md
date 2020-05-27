# Docker-CheatSheet

A CheatSheet for Docker 

## Installation
```sh
 
 - Install few packages which are required beforehand

   sudo apt install apt-transport-https ca-certificates curl software-properties-common

 - Add GPG key 

   curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -

 - Add Docker repository to apt sources

   sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu bionic stable"

 - Update your existing list of packages
   
   sudo apt update

 - Install Docker-ce

   sudo apt install docker-ce

 - Start Docker Process

   sudo systemctl status docker 

```