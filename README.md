# Dotfiles & environment

System Info
- Windows 11

Clone this repo into your `X:\Envs\Github\dotfiles` or any path you find appropiate
Then copy these dotfiles which are meant to be placed directly into your `USER` directory like so `C:\Users\jpokan`

### Software
General overview of the software required

Usually installed using their respective installers, optionally you can install them using winget https://github.com/microsoft/winget-cli/issues/3652 update winget if you have an issue

Git Bash
- https://git-scm.com/download/win
`winget install --id Git.Git -e --source winget`

Starship
- https://starship.rs/guide/#%F0%9F%9A%80-installation
`winget install --id Starship.Starship`

Neovim
- https://github.com/neovim/neovim/blob/master/INSTALL.md
`winget install Neovim.Neovim`
    - after installing neovim, you might want to check https://github.com/jpokan/nvim-config for setup instructions

Nvm for windows
- https://github.com/coreybutler/nvm-windows
    - following steps include installing yarn

Pyenv for windows
- https://github.com/pyenv-win/pyenv-win
    - mainly used for "masterkey" project


Sunbather colorscheme for windows terminal, paste this on your windows terminal JSON file
```json
{
    "background": "#080808",
    "black": "#929292",
    "blue": "#97BEDC",
    "brightBlack": "#BDBDBD",
    "brightBlue": "#B1D8F6",
    "brightCyan": "#1AB2A8",
    "brightGreen": "#BDDEAB",
    "brightPurple": "#FBDAFF",
    "brightRed": "#FFA1A1",
    "brightWhite": "#FFFFFF",
    "brightYellow": "#FFDCA0",
    "cursorColor": "#FFA560",
    "cyan": "#00988E",
    "foreground": "#DEDEDE",
    "green": "#94B979",
    "name": "Sunbather",
    "purple": "#E1C0FA",
    "red": "#E27373",
    "selectionBackground": "#474E91",
    "white": "#DEDEDE",
    "yellow": "#FFBA7B"
}
```

