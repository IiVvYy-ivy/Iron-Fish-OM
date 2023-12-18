# Update SOFTWARE and DEPENDENCY

## Update SOFTWARE

sudo apt update

## Update DEPENDENCY

sudo apt install build-essential

# Install npm 

sudo apt npm

### Check NPM and NODE.JS version

node --version
npm  --version

#### If version is lower than ironfish required, you need update them to the minimum requirements

##### Update NODE

sudo npm cache clean -f

sudo npm install -g n

sudo n latest

##### Update NPM

sudo npm install -g npm@<version> **# <version> is npm version you need update**

# Start ironfish

ironfish

#### If you see your terminal like this, you install ironfish successfully!

