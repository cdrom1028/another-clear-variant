# another-clear-variant
Another variant of Clear Theme Dark for Home Assistant with rounded corners

# Clear Theme Dark
[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg)](https://github.com/custom-components/hacs)
[![GitHub last commit](https://img.shields.io/github/last-commit/naofireblade/clear-theme-dark)](https://github.com/naofireblade/clear-theme-dark)

This is a theme for [Home Assistant](https://www.home-assistant.io/). You can install it [manually](#installation) or via [HACS](https://hacs.xyz/).

## Installation

1. Copy the folder `themes` into your home-assistant folder
2. Add this under the section `frontend` in your `config.yaml`:
    ```
    frontend:
      themes: !include_dir_merge_named themes
    ```
3. Restart Home Assistant
4. Enable the theme in your user profile (bottom left in Home Assistant)
 
## Screenshot
![image](https://user-images.githubusercontent.com/12081369/68703769-8b119600-058b-11ea-9cf3-2aa01482e92f.png)

## Optional custom cards from the screenshot
- [Button Card](https://github.com/rodrigofragadf/lovelace-cards/tree/master/tiles-card)
- [Animated Weather Card](https://github.com/bramkragten/custom-ui/tree/master/weather-card)
- [Graph Card](https://github.com/kalkih/mini-graph-card)
- [Slim Header](https://github.com/maykar/compact-custom-header/)

## Known problems
- Text in the logbook is barely readable (not fixable at the moment)

> Feel free to leave any feedback [here](https://github.com/naofireblade/clear-theme-dark/issues).

## Donations
If you like this theme, I would be forever grateful for your support:

<a href="https://www.buymeacoffee.com/UkeoJiV" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-red.png" alt="Buy Me A Coffee" style="height: 51px !important;width: 217px !important;" ></a>

## Attributions
- Background Image based on an image from [unknown](https://visme.co/blog/simple-backgrounds/)
