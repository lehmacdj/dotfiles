# dotfiles
A simple set of dotfiles for people new to the command line interface (cli).

## Motivation
When I began using the cli I thought it was difficult to discover some of the most basic things that were necessary in order to create a good cli configuration.
This repository aims to be an effective minimal starting point that new cli users can use in order to jump start their progress without getting too much for free or copying too much that others wrote, therefore not understanding parts of their configuration.
It aims to be well documented and friendly to people who have little to no experience with the cli.

## Installation
I highly recommend forking this repository if you plan on using this configuration because an essential process of mastering the cli is modifying and updating your environment.
However if you choose not to or would simply like to try it out before you fork it for yourself simply:

```
git clone https://github.com/lehmacdj/dotfiles .dotfiles
```

If you did fork this repository then clone your fork to your home directory.


Next to symlink the various bits and pieces to their proper location do:

```
.dotfiles/install
```

## Screenshots
[Here go pictures of what various things look like when this is installed]


[They won't be very flashy though because as a whole this configuration isn't meant to be flashy.]

## Documentation
These dotfiles aim to be as well documented as possible, so if you are curious what a file is for open that file and see what it says.
However here is a short overview of what is included:
+ sane bash defaults
+ a few useful bash functions and aliases
+ sane zsh defaults
+ a few useful zsh functions and aliases
+ very basic tmux configuration
+ sane vim defaults
+ sane nvim defaults
+ useful git configuration
+ some additional more advanced configuration that is not enabled by default but that I would recommend to almost anyone
+ heaps of documentation to get you started choosing additional things to add to your cli

## Contributing
Have ideas about what would make this repository better?
Want to add some sane defaults for some tool that is not currently included in this repository?
Submit a pull request to the `dev` branch.
Changes accepted to the `dev` branch will be rolled into the master branch for new cli users to profit from frequently.
