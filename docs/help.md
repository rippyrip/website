# Help

If you are having trouble connecting, double-check you are connecting to port 6697 and have enabled SSL. If the settings are definitely correct, check for updates for your IRC client – if it's very old it probably can't speak the right version of SSL. Do _not_ disable certificate checking to try to make it work!

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
