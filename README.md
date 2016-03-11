# How to install
Untar the file into /opt folder

```
git clone https://github.com/Shanush/os161-tools-mac.git 
sudo mv os161.tar.gz /opt/
cd /opt/
sudo tar -zxvf os161.tar.gz
sudo rm os161.tar.gz
```

Update path to include os161. Add following to ~/.bash_profile
```
export PATH=$PATH:/opt/os161/tools/bin
```
