# check node version

```
node -v
```

# node current versions

```
nvm ls
```

# install node lts/hydrogen

```
nvm install lts/hydrogen
```

# set default version

```
nvm alias default lts/hydrogen
```

# set default version using .nvmrc

### create file .nvmrc and put the config below

```
lts/hydrogen
```

### run nvm install command

```
nvm install
```

# Notes

- lts: long term support
- rc: run commands (.nvmrc, .bashrc, etc)
