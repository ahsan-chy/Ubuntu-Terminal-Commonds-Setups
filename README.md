# Ubuntu-Terminal-Commonds-Setups

Basic commonds of Terminal 
- Terminal Commands
- Docker Setup
- VS Code Setup
- Node JS Setup
- 




## Terminal Commands

To know about all commonds in Terminal
```
help
```
Cange Drive
```
d:
```

mkdir – Creates a Folder
```
mkdir new-folder-name
```

Show folders
```
dir
```
rmdir – Deletes a Folder
```
rmdir foldername
```

Move back to parent dir
```
cd ..
```

Move Inside Folder
```
cd foldername
```

Make react app here 
```
npx create-react-app .
```

Make react app in folder **firstapp**
```
npx create-react-app firstapp
```

Open current folder in VS Code
```
code .
```

Rename Files and Folder
```
ren [folder][newFolderName]
```

Copy Files
```
copy [file][destination]
```

#### Stop Execution Commond
`ctrl + c`


#### Tree
`tree`

#### ClS
`cls`
#### Clear
`clear`

#### Delete
```
del [file]
```

#### Uninstall package
```
rm -rf node_modules
```
```
npm cache clean --force
```


# Ubuntu Terminal Commonds 


Here are some commonly used Ubuntu commands:

- **ls:** list directory contents
- **cd:** change directory
- **mkdir:** make directory
- **rmdir:** remove directory
- **touch:** create a new file
- **rm:** remove files or directories
- **cp:** copy files or directories
- **mv:** move files or directories
- **sudo:** run a command with superuser privileges
- **apt-get:** package manager for installing, updating and removing software
- **grep:** search for specific text within files
- **chmod:** change permissions for files or directories
- **chown:** change ownership of files or directories
- **tar:** create or extract compressed archives
- **ssh:** remote login to another computer
- **ps:** display running processes
- **top:** display system resource usage
- **ifconfig:** display network configuration information
- **ping:** test network connectivity to a specific host or IP address
- **traceroute:** trace the route taken by packets across a network.



. 


# Ubuntu setup and packages install

- Google Chrome
- Node JS
- NVM
- VS Code
- Discord
- Postman
- Wrap
- Docker
- 


### Node JS

[Download Node.js the way you want](https://nodejs.org/en/download/package-manager)


```javascript
sudo apt update

&

sudo apt install curl
```

```javascript
# installs nvm (Node Version Manager)
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
```

**Close the terminal and reopen and run below commonds**

```javascript
# download and install Node.js
nvm install 20

# verifies the right Node.js version is in the environment
node -v # should print `v20.13.1`

# verifies the right NPM version is in the environment
npm -v # should print `10.5.2`
```


- While installing packages first time issues are following. 


### Yarn - Install and inital setup 

```javascript
npm install --global yarn

yarn --version
```

```javascript

```

## NVM

### [Video Link](https://youtu.be/RDScvojqAio)

[nvm Link to download NVM](https://github.com/coreybutler/nvm-windows#install-nvm-windows)


How to setup NVM

- First open **Gitbash** / **Window powershell(Admin)** then run following commonds
```javascript
nvm current 

nvm on 

nvm ls 

nvm install 18.16.0

nvm use 18.16.0

```

Install version
```javascript
nvm install <version>
nvm install 16.19.1
nvm install 18.16.0
```

Check Current Version
```javascript
nvm current
```

Use nvm version
```javascript
nvm use <version>
nvm use 18.16.0
```

Set Default nvm
```javascript
nvm alias default 14

```



[NVM Link](https://github.com/nvm-sh/nvm)


## NVS (Node Version Switcher)


[NVS Link](https://github.com/jasongin/nvs)


### Postman 

```javascript
sudo snap install postman
```

### Git & Github

- [git install](https://git-scm.com/download/linux)

```javascript
sudo apt-get install git
```


- For Github you need to follow these commonds 


```javascript
ssh-keygen -t rsa -b 4096 -C "ahsaniqbal@gmail.com"
```
Enter Enter Enter

```javascript
eval $(ssh-agent -s)
```

```javascript
ssh-add
```

- Get the ssh key
```javascript
cat ~/.ssh/id_rsa.pub
```

- Copy the ssh key and paste it in github.com and save it.



#### Setup username and email in local folder or globally. 

```javascript
git config user.name "ahsan-"
git config user.email "ahsaniqbal@aleh.tech"
```







## VS Code Install

Step1: 

Download VS Code from official site

```javascript
sudo dpkg -i ./<file>.deb

```



.



## Change Taskbar position


## [How to Fix ‘shell user theme extension not enabled’ Error on Ubuntu](https://geniusgeeks.com/shell-user-theme-extension-not-enabled/)



.



## Node JS Install

[Node JS Latest Version](https://github.com/nodesource/distributions)

#### Update Node JS version to Latest

[3 Ways to Update Node.js to Latest Version on Linux Systems](https://phoenixnap.com/kb/update-node-js-version)

## Nvm



## Postman


## Docker Download

[Documentation to install Docker](https://docs.docker.com/engine/install/ubuntu/)

**install using the apt repository**

- Set up Docker's apt repository.
- Install the Docker packages.
- Verify that the Docker Engine installation is successful by running the hello-world image.
- Install the .deb downloaded package.
    ```sudo apt-get install ./docker-desktop-4.29.0-amd64.deb```
- Verify that the Docker Engine installation is successful by running the hello-world image.




## Curl

`Note: If you don't have **curl,** install the utility by running the command:`

```javascript
sudo apt install curl
```



## MySql Workbanch
```javascript
snap install mysql-workbench-community
apt install mysql-workbench
```
```javascript

```
```javascript

```
