<p>===================================================<br /># Centos <br />sudo yum groupinstall -y "Development Tools" <br />sudo yum install -y libpcap libpcap-devel <br />git clone https://github.com/robertdavidgraham/masscan <br />cd masscan <br />make <br />sudo make install <br />===================================================<br />===================================================<br /># Ubuntu<br />sudo apt-get -y install git gcc make libpcap-dev<br />git clone https://github.com/robertdavidgraham/masscan<br />cd masscan/<br />make<br />sudo make install<br />===================================================</p>
<p>===================================================<br /># ===================================================<br /># CentOS Linux 7 (Core)</p>
<p>masscan-ng</p>
<pre class="notranslate"><code class="notranslate">sudo yum install -y epel-release
sudo yum install -y unzip gcc clang glibc-devel pcre-devel openssl11-devel libpcap-devel<br />git clone <a href="https://github.com/bi-zone/masscan-ng.git">https://github.com/bi-zone/masscan-ng.git</a><br /></code></pre>
<pre class="notranslate"><code>cd masscan-ng</code></pre>
<pre class="notranslate"><code class="notranslate">CC=clang LDFLAGS="-L/usr/lib64/openssl11" INCLUDES="-I/usr/include/openssl11" make<br /></code></pre>
<pre class="notranslate"><code>make install</code><code class="notranslate"></code><br />===================================================</pre>
<p>&nbsp;</p>



