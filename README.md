# wpsfonts

mkdir /tmp/wpsfonts
cd /tmp/wpsfonts/
git clone https://github.com/udoyen/wps-fonts
sudo mkdir /usr/share/fonts/kingsoft
mv /tmp/wpsfonts/wps-fonts/wps/*.ttf /usr/share/fonts/kingsoft
mv /tmp/wpsfonts/wps-fonts/wps/*.TTF /usr/share/fonts/kingsoft
sudo chown -R $USER:$USER /usr/share/fonts/kingsoft
sudo chmod -R o+rw,g+rw /usr/share/fonts/kingsoft
sudo fc-cache -vfs
