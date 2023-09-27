# /etc/wsl.conf
```
[automount]
enabled = false
mountFsTab = true

[interop]
enabled = false
appendWindowsPath = false
```

# /etc/fstab
```
R:      /mnt/r  drvfs   rw,noatime,uid=1000,gid=1000    0 0
```

# miscellaneous
```
sudo apt install net-tools

sudo apt install mc

sudo add-apt-repository universe
sudo apt update
sudo apt install p7zip-full
```

# installing the recent stable Node.js
```
# https://www.hostingadvice.com/how-to/update-node-js-latest-version/

sudo apt-get update
sudo apt-get install nodejs
#sudo apt-get install npm
sudo npm cache clean -f
sudo npm install -g n
sudo n stable

https://askubuntu.com/questions/1152570/npm-cant-find-module-semver-error-in-ubuntu-19-04

sudo apt-get purge nodejs --auto-remove
sudo apt-get purge npm --auto-remove
#whereis node
#sudo npm install -g npm@10.1.0

npx create-react-app project-x
```
