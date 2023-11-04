# Centos<br />
sudo yum groupinstall -y "Development Tools"<br />
sudo yum install -y libpcap libpcap-devel<br />
git clone https://github.com/robertdavidgraham/masscan<br />
cd masscan<br />
make<br />
sudo make install<br />
<br /><br />
# Ubuntu<br />
sudo apt-get -y install git gcc make libpcap-dev<br />
git clone https://github.com/robertdavidgraham/masscan<br />
cd masscan/<br />
make<br />
sudo make install<br />
<br />
<br />
