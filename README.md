# dotfiles

My developer/productivity-oriented configurations for MacOS. Eyeballed, untested, and possibly disasterous.

## Includes, but is not limited to:

- [Oh My Zsh](https://ohmyz.sh/) with [Powerlevel10k](https://github.com/romkatv/powerlevel10k)
- [iTerm2](https://iterm2.com/)
- [Alfred](https://www.alfredapp.com/)
- "Mini-apps": [AltTab](https://alt-tab-macos.netlify.app/), [Rectangle](https://rectangleapp.com/), [Flux](https://justgetflux.com/), etc.
- Apps: 1Password, Spotify, Discord, Notion, etc.
- Gloabal NPM installations via `.npmfile`

# Setup

 > :warning: As of 3/4/2023, this has not been tested on a new machine. Proceed with caution.
 
Ensure you have MacOS, Homebrew, and perhaps some other things I forgot to mention.

1. *Copy* all files to the user directory, e.g. `/Users/quinnouyang`. **Do not clone the repository directly there.**
2. Review `Brewfile` and comment/uncomment as needed, likely avoiding already-installed software. Then execute `brew bundle install`.
3. Manually do a bunch of crap. Good luck lol:)
