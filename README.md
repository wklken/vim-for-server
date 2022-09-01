vim-for-server
==============

.vimrc, simple configures for server, without plugins.

# Introduction

This repository is a simplified version of [k-vim](https://github.com/wklken/k-vim)

Just remove all plugins, keep basic config.

# Screenshot

![screenshot](https://raw.githubusercontent.com/wklken/gallery/master/vim/vim-for-server.png)

# Install

#### 1. backup your old .vimrc if it is necessary

```
cp ~/.vimrc ~/.vimrc_bak
```

#### 2. just get the file

recommend
```
# Unix/Linux/macOS
curl https://raw.githubusercontent.com/the-eric-kwok/vim-for-server/master/vimrc > ~/.vimrc

# Windows PowerShell
Invoke-WebRequest -URI https://raw.githubusercontent.com/the-eric-kwok/vim-for-server/master/vimrc -OutFile ~\.vimrc
```
or  use git

```
# Unix/Linux/macOS
git clone https://github.com/the-eric-kwok/vim-for-server.git
ln -s vim-for-server/vimrc ~/.vimrc

# Windows PowerShell
git clone https://github.com/the-eric-kwok/vim-for-server.git
# Run below command in Administrator privelege
New-Item -Value vim-for-server/vimrc -Path ~\.vimrc -ItemType SymbolicLink

```

If you're using IdeaVim, you can do
```
# Unix/Linux/macOS
ln -s vim-for-server/vimrc ~/.ideavimrc

# Windows PowerShell
# Run below command in Administrator privelege
New-Item -Value vim-for-server/vimrc -Path ~\.ideavimrc -ItemType SymbolicLink
```

#### 3. Done, enjoy it


# Donation

You can Buy me a coffee:)  [link](http://www.wklken.me/pages/donation.html)


------------------------
------------------------

wklken

Email: wklken@yeah.net

Github: https://github.com/wklken

Blog: [http://www.wklken.me](http://www.wklken.me)

2014-10-26 ShenZhen
