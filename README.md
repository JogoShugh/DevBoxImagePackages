DevBoxImagePackages
===================

To install all this software into a clean baseline computer, first install Chocolatey from Powershell by typing:

```powershell
iex ((new-object net.webclient).DownloadString('https://chocolatey.org/install.ps1'))
```
Then, clone this repository, and open a new Powershell window and navigate to the cloned folder.

Type:

`choco install packages.config`

There may be failures. If we determine unreliable packages, we can move them toward the bottom so that reliable packages can be easily refreshed without having to sit there and manually download and install those.

See full docs here: https://github.com/chocolatey/chocolatey/wiki/CommandsInstall
