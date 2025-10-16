# Bn Arch Repository

A personal Arch Linux repository maintained by **BnSplit** (AKA me).

---

## Repository Setup

To use this repository, add the following lines to your `/etc/pacman.conf`:

```ini
[bn-arch-repo]
SigLevel = Optional TrustAll
Server = https://bnsplits.github.io/bn-arch-repo/$arch
```

Then update the package databases:

```bash
sudo pacman -Sy
```

You can now install packages directly from this repository using `pacman`.

---

## Packages

- [mpv-bn](https://github.com/BnSplits/mpv-bn)
- [chromafade](https://github.com/BnSplits/chromafade)
- [chromapick](https://github.com/BnSplits/chromapick)
- [hypr-go-to-workspace](https://github.com/BnSplits/hypr-go-to-workspace)
- [hypr-move-to-workspace](https://github.com/BnSplits/hypr-move-to-workspace)
- [anime-dive](https://github.com/BnSplits/anime-dive)
- packettracer-bn (PKGBUILD only)

---

## Notes

- All packages are built from source and may contain small adjustments for personal workflows.
- This repository is intended for personal or experimental use. Use at your own discretion.

---

**Maintainer:** [BnSplits](https://github.com/BnSplits)

**License:** Same as the upstream projects unless otherwise stated.
