## PI SETUP

Distro: Raspbian Lite

run
`sudo apt-get install vim git imagemagick`

`git clone https://github.com/sstephenson/rbenv.git ~/.rbenv`
`echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bashrc`
`echo 'eval "$(rbenv init -)"' >> ~/.bashrc`
`git clone https://github.com/sstephenson/ruby-build.git ~/.rbenv/plugins/ruby-build`
`sudo apt-get install -y openssl libreadline6-dev git-core zlib1g libssl-dev`
`sudo apt-get install -y libyaml-dev libsqlite3-dev sqlite3`
`sudo apt-get install -y libxml2-dev libxslt-dev`
`sudo apt-get install -y autoconf automake libtool bison`
