# zed-config

My Zed settings. Extensions listed under `auto_install_extensions` install on first launch.

## Install

Close Zed, back up the existing config folder, then clone this repo in its place.

macOS / Linux:

```sh
mv ~/.config/zed ~/.config/zed.bak
git clone git@github.com:igor570/zed-config.git ~/.config/zed
```

Windows (PowerShell):

```powershell
Move-Item $env:APPDATA\Zed $env:APPDATA\Zed.bak
git clone git@github.com:igor570/zed-config.git $env:APPDATA\Zed
```

## Update

Commit and push from the config folder on any machine; `git pull` on the others.
