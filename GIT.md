# **_Git Tutorials_**
_References for Git Commands_

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

### Git Useful Commands
* Caching ID & Password when Git Push
```
git config --global credential.helper cache
```

### Git Examples
* Untracked -> Staged
```
git add filename
```
* Staged -> Untracked
```
git reset [HEAD] filename
```
* Modified -> Unmodified
```
git checkout -- filename
```
* Modified -> Staged
```
git add filename
```
* Staged -> Modified
```
git reset [HEAD] filename
```
