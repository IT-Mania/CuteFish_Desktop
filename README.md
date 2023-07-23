CUTEFISH DESKTOP ENVIRONMENT

![cutefish_desktop](https://github.com/IT-Mania/CuteFish_Desktop/assets/66995446/d6f09cea-baf4-4f87-a0d7-dca8989c705e)

How to add on EncomOS

cd /etc/yum.repos.d/

sudo wget https://raw.githubusercontent.com/IT-mania/CuteFish_Desktop/master/cutefish-desktop.repo

sudo dnf update --refresh --repo cutefish-desktop

sudo dnf install cutefish-desktop cutefish-screenshot fishui-devel fishui libcutefish cutefish-videoplayer

If you want to change the graphical login screen to Cutefish, install the sddm-theme-cutefish package.

sudo dnf install sddm-theme-cutefish

Done! Enjoy!


