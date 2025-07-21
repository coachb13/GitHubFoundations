
> Hidden `.git` folde


## Initialize Git Repo

```sh
mkdir /workspace/tmp
cd /workspace/tmp
git init
touch README.md
code README.md


```

## Commits

Cloning can be done via:

- HTTPS
- SSH
- GitHub CLI



### HTTPS

```sh
git clone https://github.com/coachb13/GitHubFoundations.git
```

Set the global editor



## Branches



## Remotes


## Stashing



## Merging


## Add

- stage changes ready to be committed


## Status


## Reset
- move staged changes to unstanged
- useful if you want to revert files not to be committed

```sh
git add .
git reset
```
> `git reset` reverts `git add .`