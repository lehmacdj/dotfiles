# dotfiles
A starting point for your own set of shell configuration.

## Motivation
Lots of people have fancy dotfiles repositories.
When I tried to make my own I found the task very daunting and didn't fine any of the ready made solutions satisfactorily customizable for what I wanted to do.
Furthermore I found it quite difficult to figure out how to build my own efficient system.
Every solution I did find was already heavily customized and featured way more features than I could every understand what they do.
This is an attempt to implement exactly what I would have wanted to find when I set out on my journey to craft my ultimate dotfiles repository and management system and I think it is the perfect starting point for almost anyone to use to start hacking together their own environment.

# Getting Started
1. First you will need to fork this repository. Go do that!
2. Are you reading this file from the fork?
3. Clone this repository (replace your username in the command below):

```
git clone https://github.com/<your-username-here>/dotfiles .dotfiles
```
<ol start="4">
<li>Run the installation script.</li>
</ol>

```
.dotfiles/install
```
<ol start="5">
<li>That's it!</li>
</ol>

## Adding Your Own Stuff
Here is how to extend this configuration in several different examples by example.

### Add an alias to shell configuration
### Add configuration for a different kind of shell
### Add a new tool
### Add a function

## Documentation
These dotfiles document themselves really well.
Every file has tons and tons of comments to help describe what every part of the code does.
Here is an overview of what is included in this set of configuration:

+ sane bash defaults
+ basic git configuration
+ a simple vimrc

## Why don't you include configuration for X in this repository?
It is very likely that I didn't think that X was very important for the ordinary case of someone using the shell.
Here is the answer for a few specific Xs:

+ **zsh** -
    Since bash is the default shell on every (maybe only almost every) system I decided that most users will not want zsh configuration at first.
    When someone is ready to use zsh they probably have enough experience that they are ready to figure out what they need from scratch.
    Plus zsh includes its own useful autoconfig that helps out a lot.
+ **tmux** -
    There really just isn't that much to configure here.
    If you think there should be tmux configuration here: send me a pull request or open an issue about it and we can discuss what should be put in the configuration.
+ **neovim** -
    Neovim already ships with much much stronger defaults than vim so it isn't nearly as necessary.
    In addition to that like with zsh I figure that most people using vim will probably start with vim and not neovim and therefore it isn't nearly not as necessary.
+ **emacs** -
    I use vim and therefore don't know what needs to be in a beginners emacs configuration.
    I would be open to adding it if anyone wants to send me a pull request; I'm not trying to fight the holy war of vim > emacs (although that is definitely true).
+ **Any others** -
    Open a pull request and then I can either add it to this list or add it to the repository if it is important enough.

## Contributing
Have ideas about what would make this repository better?
Want to add some sane defaults for some tool that is not currently included in this repository?
Submit a pull request to the `dev` branch.
Changes accepted to the `dev` branch will be rolled into the master branch for new cli users to profit from frequently.
