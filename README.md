sudo apt upgrade
sudo snap install microstack --beta
snap list microstack
sudo microstack init --auto --control
microstack.openstack --version
sudo snap get microstack config.credentials.keystone-password
apt install net-tools
ifconfig

open browser -> your_ip

create network and subnets
public - 10.0.1.0/24
private - 10.0.2.0/24

configure internet gateway (virtual router)

NAT gateway

login using virtual public image by first creating image from iso
