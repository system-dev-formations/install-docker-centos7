# Install-docker-centos7
## Pre-requisite
```shell script
 git clone  https://github.com/system-dev-formations/install-docker-centos7.git
 cd install-docker-centos7
```
Install python3
```shell script
sudo yum -y install -y python3
```
 
## Set up a python virtualenv, and install ansible
```shell script
  #  directory 
  python3 -m venv venv  # install virtualenv module dans la directory venv
  source venv/bin/activate # activate the python virtualenv
  pip3 install wheel  # install pip package wheel for permission usage
  pip3 install ansible # install ansible
  ansible --version   # Check version number
```