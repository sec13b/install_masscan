# Centos
sudo yum groupinstall -y "Development Tools"
sudo yum install -y libpcap libpcap-devel
git clone https://github.com/robertdavidgraham/masscan
cd masscan
make
sudo make install

# Ubuntu
sudo apt-get -y install git gcc make libpcap-dev
git clone https://github.com/robertdavidgraham/masscan
cd masscan/
make
sudo make install
