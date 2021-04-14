#!/bin/bash

cd /etc/ssh
echo PermitRootLogin yes >> sshd_config
passwd root
sleep 2
systemctl restart ssh
