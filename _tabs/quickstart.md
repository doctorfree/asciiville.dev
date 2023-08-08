---
layout: post
post_style: page
icon: fas fa-info-circle
toc: false
order: 2
---

- Install the latest Arch, Debian, macOS, RPM, or compressed tar archive format installation package from the [Asciiville Releases](https://github.com/doctorfree/Asciiville/releases) page
- Run the `ascinit` command
  - Must be done as a normal user with `sudo` privilege
  - Run `ascinit -c` to perform a console initialization (no graphical utilities)
- Initialize the command line Twitter client by invoking the `rainbowstream` command and authorizing the app to access your Twitter account
- Execute the `asciiville` command in interactive menu mode by running `asciiville -i`
- See the [online asciiville man page](https://github.com/doctorfree/Asciiville/wiki/asciiville.1) or `man asciiville` for different ways to invoke the `asciiville` command

The `asciiville` command can simply take ascii art filenames as arguments
and it will display them. The full filename isn't even necessary, it will
try to figure out what you mean. For example, to test whether your Asciiville
installation is working, try the command:

```console
asciiville Waterfalls/wallhaven-r768vq
```

This should display a waterfall rendered with characters as ascii art.
