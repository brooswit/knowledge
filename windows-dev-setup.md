## Quickstart
```
Set-ExecutionPolicy RemoteSigned -scope CurrentUser
iwr -useb get.scoop.sh | iex
scoop install openssh
scoop install curl
scoop install git
```

## Setup step 1: Package management

All "real" dev environments are built using package managers. Unlike other operating systems, windows does not have a package manager. I use scoop. it's great.

Setup instructions can be found here: https://scoop.sh/

## Setup step 2: Useful packages

### A) tools
`scoop install git`
`scoop install curl`

### B) Background services
`scoop install redis`
`scoop install mongodb`

### C) Runtimes
`scoop install nodejs`
`scoop install python`

## Step 3: Useful software
https://www.autohotkey.com
https://github.com/brooswit/autohotkey-monorepo

## Step 4: Helpful Guides
https://mcpmag.com/articles/2019/03/28/environment-variables-in-powershell.aspx
