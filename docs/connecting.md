# Connecting

Connect to irc.rippy.rip (or specify a server if you prefer) on port 6697 with SSL.

## Servers

* irc.rippy.rip is a round-robin of all (2) servers


## Client-specific instructions

### mIRC

`/server irc.rippy.rip:+6697`

### Hexchat

`/server -ssl irc.rippy.rip 6697`

### XChat

Don't use XChat, it has been discontinued. Hexchat is the up-to-date fork.

### irssi

`/server add -ssl -ssl_verify -network rippy -port 6697 irc.rippy.rip`

### Weechat

`/server add rippy irc.rippy.rip/6697 -ssl`
