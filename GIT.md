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
* Check Status
```
git status
git status -s
(= git status --short)
```
  * ```?? A : untracked```
  * ```_M B : unstaged(modified)```
  * ```MM B : staged(modified) -> unstaged(modified)```
  * ```A_ B : staged(added)```
  * ```M_ B : staged(modified)```


* Untracked -> Staged
* Modified -> Staged
```
git add filename
```
* Staged -> Untracked
* Staged -> Modified
```
git reset [HEAD] filename
```
* Modified -> Unmodified
```
git checkout -- filename
```

* Check Differences Between Unmodified(Staged) & Modified(Unstaged)
```
git diff filename
```
* Check Differences Between Commited & Staged
```
git diff --staged filename
git diff --cached filename
```

* Commit
```
git commit -m 'commit message'
```
* Commit including staging step
```
git commit -a -m 'commit message'
```
