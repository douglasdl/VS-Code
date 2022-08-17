# VS-Code

- Download the [Visual Studio Code](https://code.visualstudio.com/)

- For Windows just double-click the .exe file and install it.

- For Linux run:
```sh
sudo dpkg -i file_name.deb
```


## Node.js
### Windows
- Download the [Node.js (LTS)](https://nodejs.org/en/)

- Double-click the .exe file and install it.

### Linux
Update Packages
```sh
sudo apt update 
```

Install Node.js
```sh
curl -fsSL https://deb.nodesource.com/setup_current.x | sudo -E bash -
sudo apt-get install -y nodejs
```
 
Check the Node.js Version
```sh
node -v 
```

## Npm
- For Linux run:
Update Packages
```sh
sudo apt update 
```

Install the NPM
```sh
sudo apt install npm
```

Check the NPM Version
```sh
npm -v 
```


## Yarn


## NVM
Install NVM
```sh
curl https://raw.githubusercontent.com/creationix/nvm/master/install.sh | bash 
```
Load the environment to use NVM
```sh
source ~/.bashrc
```
List all NPM versions
```sh
nvm ls-remote
```

Install LTS
```sh
nvm install v16.17.0
```
Change the used version
```sh
nvm use v16.17.0
```


## Expo-cli
```sh
npm install -g expo-cli
```

expo -V
