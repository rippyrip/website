# Connecting

Connect to irc.rippy.rip (or specify a server if you prefer) on port 6697 with SSL.

## Servers

* irc.rippy.rip is a round-robin of all servers
* us.rippy.rip for our US-based server
* eu.rippy.rip for our EU-based server

All our servers have SSL certificates that are valid for their hostname and the round-robin domain.

## Client-specific instructions

### mIRC

`/server irc.rippy.rip:+6697`

### Hexchat

`/server -ssl irc.rippy.rip 6697`

### XChat

Don't use XChat, it has been discontinued.

### irssi

`/server add -ssl -ssl_verify -network rippy -port 6697 irc.rippy.rip`

### Weechat

`/server add rippy irc.rippy.rip/6697 -ssl`
