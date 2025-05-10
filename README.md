# win11-termial-config

## Shell

[PowerShell](https://github.com/PowerShell/PowerShell)

## CLI tools

[zoxide](https://github.com/ajeetdsouza/zoxide?ysclid=mai8uvgczi820479217)

[fzf](https://github.com/junegunn/fzf)

[uv](https://docs.astral.sh/uv/)

[nvim](https://neovim.io/)

## Startup

`$PROFILE`
```
$env:Path += ";C:\Users\user\AppData\Local\Programs\oh-my-posh\bin"

oh-my-posh init pwsh --config "C:\Users\Arseny\AppData\Local\Programs\oh-my-posh\themes\emodipt-extend.omp.json" | Invoke-Expression

Invoke-Expression (& { (zoxide init powershell | Out-String) })

Set-Alias -Name np -Value C:\Windows\notepad.exe
```

## Schemes

`settings.json`
```
"schemes": 
    [
        {
            "background": "#1C1C1C",
            "black": "#3D352A",
            "blue": "#6495ED",
            "brightBlack": "#554444",
            "brightBlue": "#87CEEB",
            "brightCyan": "#B0C4DE",
            "brightGreen": "#88AA22",
            "brightPurple": "#996600",
            "brightRed": "#CC5533",
            "brightWhite": "#DDCCBB",
            "brightYellow": "#FFA75D",
            "cursorColor": "#E2BBEF",
            "cyan": "#B0C4DE",
            "foreground": "#DDEEDD",
            "green": "#86AF80",
            "name": "Arthur",
            "purple": "#DEB887",
            "red": "#CD5C5C",
            "selectionBackground": "#4D4D4D",
            "white": "#BBAA99",
            "yellow": "#E8AE5B"
        }
    ],
```
