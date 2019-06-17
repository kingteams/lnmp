# lnmp

screen: Centos ：yum install screen Ubuntu ：apt-get install screen
wget：yum install wget Ubuntu ：apt-get install wget

screen -S lnmp
wget https://github.com/kingteams/lnmp/raw/master/lnmp1.6.tar.gz -cO lnmp1.6.tar.gz && tar zxf lnmp1.6.tar.gz && cd lnmp1.6 && ./install.sh lnmp
