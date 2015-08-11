# Ubuntu-14.04-x64-server-setup
steps to rolling out ubuntu 14.04 on digital ocean

## Extend SSH Idle TimeOut
#### On Server: /etc/ssh/sshd_config
```
ClientAliveInterval 30
TCPKeepAlive yes
ClientAliveCountMax 99999
```
#### On Client ~/.ssh/config
```
ServerAliveInterval 100
```
## Add Non Root User

## Install Rails

## Install RBENV

## Install Rails

## Setup Firewall

