# 网易云音乐 Ubuntu 16.04
从深度repo上下载的netease-cloud-music_1.1.3.1-1_amd64.deb解包制作而成，
加入来自launchpad的“Qt 5.10.1 for /opt Xenial”，来自debian中文的libqcef1_1.1.4.4-3rebuild.0.deb10u1.debiancn0_amd64.deb，
目测这个版本Bug少一些..
你需要:
git clone https://github.com/TeddyNight/netease-cloud-music.git
cd netease-cloud-music
sudo dpkg -i netease-cloud-music.deb
sudo dpkg -i libqcef1_1.1.4.4-3rebuild.0.deb10u1.debiancn0_amd64.deb
详细可以看blog:http://www.sftp.pw/2019/02/11/netease-cloud-music-for-xenial.html
