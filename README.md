This a sub-repo of [Neard project](https://github.com/crazy-max/neard) involving HostsEditor tool bundles.

## Installation

* Download and install [Neard](https://github.com/crazy-max/neard).
* If you already have installed Neard, stop it.
* Download [a HostsEditor bundle](#download).
* Extract archive in `neard\tools\hostseditor\`. Directory structure example :

```
[-] neard
 | [-] tools
 |  | [-] hostseditor 
 |  |  | [-] hostseditor1.1.0.0
 |  |     | neard.conf
```

* Edit the `neard.conf` file and replace the key `hostseditorVersion` with the correct version.
* Start Neard.

## Download

![](https://raw.github.com/crazy-max/neard-tool-hostseditor/master/img/star-20160403.png) : Default bundle on Neard.

|                         | HostsEditor release date | Neard release | Download |
| ------------------------|:------------------------:|:-------------:|:--------:|
| **HostsEditor 1.1.0.0** ![](https://raw.github.com/crazy-max/neard-tool-hostseditor/master/img/star-20160403.png) | 2008/10/29 | [r1](https://github.com/crazy-max/neard-tool-hostseditor/releases/tag/r1) | [neard-hostseditor-1.1.0.0-r1.zip](https://github.com/crazy-max/neard-tool-hostseditor/releases/download/r1/neard-hostseditor-1.1.0.0-r1.zip) |

## Sources

* https://hostseditor.codeplex.com/

## Contribute

If you want to contribute to this bundle and create new bundles, you have to download [neard-dev](https://github.com/crazy-max/neard-dev) in the parent folder of the bundle.
Directory structure example :

```
[-] neard-dev
 | [-] build
 |  |  | build-commons.xml 
[-] neard-tool-hostseditor
 |  | build.xml
```

To create a new bundle :
* Do not forget to increment the `build.release` in the `build.properties` file.
* If you want you can change the `build.path` (default `C:\neard-build`).
* Open a command prompt in your bundle folder and call the Ant target `release` : `ant release`.
* Upload your release on a file hosting system like [Sendspace](https://www.sendspace.com/).
* Create an [issue on Neard repository](https://github.com/crazy-max/neard/issues) to integrate your release.

## Issues

Issues must be reported on [Neard repository](https://github.com/crazy-max/neard/issues).<br />
Please read [Found a bug?](https://github.com/crazy-max/neard#found-a-bug) section before reporting an issue.
