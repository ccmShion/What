#install ssr
yum -y install wget
wget -N --no-check-certificate https://github.com/ccmShion/What/blob/master/ssr.sh
chmod +x ssr.sh
bash ssr.sh

#install bbr
wget --no-check-certificate https://github.com/ccmShion/What/blob/master/bbr.sh
chmod +x bbr.sh
bash bbr.sh
