# Git and Github 

- [install git](#install-git)
- [configure git](#configuration---git)
- [verified commit using ssh](#verified-commit---using-ssh)



## install git 

1. https://git-scm.com/
2. brew install git (make sure homebrew is alrady install)

## configuration - git

`git config --global user.name "your-name"`
`git config --global user.email "your-email"` : email should be link to your github account
`git config --global color.ui auto`

## [verified] commit - Using SSH

check existing key: `ls -al ~/.ssh` no directory means no keys

Steps for first timer

- `ssh-keygen -t ed25519 -C "your_email@example.com"` - generate ssh key
- `eval "$(ssh-agent -s)"` add it to the background
- `touch ~/.ssh/config` creat config file for ssh
- `code ~/.ssh/config` then add following

```git
Host *.github.com
  AddKeysToAgent yes
  UseKeychain yes
  IdentityFile ~/.ssh/id_ed25519
```

- no need to enter passphrase again and again
  - `ssh-add --apple-use-keychain ~/.ssh/id_ed25519` for newer version 
  - `/usr/bin/ssh-add -K ~/.ssh/id_ed25519` for older version and for those having trouble with -K option

- adding these keys to github so linking will be establish between git commit and github
  - `pbcopy < ~/.ssh/id_ed25519.pub` it will copy the keys now go to github account>setting ssh and gpg keys > add ssh > paste and click on add ssh
  - use `gh` cli or web to add your key

- adding ssh to git 
  - `git config --global gpg.format ssh` it will specify the format of key is being used for sign and 
  -`git config --global user.signingkey ~/.ssh/id_ed25519.pub` add path of your ssh keys 
- commit command with verified signature 
  - `git commit -S -m "message"`  or add these-
 after this commit will ask for passphrase
`git config --global commit.gpgsign true` after this no need to use -S flag with git commit.

