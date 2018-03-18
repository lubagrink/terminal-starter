# terminal-starter
##mac
* brew : https://brew.sh
* brew install thefuck : https://github.com/nvbn/thefuck
* liquidprompt : https://github.com/nojhan/liquidprompt
* 
```
test -e "${HOME}/.iterm2_shell_integration.bash" && source "${HOME}/.iterm2_shell_integration.bash"
```
* brew install caskroom/cask/clipy 


##git
* ssh keys https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/ : 
ssh-keygen -t rsa -b 4096 -C "lubagrink@yandex.ru"
~/.ssh/config : 
```
Host *
 AddKeysToAgent yes
 UseKeychain yes
 IdentityFile ~/.ssh/id_rsa
```
or
```
Host *
   SendEnv LANG LC_*

HashKnownHosts no
UseRoaming no
ForwardAgent yes
```
ssh -T git@github.com

