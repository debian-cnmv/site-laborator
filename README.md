# Laborator (site)

- Static site
- `Hugo` with theme `etch` as a **submodule**

## Useful commands

### Make and sync

```sh
cd ~/repos/site-laborator
hugo
sudo rsync -v -a --delete  /home/profesor/repos/site-laborator/public/ /var/www/html/

```

### Cloning with submodules

```sh
git clone --depth=1 git@github.com:debian-cnmv/site-laborator
git submodule add https://github.com/LukasJoswiak/etch.git themes/
git submodule init
git submodule update
```

