### screen install
Centos ：yum install screen <br>
Ubuntu ：apt-get install screen

### wget install
Centos：yum install wget <br>
Ubuntu ：apt-get install wget

### lnmp install
screen -S lnmp
wget https://github.com/kingteams/lnmp/releases/download/1.6/lnmp1.6.tar.gz -cO lnmp1.6.tar.gz && tar zxf lnmp1.6.tar.gz && cd lnmp1.6 && ./install.sh lnmp

### nginx install
screen -S lnmp
wget https://github.com/kingteams/lnmp/releases/download/1.6/lnmp1.6.tar.gz -cO lnmp1.6.tar.gz && tar zxf lnmp1.6.tar.gz && cd lnmp1.6 && ./install.sh nginx
