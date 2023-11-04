<p>===================================================<br />
# Centos <br />
  <code>sudo yum groupinstall -y "Development Tools" </code><br />
  <code>sudo yum install -y libpcap libpcap-devel</code> <br />
  <code>git clone https://github.com/robertdavidgraham/masscan</code> <br />
  <code>cd masscan</code> <br />
 <code>make</code> <br />
 <code>sudo make install</code> <br />
  ===================================================<br />
  ===================================================<br />
  # Ubuntu<br />
 <code>sudo apt-get -y install git gcc make libpcap-dev </code> <br />
<code>git clone https://github.com/robertdavidgraham/masscan.git </code> <br />
<code>cd masscan/</code> <br />
<code>make</code><br />
<code>sudo make install</code><br />


  ===================================================<br /># 
CentOS Linux 7 (Core)</p>
<p>masscan-ng</p>
<code>sudo yum install -y epel-release</code> <br />
<code>sudo yum install -y unzip gcc clang glibc-devel pcre-devel openssl11-devel libpcap-devel</code> <br />
<code>git clone https://github.com/bi-zone/masscan-ng.git </code> <br />
<code>cd masscan-ng </code> <br />
<code>CC=clang LDFLAGS="-L/usr/lib64/openssl11" INCLUDES="-I/usr/include/openssl11" make</code> <br />
<code>make install</code> <br />
  ===================================================




