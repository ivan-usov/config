## config
To recover the state:
```
$ git clone --no-checkout git@github.com:ivan-usov/config.git ~/config && cd $_
$ git config --local user.email ivan.a.usov@gmail.com
$ git config --local core.worktree $HOME
$ git config --local status.showUntrackedFiles no
$ git reset --hard
```
