# /etc/wsl.conf
[automount]
enabled = false
mountFsTab = true
[interop]
enabled = false
appendWindowsPath = false

# /etc/fstab
R:      /mnt/r  drvfs   rw,noatime,uid=1000,gid=1000    0 0

sudo apt install net-tools

sudo add-apt-repository universe
sudo apt update
sudo apt install p7zip-full
