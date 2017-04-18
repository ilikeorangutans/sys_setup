# sys_setup

Sets up a workstation with my commonly used tools and configurations. Configurations are sourced from github.com/ilikeorangutans/dotfiles.

## Prerequesites

* ansible

## Getting It

```
mkdir -p ~/src/github.com/ilikeorangutans
cd ~/src/github.com/ilikeorangutans
git clone git@github.com:ilikeorangutans/sys_setup.git
```

## Executing

Run like so:

```
$ ansible-playook -K workstation.yml
```
