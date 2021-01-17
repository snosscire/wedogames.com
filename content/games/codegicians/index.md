+++
title = "Codegicians"
date = 2017-06-05
[extra]
url_sceneorg = "https://files.scene.org/view/parties/2017/birdie17/gamedev/120-snosscire-codegicians.zip"
+++
Two players fight to the death inside *the code*.

The ability to walk has since long been forgotten inside
this digital world therefore players teleport themselves
to different positions within the map.

The world is constructed by an underlying code (you can view
the code by pressing `F1`). Teleportation within the world is
performed by using the VIM program. The VIM program has been
adapted for the best user experience through centuries
and therefore can be fully navigable only using
the keyboard.

- `g`+`g` - move to top of map
- `Shift`+`g` - move to bottom of map
- `h` - move one step left
- `l` - move one step right
- `k` - move one step up
- `j` - move one step down
- `$number` then `Shift`+`g` - move to row $number
- `0` - move to start of line
- `Shift`+`4` or `AltGr`+`4` - move to end of line
- `Shift`+`h` - move to top of screen
- `Shift`+`m` - move to middle of screen
- `Shift`+`l` - move to bottom of screen
- `w` - move forwards to the start of next word
- `e` - move forwards to the end of next word
- `b` - move backwards to the start of previous word

Players kill each other using *the code*. To kill another
player first target the player with `n` then put your
VIM program in "insert mode" (press `i` or `Insert`).
This will open up the editor window. Enter the words
presented in the editor window to inflict harm on your
opponent.

By default Codegicians will connect to the game server
`wedogames.se`. To run your own server run:

```
./Codegicians_DedicatedServer.x86_64
```

The server will listen on port 46337 so be sure to have
this port opened in your firewall.

To make the game client connect to your server modify
the configuration file `config.txt`.

Released at [Birdie 17](https://www.birdie.org/en/).

Code by [snosscire](https://github.com/snosscire/).
Gfx from [OpenGameArt.org](https://opengameart.org/).