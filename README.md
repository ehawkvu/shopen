# shopen - a POSIX shell file opener

shopen is meant to be a replacement for xdg-open, written
in POSIX shell.

Similar in vein to [sx-open](https://code.fleshless.org/fbt/sx-open)
but aims to support XDG Desktop files.

## Tested shells

shell       | working
---:        | --:
bash        | yes
dash        | yes
yash        | yes
mksh        | mostly; needs more testing
busybox ash | yes
zsh         | yes
