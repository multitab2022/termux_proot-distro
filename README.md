https://multitab.tistory.com/266

if ubuntu 22.04 LTS is required, it can be installed as follows.

# termux_proot-distro
termux proot-distro

```
-- in Termux 
$ cd ~
$ wget https://raw.githubusercontent.com/multitab2022/termux_proot-distro/main/distro-plugins/ubuntu2204.sh
$ cp ubuntu2204.sh $PREFIX/etc/proot-distro/ubuntu2204.sh

-- install
$ proot-distro install ubuntu2204

-- remove
$ proot-distro remove ubuntu2204
```
