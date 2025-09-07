## Cloning

We can clone using three ways

First of all I am going to create a tmp directory to see the function of the ```git clone``` command

```sh
mkdir /workspaces/tmp && cd tmp
```

### HTTPS
```sh
git clone https://github.com/spB0B/Github-Foundation-Practice.git
```
>may need a FGT to push commit from a local workspace if you haven't signed into the GitHub from that workspace

go to settings > developer options

## Git Hidden folder

There is a hidden folder inside that cloned repository called `.git`. It has things like `HEAD, config, description, hooks, index, info, logs, objects, packed-refs, refs`. some of the things are encoded but some files has important things like url of this repo.

To create new repo I created /workspaces/tmp2. then command `git init` to initiate a git repository.

after creating the `Readme.md` inside the tmp2, I `git status` to `check the status of the repo`. there I could see files that are currently not tracked by the git. So I used `git add` which is used to `add everything that is not being tracked`. and we can use the file name instead of the period that way git only stage that one.  

## Commits

git commit is used to commit the changes to the repository.
```sh
git commit -m 'message'
```
the `-m` flag gives the commit message from the terminal. that way we don't have to type the commit message in the editor. the message is also useful because I think it is used to reverse commits.

## Branches

## Remotes

## Stashing

## Mergings

## Push

this is me trying to push the the changes after cloning the repository to my local workspace. first I cloned the repo using `git clone` and then now I am trying to do `git push` from this local env. 

### FGT -Fine Grained Token

FGT is a one time appearing token that allows us to use instead of the password. we can set permissions, valid time period for FGT. nothing will cache that value.