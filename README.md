# uniswap2-info
uniswap analyzation

1. update npm to the latest version
sudo npm install -g npm

2. install Graph CLI: npm install -g @graphprotocol/graph-cli
some useful links: https://docs.npmjs.com/resolving-eacces-permissions-errors-when-installing-packages-globally

[ reinstall yarn ]
1. sudo apt remove cmdtest (installed default by ubuntu)
2. curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
3. sudo apt-get install yarn

3. graph init --from-example kundouzhishou/uniswap2 uni-dir

