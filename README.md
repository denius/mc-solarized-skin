# Midnight Commander Solarized 

This is a skin for [Midnight Commander][1] using the [Solarized palette][2].   
It is designed to be used with terminal emulators that use Solarized palette as   
their [ANSI colors][3].   

It is a fork from nkulikov/mc-solarized-skin however it was rewriten from   
scratch based on [GoTaR][4] MC skin. The file highliting was adjusted to be as   
close as possible to the Solarized [dircolors.ansi-universal][5].   

Some info on skin writing is available on [MC wiki][6],   
yet it's usually takes a PHD to understand what's going on.   
And since I'm senile and lazy, I don't want to keep going to external references.   

Also, it seems it's bloody scattered all over the place, and one has to collect tiny,   
and I do mean TINY, and sometimes outdated, pieces of information to form something complete.   
That's why I took the libery to comment EVERYTHING, just in case.   

# Screenshot

![Midnight Commander Solarized](screenshot.png)

# Installation and Usage

Note you might need mc > 4.7.5 for this scheme to work   
See [MC install script][7] on how to compile from source.   

Clone the repostiry into $HOME/.mc/lib/mc-solarized,   
and define MC_SKIN in .bashrc, .zshrc or .whatnotrc:   

```bash
mkdir -p $HOME/.mc/lib/
git clone https://github.com/iwfmp/mc-solarized-skin.git $HOME/.mc/lib/
echo "MC_SKIN=$HOME/.mc/lib/mc-solarized/solarized.ini" >> .zshrc
```
# Color reference
| SOLARIZED | HEX     | TERMCOL       |   
|-----------|:--------|:--------------|   
| base03    | #002b36 | brightblack   |   
| base02    | #073642 | black         |   
| base01    | #586e75 | brightgreen   |   
| base00    | #657b83 | brightyellow  |   
| base0     | #839496 | brightblue    |   
| base1     | #93a1a1 | brightcyan    |   
| base2     | #eee8d5 | white         |   
| base3     | #fdf6e3 | brightwhite   |   
| yellow    | #b58900 | brown         |   
| orange    | #cb4b16 | brightred     |   
| red       | #dc322f | red           |   
| magenta   | #d33682 | magenta       |   
| violet    | #6c71c4 | brightmageta  |   
| blue      | #268bd2 | blue          |   
| cyan      | #2aa198 | cyan          |   
| green     | #859900 | green         | 

[1]: https://www.midnight-commander.org                                "Midnight Commander"
[2]: http://ethanschoonover.com/solarized                              "Solarized palette"
[3]: https://github.com/sigurdga/gnome-terminal-colors-solarized       "ANSI colors"
[4]: http://www.midnight-commander.org/nopaste/skin_parser/outdir      "GoTaR"
[5]: https://github.com/seebi/dircolors-solarized                      "dircolors.ansi-universal"
[6]: https://www.midnight-commander.org/wiki/doc/common/skins          "MC wiki"
[7]: https://github.com/iwfmp/midnight-commander/blob/master/install   "MC install script"
