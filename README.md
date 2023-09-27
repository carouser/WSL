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
sudo apt-get install nodejs
#sudo apt-get install npm

sudo npm cache clean -f
sudo npm install -g n
sudo n stable

sudo apt-get purge nodejs --auto-remove
sudo apt-get purge npm --auto-remove
#whereis node

npx create-react-app project-x

#sudo npm install -g npm@10.1.0
```
