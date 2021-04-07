## --global format.pretty
``` js
git config --global format.pretty "%C(red)%h %Cgreen(%cD)%Creset %s %C(bold blue)<%an>%C(yellow)%d%Creset"
```
![console style](https://i.imgur.com/)
## Git lg
Alias log for 10 records | [Thank](https://coderwall.com/p/euwpig/a-better-git-log)
``` js
git config --global alias.lg "log --color --graph --abbrev-commit -10"
```
