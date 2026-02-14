# pills
OmegaLinux NEXT "Pills" package repository, mainly used in the archiso configs
# Setting up
Add this to your pacman.conf file, specially right above the main repos:
```
[pills]
SigLevel = Optional TrustAll
Server = https://ohjhas.github.io/pills/$arch
```
