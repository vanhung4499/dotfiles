# My config files for macOS [![Thanks](http://bit.ly/saythankss)](https://github.com/users/nikitavoloboev/sponsorship)

> Zsh, Karabiner, VS Code, Sublime, Neovim, Nix

![](https://i.imgur.com/e1Ei3b1.jpg)

> Using [screenfetch](https://github.com/KittyKatt/screenFetch) to get OS details.

![](https://i.imgur.com/li5tXYp.jpg)

> I prefer to use light themes during the day as it's easier to focus on the text. I have macOS switch between the themes between evening & day.

I don't actually split editors like above. I code with each window maximized. Sometimes I use iPad with Sidecar and chrome browser on the side (for web dev) but mostly use one screen (MacBook).

You can see my top used apps, Safari extensions and Alfred workflows [here](https://github.com/nikitavoloboev/my-mac-os).

## Clean install

1. Boot latest macOS version. Remember that username is the name you want the home folder to be (by default its first name & last name).
2. Go through [preferences](https://imgur.com/a/KoVAxFQ) & set everything up.
3. Download & install [apps I use](https://github.com/nikitavoloboev/my-mac-os).
4. Clone dotfiles & sync them.
5. [Sync settings](https://github.com/zenangst/Syncalicious) for apps I use.

## Setup & sync dotfiles

Take a look at [install](install) shell script. It will install [brew](https://brew.sh), [go](https://go.dev) & [mage](https://github.com/magefile/mage).

Run it with `./install`. As part of the script it will run `mage setup`. Take a look at [magefile.go](magefile.go) `Setup` function to see what it will do.

You can also run `mage` alone to see what commands you can run with descriptions of them.

In short, it will create appropriate symlinks pointing at files in `~/.dotfiles`. It is assumed that the dotfiles repo is placed there.

It will also install CLI tools & apps.

## Interesting dotfiles

[Here](https://wiki.nikitavoloboev.xyz/unix/dotfiles) are dotfiles I got many ideas from and liked. I also mention [Nix configurations I liked](https://wiki.nikitavoloboev.xyz/operating-systems/linux/nixos).

## Contributing

[Suggestions](../../issues/) on how I can improve the these dotfiles or suggestions of new and awesome tools are welcome.

## Thank you

You can support me on [GitHub](https://github.com/users/nikitavoloboev/sponsorship) or look into [other projects](https://nikitavoloboev.xyz/projects) I shared.

[![MIT](https://img.shields.io/badge/license-MIT-0a0a0a.svg?style=flat&colorA=0a0a0a)](license) [![Twitter](http://bit.ly/nikitatweet)](https://twitter.com/nikitavoloboev)
