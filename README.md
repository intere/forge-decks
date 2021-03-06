# Decks

This is a repo of various decks that I play / play against (mostly modern) via Forge Desktop.  In addition to that, I've authored a script that lets me clone this repo onto a system and then run a script (`hookup.sh`) that will make itself the decks directory (via a symlink) and allow me to source control all of my decks.  Now I can ensure I keep all of my decks in one place and I can load them onto every machine very easily.

## Usage
```bash
mkdir ~/magic
cd ~/magic
git clone https://github.com/intere/forge-decks
./hookup.sh
```

It should produce some output like this:
```bash
I've created a symlink: '/Users/einternicola/Library/Application Support/Forge/decks' now points to '/Users/einternicola/git/decks'
On branch master
nothing to commit, working tree clean
```


## Forge
* [Development Process](https://www.slightlymagic.net/wiki/Forge:How_to_Get_Started_Developing_Forge#Bleeding_Edge_Build_Instructions)
* [Download Builds](https://www.slightlymagic.net/forum/viewtopic.php?f=26&t=468)
* [Forge Forum](https://www.slightlymagic.net/forum/viewtopic.php?f=26&t=468)
