
## 🏗 How to Install

Simply run the following interactive bootstrap command, and you should be all set 👍

- **Windows** _(Note: This script REQUIRES `pwsh` > `v7.1`)_

```pwsh
Set-ExecutionPolicy Bypass -Scope Process -Force; Invoke-Expression ((New-Object System.Net.WebClient).DownloadString('https://raw.githubusercontent.com/ayamir/nvimdots/HEAD/scripts/install.ps1'))
```

- **\*nix**

```sh
if command -v curl >/dev/null 2>&1; then
    bash -c "$(curl -fsSL https://raw.githubusercontent.com/seriktest/nvimdots/HEAD/scripts/install.sh)"
else
    bash -c "$(wget -O- https://raw.githubusercontent.com/seriktest/nvimdots/HEAD/scripts/install.sh)"
fi
```

It's strongly recommended to read [Wiki: Prerequisites](https://github.com/ayamir/nvimdots/wiki/Prerequisites) before starting, especially for \*nix users.
