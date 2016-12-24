# bashprofile
Zsh on Bash on Ubuntu on Windows Profile Settings

alias apt-get='yum' 

## Installed Apps
```
apt-get -y install git
apt-get -y install zsh
yum -y install npm
npm install -g azure-cli
echo '. <(azure --completion)' >> .zshrc
yum -y install vim-gtk
export DISPLAY=127.0.0.1:0.0
yum -y install node
~ && wget -O - "https://www.dropbox.com/download?plat=lnx.x86_64" | tar xzf -
~/.dropbox-dist/dropboxd
apt-get -y install fluxbox 
updatedb
```

## addins
http://fluxbox.org/features/

## redis
http://vvv.tobiassjosten.net/linux/installing-redis-on-ubuntu-with-apt/
apt-get install redis-server

## zsh
http://reasoniamhere.com/2014/01/11/outrageously-useful-tips-to-master-your-z-shell/
http://www.slideshare.net/jaguardesignstudio/why-zsh-is-cooler-than-your-shell-16194692

## tmux
https://robots.thoughtbot.com/a-tmux-crash-course

## zsh theme
https://github.com/robbyrussell/oh-my-zsh/wiki/themes#agnoster

## Powerline fonts
git clone https://github.com/powerline/fonts.git
./fonts/install.sh
