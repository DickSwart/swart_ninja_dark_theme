# Swart Ninja Dark Theme

[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg?style=for-the-badge)](https://github.com/custom-components/hacs)

## Screenshots

### Overview of some of Home Assistant native controls.

![Theme - Overview](https://raw.githubusercontent.com/DickSwart/swart_ninja_dark_theme/master/docs/theme-overview.png)

![Theme - Map](https://raw.githubusercontent.com/DickSwart/swart_ninja_dark_theme/master/docs/theme-livingroom.png)

### Notifications

![Theme - Logbook](https://raw.githubusercontent.com/DickSwart/swart_ninja_dark_theme/master/docs/theme-notifications.png)

### Logbook

![Theme - Logbook](https://raw.githubusercontent.com/DickSwart/swart_ninja_dark_theme/master/docs/theme-logbook.png)

### History

![Theme - History](https://raw.githubusercontent.com/DickSwart/swart_ninja_dark_theme/master/docs/theme-history.png)

### Developer Tools

![Theme - Developer Tools](https://raw.githubusercontent.com/DickSwart/swart_ninja_dark_theme/master/docs/theme-developer-tools.png)

### Configuration

![Theme - Configuration](https://raw.githubusercontent.com/DickSwart/swart_ninja_dark_theme/master/docs/theme-configuration.png)

### Profile

![Theme - Profile](https://raw.githubusercontent.com/DickSwart/swart_ninja_dark_theme/master/docs/theme-profile.png)

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