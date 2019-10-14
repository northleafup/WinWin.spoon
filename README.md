## What is this

It is a spoon for hammerspoon



## Where is from 

Copy and change from [Here](https://github.com/Hammerspoon/Spoons/tree/master/Spoons) and [There](https://github.com/ashfinal/awesome-hammerspoon/blob/master/init.lua)

## How to use in MacOs  

##### 1. Clone code 

```bash
cd ~
cd .hammerspoon/Spoons
git clone https://github.com/northleafup/WinWin.spoon.git
```

##### 2. Update `.hammerspoon/init.lua` file 

You must load spoon `ModalMgr` like this first 

```lua 
hs.loadSpoon("ModalMgr")
```

Next, load this spoon 

```lua
hs.loadSpoon("WinWin")
```

Then add the following code 

```lua
spoon.ModalMgr.supervisor:enter()
```

## How to use in MacOs with  [my config](https://github.com/northleafup/my-hammerspoon)

##### 1. Clone code

```bash
cd ~
cd .hammerspoon/Spoons
git clone https://github.com/northleafup/WinWin.spoon.git
```

##### 2. Load Specify Spoon 

please refer [this](https://github.com/northleafup/my-hammerspoon#2-load-specify-spoon).

## How to custome

##### 1. Create private folder 

Create yourseft config .If there is no directory "~/.hammerspoon/private", please make it 

```bash
cd ~
cd .hammerspoon
mkdir private
```

##### 2. Copy example config 

Copy example config

```bash
cd ~
cp .hammerspoon/Spoons/WinWin.spoon/WinWin.lua ~/.hammerspoon/private/WinWin.lua
```

##### 3. Update function `obj.bindKey`

You can update the function body ,but can not delete this function



## Thanks To

[https://github.com/ashfinal/awesome-hammerspoon](https://github.com/ashfinal/awesome-hammerspoon)