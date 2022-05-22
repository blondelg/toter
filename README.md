# Toter
One move to run selected text into a terminal

<img src="https://img.shields.io/badge/Made%20with-Bash-1f425f.svg"></img>

![demo](./demo.gif)

# How to use

* Install
* Link a keyboard shortcut to `toter -r` command
* Highlight a terminal command somewhere (browser, notebook, terminal ...)
* Hit the keyboard shortcut

# Install
## Debian

`sudo dpkg -i toter_1.0.1.deb` or `sudo apt install ./toter_1.0.1.deb`

check if install is done well:

```shell    
$ toter -v
toter 1.0.1 
```

## Other
Script is in *usr/bin*
install *xsel* as dependency

## Configure
Generate a config file
`toter -c`

Update config file with your favourite text editor
`~/.toter.conf`