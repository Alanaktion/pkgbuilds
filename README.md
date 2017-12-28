pkgbuilds
=========
*A collection of PKGBUILD files I'm playing around with*

## Basics of creating a package
Create a [valid PKGBUILD](https://wiki.archlinux.org/index.php/PKGBUILD) file, then:

```bash
namcap PKGBUILD
makepkg --printsrcinfo > .SRCINFO
```

## Installing packages
Open the directory containing the PKGBUILD file, then:

```bash
makepkg -si
```

Most of these can also be found on the [AUR](https://aur.archlinux.org/).
