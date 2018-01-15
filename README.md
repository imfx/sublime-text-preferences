# Sublime Text (3) Preferences

## Cheatsheet

### User Packages Directory
```bash
$ cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User
```

### Set up the first device

```bash
$ git init
$ git remote add origin <repository url>
$ git fetch
$ git commit -am "added: settings and packages"
$ git push
```

### Set up all other devices

```bash
$ git init
$ git remote add origin <repository url>
$ git fetch
$ git reset --hard origin/master
```

## Tutorials
* https://packagecontrol.io/docs/syncing
* [https://medium.com/@devmount/using-git-to-sync-sublime-text-settings-f70b8dc7a40d](https://medium.com/@devmount/using-git-to-sync-sublime-text-settings-f70b8dc7a40d)