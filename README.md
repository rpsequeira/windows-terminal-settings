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
Set-Theme Paradox
```

Install font Cascadia Code PL from https://github.com/microsoft/cascadia-code/releases .




Based on Scott Hanselman's How to make a pretty prompt in Windows Terminal with Powerline, Nerd Fonts, Cascadia Code, WSL, and oh-my-posh (https://www.hanselman.com/blog/how-to-make-a-pretty-prompt-in-windows-terminal-with-powerline-nerd-fonts-cascadia-code-wsl-and-ohmyposh).