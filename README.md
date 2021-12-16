# MultiMC package for Arch Linux

Avoid the AUR and use this instead. It is actually supported by the real MultiMC maintainers and community.

## How to install

You need to set up your Arch install to be able to build packages.

See instructions for that: https://wiki.archlinux.org/title/Makepkg#Usage

### Using git
If you have `git` installed, you can just clone the whole repository.

```
git clone https://github.com/MultiMC/multimc-pkgbuild.git
cd multimc-pkgbuild
makepkg -si
```

### Using wget
If you do not have `git` installed, you can use a downloader like `wget` or directly download the `PKGBUILD` using your browser.

```
mkdir multimc-pkgbuild
cd multimc-pkgbuild
wget https://raw.githubusercontent.com/MultiMC/multimc-pkgbuild/master/PKGBUILD
makepkg -si
```

## Issues?

Report issues [here](https://github.com/MultiMC/multimc-pkgbuild/issues).

Or talk to us on [Discord](https://discord.gg/multimc).
