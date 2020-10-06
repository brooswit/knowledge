## Quickstart

```
Set-ExecutionPolicy RemoteSigned -scope CurrentUser
iwr -useb get.scoop.sh | iex
scoop install openssh
scoop install curl
scoop install git
```

## Package management

All "real" dev environments are built using package managers. Unlike other operating systems, windows does not have a package manager. I use scoop. it's great.

Setup instructions can be found here: https://scoop.sh/

Here are some useful packages

### Tools

`scoop install git`

`scoop install curl`

`scoop install heroku`

### Background services

`scoop install redis`

`scoop install mongodb`

### Runtimes

`scoop install nodejs`

`scoop install python`

## Other software

https://www.autohotkey.com
https://github.com/brooswit/autohotkey-monorepo
https://github.com/microsoft/PowerToys/releases/

## Helpful Guides

https://mcpmag.com/articles/2019/03/28/environment-variables-in-powershell.aspx
