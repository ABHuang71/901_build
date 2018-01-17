# 901_build
#
# CentOS 7.3 with docker, build Advantech Debian-LIVE
#   Get Docker for CentOS
#   -- https://docs.docker.com/engine/installation/linux/centos/#install-from-a-package
#   How To Install and Use Docker on CentOS 7
#   -- https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-centos-7
#

CentOS 7.3 1611 x64 (Server w/ GUI)


sudo chmod u+w /etc/sudoers
sudo visudo
	root	ALL=(ALL:ALL) ALL
	swae	ALL=(root) NOPASSWD:ALL
sudo chmod u-w /etc/sudoers


uname -a
	Linux localhost.localdomain 3.10.0-514.el7.x86_64 #1 SMP Tue Nov 22 16:42:41 UTC 2016 x86_64 x86_64 x86_64 GNU/Linux
cat /etc/*-release
	CentOS Linux release 7.3.1611 (Core)
	NAME="CentOS Linux"
	VERSION="7 (Core)"
	ID="centos"
	ID_LIKE="rhel fedora"
	VERSION_ID="7"
