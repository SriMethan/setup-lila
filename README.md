# setup-lila

sudo apt update && sudo apt upgrade -y
sudo reboot command
sudo apt --purge autoremove
sudo apt install update-manager-core
sudo do-release-upgrade
lsb_release -a

# Inatall Yarn
```
curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
sudo apt update
sudo apt install yarn
yarn --version
```
