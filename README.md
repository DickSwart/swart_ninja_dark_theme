# Swart Ninja Dark Theme

[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg?style=flat-square)](https://github.com/custom-components/hacs)
![GitHub](https://img.shields.io/github/license/dickswart/swart_ninja_dark_theme?style=flat-square)
[![homeassistant_community](https://img.shields.io/badge/HA%20community-forum-orange?style=flat-square)](https://community.home-assistant.io/t/share-your-themes/22018/260?u=dickswart)
![Travis (.com)](https://img.shields.io/travis/com/DickSwart/swart_ninja_dark_theme?style=flat-square)
![Yamllint](https://github.com/DickSwart/swart_ninja_dark_theme/workflows/Yamllint/badge.svg)
![HACS validation](https://github.com/DickSwart/swart_ninja_dark_theme/workflows/HACS%20validation/badge.svg)

If you like this theme please don't forget to ⭐ this repo.

## Screenshots

More screenshots can be found in the [repo docs](https://github.com/DickSwart/swart_ninja_dark_theme/tree/master/docs).

![Theme - Overview](https://raw.githubusercontent.com/DickSwart/swart_ninja_dark_theme/master/docs/theme-overview.png)

![Theme - Map](https://raw.githubusercontent.com/DickSwart/swart_ninja_dark_theme/master/docs/theme-livingroom.png)

## Installation

Add the following code to your `configuration.yaml` file (reboot required).

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```

### HACS

1. Go to the Community Store.
2. Search for `Swart Ninja Dark Theme`.
3. Navigate to `Swart Ninja Dark Theme` theme.
4. Press `Install`.
5. Go to services and trigger the `frontend.reload_themes` service.

### Manual

Clone this repository in your existing (or create it) `themes/` folder.

```bash
cd themes/
git clone https://github.com/DickSwart/swart_ninja_dark.git
```

Or using submodules:

```bash
cd themes/
git submodule add https://github.com/DickSwart/swart_ninja_dark.git
```

## Font

These fonts are licensed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).

- [Roboto](https://fonts.google.com/specimen/Roboto)
- [Open Sans](https://fonts.google.com/specimen/Open+Sans)

---

## Support and donate
If you like this theme please star this repo and share with your friends.
<p align="center">
<a href="https://www.buymeacoffee.com/swartninja" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/lato-black.png" alt="Buy Me A Coffee" style="height: 51px !important;width: 217px !important;" ></a>
</p>