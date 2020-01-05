# rbenv-installer
Cara mudah untuk instalasi rbenv

## Install Dependencies
`sudo apt-get install curl git autoconf bison build-essential libssl-dev libyaml-dev libreadline6-dev zlib1g-dev libncurses5-dev libffi-dev libgdbm5 libgdbm-dev`

## Update .bashrc or .bash_profile
`echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bashrc`
`echo 'eval "$(rbenv init -)"' >> ~/.bashrc`
`source ~/.bashrc`

## Rbenv Installer
`curl -fsSL https://github.com/rbenv/rbenv-installer/raw/master/bin/rbenv-installer | bash`
