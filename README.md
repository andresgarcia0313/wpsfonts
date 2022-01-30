# wpsfonts

mkdir /tmp/wpsfonts <br>
cd /tmp/wpsfonts/<br>
git clone https://github.com/udoyen/wps-fonts<br>
sudo mkdir /usr/share/fonts/kingsoft<br>
mv /tmp/wpsfonts/wps-fonts/wps/*.ttf /usr/share/fonts/kingsoft<br>
mv /tmp/wpsfonts/wps-fonts/wps/*.TTF /usr/share/fonts/kingsoft<br>
sudo chown -R $USER:$USER /usr/share/fonts/kingsoft<br>
sudo chmod -R o+rw,g+rw /usr/share/fonts/kingsoft<br>
sudo fc-cache -vfs<br>
