# Bn Arch Repository

A personal Arch Linux repository maintained by **BnSplits** (AKA me).
This repository provides modified versions of existing Arch packages, built to better fit specific use cases or workflows.

---

## Repository Setup

To use this repository, add the following lines to your `/etc/pacman.conf`:

```ini
[bn-arch-repo]
SigLevel = Optional TrustAll
Server = https://bnsplits.github.io/bn-arch-repo/$arch
````

Then update the package databases:

```bash
sudo pacman -Sy
```

You can now install packages directly from this repository using `pacman`.

---

## Packages

### mpv-bn

**Base package:** [mpv](https://archlinux.org/packages/extra/x86_64/mpv/)
**Modification:** Uses the `umpv` wrapper script instead of launching `mpv` directly.
This allows mpv to be started through the `umpv` helper, which provides improved desktop integration and argument handling.

---

## Notes

* All packages are built from source and may contain small adjustments for personal workflows.
* This repository is intended for personal or experimental use. Use at your own discretion.

---

**Maintainer:** [BnSplits](https://github.com/BnSplits)
**License:** Same as the upstream projects unless otherwise stated.
