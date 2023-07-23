How to add on EncomOS

cd /etc/yum.repos.d/

sudo wget https://raw.githubusercontent.com/IT-mania/CuteFish_Desktop/master/cutefish-desktop.repo

sudo dnf update --refresh --repo cutefish-desktop

sudo dnf install cutefish-* fishui-* libcutefish sddm-theme-cutefish

Done! Enjoy!
