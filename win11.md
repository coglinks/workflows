## Patches 

- Disable Nahimic audio
    - Refer to [Reddit comment](https://www.reddit.com/r/playnite/comments/vwf5vc/comment/ifq6rrt/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button)

## Uninstall

- Office 365 Co-pilot, MS Co-pilot

```
winget source remove msstore
```

```
powercfg.exe /hibernate on
```

## Install

#### WSL
- search bar search: Turn windows features on or off
    - enable HyprV
    - enable Windows Subsystem for Linux
- exec:
    - `wsl`
    - `wsl --install debian`

#### Other apps

```
winget install chrome playnite
```

```
winget install epicgames.epicgameslauncher
```

- [OFFICE 365](https://www.microsoft.com/en-us/microsoft-365/download-office#download)
