# toggleproxy
I found no tools to do that for me, so I made this. Not a masterpiece, but it WORKS.
## Instruction (how-to-use):
put the `.conf` file in `~/.config/toggleproxy.conf` and modify it as your need, for example, to create a new profile, see this [example](https://github.com/Aryangh1379/toggleproxy/commit/5e7ef2fd94ba0f215e9367a0d27e8eafcbbcef78)
If you only want to use socks proxy settings, you can delete the http, https, ftp lines in the config.
after configuration, to switch your profile, enter: 
```
$ toggleproxy [your-profile-in-here]
```
or to turn off the proxies:
```
$ toggleproxy none
```
and your Gnome proxy settings will be unset.

###fun
