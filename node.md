# Update / Install node
## Mac
https://nodejs.org/en/download/


## Ubuntu
*Install nodejs 14 and yarn*
```
curl -sL https://deb.nodesource.com/setup_14.x | sudo bash -

cat /etc/apt/sources.list.d/nodesource.list
deb https://deb.nodesource.com/node_14.x focal main
deb-src https://deb.nodesource.com/node_14.x focal main

sudo apt -y install nodejs

sudo apt -y install gcc g++ make

curl -sL https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
sudo apt update && sudo apt install yarn
```
