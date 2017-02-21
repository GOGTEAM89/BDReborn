
# [BDreborn](https://telegram.me/BDreborn)

**An advanced and powerful administration bot based on NEW TG-CLI


* * *

## Commands

| Use help |
|:--------|:------------|
| [#!/]help | just send help in your group and get the commands |

**You can use "#", "!", or "/" to begin all commands

* * *

# پیش نیازها
`````sh
wget http://luarocks.org/releases/luarocks-2.2.2.tar.gz && tar zxpf luarocks-2.2.2.tar.gz && cd luarocks-2.2.2 && ./configure; sudo make bootstrap && sudo luarocks install luasocket && sudo luarocks install luasec && sudo luarocks install redis-lua && sudo luarocks install lua-term && sudo luarocks install serpent && sudo luarocks install dkjson && sudo luarocks install lanes && sudo luarocks install Lua-cURL && sudo luarocks install luaxmlrpc
`````
# پیش نیازها
`````sh
sudo apt-get update && sudo apt-get upgrade && sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev libevent-dev make unzip git redis-server g++ libjansson-dev libpython-dev expat libexpat1-dev tmux subversion
`````
# پیش نیازها
`````sh
sudo apt-get install libstdc++6 && sudo add-apt-repository ppa:ubuntu-toolchain-r/test && sudo apt-get update && sudo apt-get upgrade && sudo apt-get dist-upgrade
`````
# install bot
`````sh
cd $HOME && git clone https://github.com/GOGTEAM89/BDReborn.git && cd BDReborn && chmod +x beyond.sh && ./beyond.sh install && ./beyond.sh
`````

* **Start Auto-launch**
`````sh
cd BDReborn && sed -i "s/hidden/$(whoami)/g" etc/pika.conf; sed -i "s_telegrambotpath_$(pwd)_g" etc/pika.conf && sudo cp etc/pika.conf /etc/init/ && chmod 777 pika && nohup ./pika &>/dev/nu
`````
* **and**
`````sh
sudo start pika && screen ./pika
`````
* **install Redis [Free Servers]**
`````sh
sudo service redis-server start && redis-cli
`````


#on bot

`````sh
cd $HOME && cd BDReborn && ./beyond.sh
`````
#update bot 
`````sh
cd $HOME && cd BDReborn && git pull
`````
