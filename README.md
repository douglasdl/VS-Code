# VS-Code

- Download the [Visual Studio Code](https://code.visualstudio.com/)
- Install the Visual Studio Code:
```sh
sudo dpkg -i file_name.deb
```

## Node.js

Update Packages
```sh
sudo apt update 
```

Install Node.js (LTS)
```sh
curl -fsSL https://deb.nodesource.com/setup_16.x | sudo -E bash -
sudo apt-get install -y nodejs
```

Install Node.js (Latest)
```sh
curl -fsSL https://deb.nodesource.com/setup_current.x | sudo -E bash -
sudo apt-get install -y nodejs
```
 
Check the Node.js Version
```sh
node -v 
```

## NPM (Node Package Manager)
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


## NVM (Node Version Manager)
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


## Expo-CLI
Install Expo
```sh
npm install -g expo-cli
```

Check Expo version
```sh
expo --version
```

Create the App
```sh
expo init appname
```

Start the App (Local)
```sh
expo start
```

Start the App (Remote)
```sh
expo start --tunnel
```


## Windows

- Download the [Node.js (LTS)](https://nodejs.org/en/)

- Double-click the .exe file and install it.

