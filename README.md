# Tic-Tac-Toe Game

Requirements
------------
  - Git
  - Node.js v6.x.x
---

Installation Instructions
-------------------------

####Mac
---

Open a terminal and:

Install Homebrew (if not already installed)

```sh
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
    
Install Git (if not already installed):

```sh
brew update
brew doctor
echo 'export PATH="/usr/local/bin:/usr/local/sbin:~/bin:$PATH"' >> ~/.bash_profile
```    
Close and reopen the terminal window.

Install Node (if not already installed):

```sh
brew install node
```

Switch to the folder you want to store this project into and clone the repository:

```sh
git clone [git-repo-url]
```

or use your preferred git tool to do so.

Configure npm packages:

```sh
npm install
```

---

Usage
-----
```sh
npm run start
```
> Build and launch a local server that will serve your built (/dist) project on port 8088:

```sh
npm run build
```
> Build your project into the /dist folder

```sh
npm run test
```
> Run the unit tests

```sh
npm run test:watch
```
> Launch a local server that will run the unit tests every time code changes are made

```sh
npm run clean
```
> Clean your project ( Deletes Dist & node_modules directories )
