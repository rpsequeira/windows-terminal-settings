# windows-terminal-settings

## Requirements

Install Powershell Core

## Steps

```
Install-Module posh-git -Scope CurrentUser
Install-Module oh-my-posh -Scope CurrentUser
```

```
Install-Module -Name PSReadLine -AllowPrerelease -Scope CurrentUser -Force -SkipPublisherCheck
```

Then run "notepad $PROFILE" and add these lines to the end:

```
Import-Module posh-git
Import-Module oh-my-posh
Set-PoshPrompt -Theme iterm2
```

Install font CaskaydiaCove Nerd Font from https://github.com/ryanoasis/nerd-fonts/releases .

Based on Scott Hanselman's How to make a pretty prompt in Windows Terminal with Powerline, Nerd Fonts, Cascadia Code, WSL, and oh-my-posh (https://www.hanselman.com/blog/how-to-make-a-pretty-prompt-in-windows-terminal-with-powerline-nerd-fonts-cascadia-code-wsl-and-ohmyposh) and Taking your PowerShell prompt to the next level with Windows Terminal and Oh my Posh 3 (https://www.hanselman.com/blog/taking-your-powershell-prompt-to-the-next-level-with-windows-terminal-and-oh-my-posh-3).
