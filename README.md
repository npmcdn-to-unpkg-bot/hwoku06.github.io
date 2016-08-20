# **_hwoku.github.io_**
_Hwoku Web Page for Hwaku `06_

### Git Configuration
* [Install Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
```
sudo apt-get install git
```
* Configure a user information
```
git config --global user.name "Seungin Cha"
git config --global user.email "seungin.cha@gmail.com"
```
* Change an editor (opt.)
```
git config --global core.editor emacs
```
* Show Configuration
```
git config --list
git config user.name
```
* Show Configuration
```
git help config
git config --help
man git-config
```

### Git useful commands
* Caching ID & Password when Git Push
```
git config --global credential.helper cache
```
