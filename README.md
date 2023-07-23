How to add on EncomOS

cd /etc/yum.repos.d/

sudo wget https://raw.githubusercontent.com/IT-mania/CuteFish_Desktop/master/cutefish-desktop.repo

sudo dnf update --refresh --repo cutefish-desktop

sudo dnf install cutefish-desktop cutefish-screenshot fishui-devel fishui libcutefish cutefish-videoplayer

If you want to change the graphical login screen to Cutefish, install the sddm-theme-cutefish package.

sudo dnf install sddm-theme-cutefish

Done! Enjoy!
