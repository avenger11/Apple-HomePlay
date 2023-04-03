![HomePlay](https://github.com/avenger11/Apple-HomePlay/blob/master/Repo-images/HomePlay%20Banner.png)

My take on Apple Home Dashboard Design for Home Assistant. (Work in Progress)

I'm running Home Assistant OS Supervised VM hosted on a NAS DS920+.
The Wall Mount tablet is a FireHD 10 from amazon running Fully Kiosk Browser.

I'm sharing my configuration there is no install button.
There is still a lot of work to be done, the dashboard appear aligned on my tablet but not perfect in browsers.

I use a swipe card to show the multiple stairs of the house.

![Dashboard](https://github.com/avenger11/Apple-HomePlay/blob/master/Repo-images/01.gif)

## Feature

- Day & Night theme support (NB: automation based on sun location)
- Support multiple floor by swaping between card
- Garbage card background become white when it's time :)
- Calendar integration
- "apps" support notification

![Night Dashboard](https://github.com/avenger11/Apple-HomePlay/blob/master/Repo-images/night01.png)

![Day Dashboard](https://github.com/avenger11/Apple-HomePlay/blob/master/Repo-images/day01.png)

The floor plan have been designed in [Sweet Home 3D](https://www.sweethome3d.com/) and edited.

### Weather background change based on condition and day/night (screenshot from weather app)

![Weather Variation](https://github.com/avenger11/Apple-HomePlay/blob/master/Repo-images/Weather%20Variations.png)

## Architecture

This is the keyplan for the layout.
![Architecture](https://github.com/avenger11/Apple-HomePlay/blob/master/Repo-images/architecture.png)

## Custom Cards from HACS
Ensure to install those custom card before using this configuration via HACS

- [Lovelace-Layout-Card](https://github.com/thomasloven/lovelace-layout-card) by Thomas loven.
- [Swipe-card](https://github.com/bramkragten/swipe-card) by Bram Kragten.
- [Button-card](https://github.com/custom-cards/button-card) by RomRider.
- [Lovelace-Card-mod](https://github.com/thomasloven/lovelace-card-mod) by Thomas loven
- [Atomic Calendar Revive](https://github.com/totaldebug/atomic-calendar-revive) by marksie1988
- [Kiosk Mode](https://github.com/NemesisRE/kiosk-mode) by NemesisRE
- [Clock weather card](https://github.com/pkissling/clock-weather-card) by pkissling

## Custom integration from HACS
- [Fontawesome](https://github.com/thomasloven/hass-fontawesome) by Thomas loven.
- [Browser_mod](https://github.com/thomasloven/hass-browser_mod) by Thomas loven.

## TODO List
- [ ] FIll the empty space on the left, potentially light on count, climat etc..
- [ ] Remove transition weather background and code
- [ ] Improve all popups
- [ ] Integrate Washer & Dryer Card
- [ ] Solve all resizing issues

## Credit

- inspired by the great work of [Mattias Persson](https://github.com/matt8707/hass-config) & [lukevink](https://github.com/lukevink/hass-config-lajv) 


If you'd like to support me and future projects:

:star2: Star my repo, if you like what you see :)

<a href="https://www.buymeacoffee.com/sebhome" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>


## Resource

Apple Icon
https://www.figma.com/file/PwWaGiMaSyrktcQRh7MxAD/SF-Symbols-4.0---SVG-Icons-(Community)?node-id=1498-49395&t=8xsPmha2AmVoMsAg-0
