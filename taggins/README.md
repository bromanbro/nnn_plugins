# Plugins for Taggins

Taggins is a lightweight command line application for creating and maintaining a list of descriptive tags for a file.

## Installation

If you have not already installed the taggins application it is available [here](https://github.com/bromanbro/taggins).

1. The nnn file manager locates plugins in ~/.config/nnn/plugins.  Simply copy the addtags and removetags plugins to this location.

2. In order to map the taggins plugins to hot keys add the following to your ~/.bashrc file:

```
export NNN_PLUG='t:addtags;T:removetags'
```

## Usage

Move over any file in nnn and enter hotkeys t to add tags or T to remove tags.  The screen will open up and display the tags that are currently on that file.  If you press enter without entering any text the command will leave the file untouched.  Therefore, if you just want to view the tags on a file you can use t and simply hit enter when done.
