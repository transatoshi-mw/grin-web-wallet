# MWC Wallet Standalone

### Description
Standalone version of the MimbleWimble Coin web wallet, [mwcwallet.com](https://mwcwallet.com), that consists of just a single HTML file.

### Building
Run the following command to install the dependencies required to build this.
```
sudo apt install php php-intl php-mbstring openssl unzip wget grep sed coreutils
```
Then run the following commands to build this.
```
wget "https://github.com/NicolasFlamel1/MWC-Wallet-Standalone/archive/refs/heads/master.zip"
unzip "./master"
cd "./MWC-Wallet-Standalone-master"
"./build.sh"
```
This will create the HTML file, `MWC-Wallet-Standalone-master/MWC Wallet Standalone.html`.
