title: Installation
prev: index
next: setup
---
It only takes few minutes for you to get Hexo ready. If you encounter any problems on installation and you can't find the solution here. Please [submit an issue](https://github.com/tommy351/hexo/issues) and I'll try to solve your problems.

## Requirements

Installing Hexo is quite easy. However, there're something required before you get started.

- [Node.js](http://nodejs.org/)
- [Git](http://git-scm.com/)

If your computer has been installed the requirements above already. Congratulations! Just install Hexo with npm.

``` bash
$ npm install -g hexo
```

If not, please follow the following instructions to install all the requirements.

{% note warn For Mac users %}
You may encounter some problems when compiling. Please install Xcode from App Store first. After Xcode is installed, open Xcode and go to **Preferences -> Download -> Command Line Tools -> Install** to install command line tools.
{% endnote %}

## Step 1: Install Git

- Windows: Download & install [msysgit](http://code.google.com/p/msysgit/).
- Mac: Install it with [Homebrew](http://mxcl.github.com/homebrew/), [MacPorts](http://www.macports.org/) or [installer](http://code.google.com/p/git-osx-installer/).
- Linux (Ubuntu, Debian): `sudo apt-get install git-core`
- Linux (Fedora, Red Hat, CentOS): `sudo yum install git-core`

## Step 2: Install Node.js

The best way to install Node.js is installing with [nvm](https://github.com/creationix/nvm).

cURL:

``` bash
$ curl https://raw.github.com/creationix/nvm/master/install.sh | sh
```

Wget:

``` bash
$ wget -qO- https://raw.github.com/creationix/nvm/master/install.sh | sh
```

Once installed, restart the terminal and run the following command to install Node.js.

``` bash
$ nvm install 0.10
```

Or you can download the [installer](http://nodejs.org/) and install it.

## Step 3: Install Hexo

Once all the requirements are installed, you can install Hexo with npm.

``` bash
$ npm install -g hexo
```