
# KBAIC - Dev-environment

Lets setup our machine for ethereum development

## 1. Nodejs and npm

Install nodejs and npm

```bash
  sudo apt update
```
 ```bash
 sudo apt install nodejs
```   
 ```bash
 node -v
```   
 ```bash
sudo apt install npm
```   
via pre built installer https://nodejs.org/en/download

## 2. Git
```
sudo apt install git-all
```
https://git-scm.com/downloads


## 3. Ganache

install the UI version - its awesome

https://trufflesuite.com/ganache/

## 4 .Truffle

Install globally

```bash
  npm install -g truffle

```
run as administartor in windows
```bash
truffle version

```

Create a directory
```bash
  mkdir setup
```
```bash
  cd setup
```

Initialise 

```bash
  truffle init
```

compile

```bash
  truffle compile
```
deploy

```bash
  truffle migrate --reset
```

## 5 . Geth
we will set up a private network using Geth, an execution client, in proof of work mode.

https://geth.ethereum.org/downloads

download geth 

extract and change into the folder

```bash
  cd geth 
```
Give executable permission
```
sudo chmod +x geth
```
Copy the file to where OS executables are stored.

```bash
sudo cp geth /usr/local/bin/
```
check version
```bash
 geth version
```