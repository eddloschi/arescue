ARescue
=======

Linux LiveCD with tools to test and rescue a system.

It is based on [Arch Linux](https://archlinux.org/) and uses [Archiso](https://projects.archlinux.org/archiso.git/) for building.
More information is avaiable at the [ArchWiki](https://wiki.archlinux.org/index.php/Archiso).

Building
========

```shell
# git clone git@github.com:eddloschi/arescue.git
# cd releng
# ./build.sh -v
```

Note that is important to use *root* user for this because every file inside ```releng/root-image``` **must** be root owned for the building to succeed
