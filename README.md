# 4015 dotfiles repository

This repository contains ~~symlinks~~ [hard link][1], to my dotfiles. and [bound mounts][2] to my dotfile directories. created w/

```sh
ln source_file link_file

mkdir mount_point_diretory
mount -o bind source_directory mount_point_diretory
```


[1]:https://stackoverflow.com/a/24275394/16953460
[2]:https://unix.stackexchange.com/a/198591/494966