# WireGuard installer for Gaming

### 1st Step: Upgrade OS

Because WireGuard is a kernel module, you **MUST** upgrade the kernel to latest first and reboot your server once.
# If you are using Ubuntu 24.04
```bash
sudo apt update && sudo apt upgrade -y
```

### Optional 1.5 Step: Install GIT for minimal install images
```bash
sudo apt install git -y
```


### 2nd Step: Download and run the script.

Download and execute the script. Script user needs to be able to use `sudo` command.

Answer the questions asked by the script and it will take care of the rest. For most VPS providers, you can just enter through all the questions.

```bash
git clone https://github.com/jakeloftis/wg_gaming_installer.git
```
```bash
cd ./wg_gaming_installer
```
```bash
./install.sh
```
## Stop / Restart / Uninstall / List clients / Add/Remove a client 

Run the script again will give you these options!
