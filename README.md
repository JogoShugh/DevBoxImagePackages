DevBoxImagePackages
===================

To install all this software into a clean baseline computer, install Chocolatey from Powershell by typing:

```powershell
iex ((new-object net.webclient).DownloadString('https://chocolatey.org/install.ps1'))
```
Then, clone this repository and as Administrator in a new Powershell window with the cloned folder, type:

`choco install packages.config`

See full docs here: https://github.com/chocolatey/chocolatey/wiki/CommandsInstall

There may be failures. If we determine unreliable packages, we can move them toward the bottom so that reliable packages can be easily refreshed without having to sit there and manually download and install those.
