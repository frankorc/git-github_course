# git-github_course
Learning Git and Github on Platzi Day

## First Option

```

git log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%Creset - %C(bold green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(bold yellow)%d%C(reset)' --all

```

If you want to put an alias

```
git config --global alias.lg "log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%Creset - %C(bold green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(bold yellow)%d%C(reset)' --all"

```

So now you can call it using `git lg`

<img src="https://github.com/frankorc/git-github_course/blob/main/Captura%20de%20pantalla%20de%202020-11-01%2000-37-20.png" />

## Second Option

```

git log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) - %C(cyan)%aD%C(reset) %C(bold green)(%ar)%C(reset)%C(bold yellow)%d%C(reset)%n''          %C(white)%s%C(reset) %C(dim white)- %an%C(reset)' --all

```

If you want to put an alias

```
git config --global alias.lg1 "log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) - %C(cyan)%aD%C(reset) %C(bold green)(%ar)%C(reset)%C(bold yellow)%d%C(reset)%n''          %C(white)%s%C(reset) %C(dim white)- %an%C(reset)' --all"

```

So now you can call it using `git lg1`

<img src="https://github.com/frankorc/git-github_course/blob/main/Captura%20de%20pantalla%20de%202020-11-01%2000-37-33.png" />


