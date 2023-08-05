---
# the default layout is 'page'
icon: fas fa-info-circle
order: 3
---

## Asciiville Features

Asciiville integrations and extensions are aimed at the character
based terminal and console user. They enable easy to use seamlessly
integrated control of a variety of ASCII Art, animation, and utilities
in a lightweight character based environment.

At the core of Asciiville is the `asciiville` command which acts as
a front-end for a variety of terminal commands and `tmux` sessions.

The `asciiville` command can be used to display Ascii Art either
as a slideshow or interactively. For example:

```console
# Slideshow of Ascii Art in /usr/share/asciiville/art/Art/
asciiville -V Art
# Slideshow of Ascii Art in /usr/share/asciiville/art/Vintage/
asciiville -V Vintage
# Interactive display of Ascii Art in .../file1 and .../file2
asciiville file1 file2 ...
# Slideshow of Ascii Art in file1, file2, and file3
asciiville -V files file1 file2 file3
# Slideshow of Ascii Art files listed in /tmp/asciiart.txt
asciiville -V files=/tmp/asciiart.txt
```

Filenames provided to `asciiville`, either on the command line or in
a specified file, can be absolute paths to files; relative paths to files;
or relative paths to files in the Asciiville Ascii Art galleries folder.
Ascii Art filenames may be provided with or without the filename suffix
(e.g. `Friends/tux.asc` or `Friends/tux.asc.gz` or `Friends/tux`).

When viewing Ascii Art in display mode it is possible to enter 'browse/zoom'
mode by entering 'b' or 'z' at the keyboard. In this mode the currently
displayed art can be zoomed in and out.

For greater detail see the [documentation](https://asciiville.dev/documentation).

The `asciiville` command can also be used to invoke commands in a variety of ways:

* The lightweight character based system monitor, `btop`
* The lightweight character based web browser, `w3m`
* The lightweight character based mail client, `neomutt`
* The lightweight character based RSS feed reader, `newsboat`
* The lightweight character based FTP client, `cbftp`
* The lightweight character based music player, `mpcplus`
* The lightweight character based file manager, `ranger`
* The lightweight character based disk usage analyzer, `gdu`
* The lightweight character based journal app, `jrnl`
* The lightweight character based terminal UI for Reddit, `tuir`
* Featureful ASCII Art display including slideshow and zoom capabilities
* Character based ASCII Art and image to ascii conversion utility `jp2a`
* One or more terminal emulators running a command
* A tmux session
* A command line web search
* A zoomable map of the world
* Command line character based Twitter client
* Translate words and phrases from and to a wide variety of languages
* A network download/upload speed test
* The AAlib BB demo running in a tmux session (Debian based systems only)
* The ASCII text-based dungeon game `nethack` with Extended ASCII glyphs
* The `cmatrix` command that displays the screen from "The Matrix"
* Many text based applications and games
* ASCII Art creation tool `aewan`
* Display system info
* Display a random Pokemon
* Display the Phase of the Moon
* Display a weather report
* Display the MusicPlayerPlus or RoonCommandLine interactive menus
* Any character based client the user wishes to run
* Several asciimatics animations optionally accompanied by audio

Without arguments or with the `-i` argument, `asciiville` presents a set
of interactive menus that can be used to control its behavior.

Integration is provided for:

* [aewan](https://github.com/doctorfree/asciiville-aewan#readme), Ascii Art creation tool
* [btop](https://github.com/doctorfree/btop#readme), character based system monitor
* [cbftp](https://github.com/doctorfree/cbftp#readme), character based FTP client
* [ddgr](https://github.com/jarun/ddgr#readme), command line web search using DuckDuckGo
* [googler](https://github.com/jarun/googler#readme), command line web search using Google
* [jrnl](https://jrnl.sh/en/stable/), a simple command line journal application
* [khard](https://github.com/lucc/khard), address book for the Unix console
* [w3m](http://w3m.sourceforge.net/), another character based web browser
* [lynx](https://lynx.invisible-island.net/), character based web browser
* [mutt](http://www.mutt.org/), character based email client
* [neomutt](http://neomutt.org/), character based email client
* [neovim](https://neovim.io/), advanced open source screen-based text editor
* [newsboat](https://github.com/newsboat/newsboat), character based RSS feed reader
* [ranger](https://ranger.github.io/), character based file manager
* [tuir](https://gitlab.com/ajak/tuir/), terminal UI for Reddit
* [gdu](https://github.com/dundee/gdu#readme), character based disk usage analyzer
* [got](https://github.com/fedeztk/got), text based translation tool
* [mpcplus](https://github.com/doctorfree/MusicPlayerPlus/blob/master/mpcplus/README.md), featureful ncurses based Music Player client
* [mplayer](http://mplayerhq.hu/design7/info.html), a media player
* [asciimatics](https://github.com/peterbrittain/asciimatics) - automatically display a variety of character based animation effects
* [asciinema](https://asciinema.org/) - automatically create ascii character based video clips
* [rainbowstream](https://github.com/orakaro/rainbowstream) - command line character based Twitter client
    * See [the rainbowstream usage manual](https://rainbowstream.readthedocs.io/en/latest/#usage) to get started
* [endoh1](https://github.com/mame/winner/tree/main/2012/endoh1), ascii fluid dynamics simulation
* [mapscii](https://github.com/rastapasta/mapscii#readme), zoomable map of the world
* [cmatrix](https://github.com/abishekvashok/cmatrix), screen from "The Matrix"
* [nethack](https://en.wikipedia.org/wiki/NetHack), ASCII text dungeon game
* [ninvaders](https://en.wikipedia.org/wiki/Space_Invaders), ASCII text version of Space Invaders
* [tetris](https://en.wikipedia.org/wiki/Tetris), ASCII text version of Tetris
* [tmux](https://github.com/tmux/tmux/wiki), a terminal multiplexer
* [wttr.in](https://github.com/chubin/wttr.in), console-oriented weather report
* Enhanced key bindings for extended control of terminal windows
* Support for several terminal emulators
    * xfce4-terminal
    * gnome-terminal
    * kitty
    * tilix
    * cool-retro-term
* [MusicPlayerPlus](https://github.com/doctorfree/MusicPlayerPlus#readme), character based suite of commands to manage music server and player
* [RoonCommandLine](https://github.com/doctorfree/RoonCommandLine#readme), command line control of the Roon audio system over a local network

