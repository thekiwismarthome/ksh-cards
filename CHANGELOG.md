# Changelog

## 1.2.0 (unreleased)

- **New `ksh-intercom-card`:** a Kiosk Satellite intercom button. The handset-and-waves icon shows this screen's intercom state; tapping it opens a popup listing the other kiosks, and tapping one calls it through Kiosk Satellite's own intercom. The popup also has hang up, answer, decline, do not disturb and volume.
- The intercom card finds its own screen: it reads the device name from the Kiosk Satellite app, so no `?kiosk=` is needed. Other browsers ask once and remember.

## 1.1.0

- **New `ksh-forecast-radar-card`:** next 24 hours and rain radar in one card, with a switch in the header, full-screen radar, and an automatic return to the forecast after 5 minutes (`radar_timeout`). Set `default_view: radar` to open on the radar.
- The hourly chart is now shared by `ksh-weather-hourly-card` and the new card, so both always look the same.

## 1.0.0

First release.

- **Icon cards:** 19 line-art device cards (`ksh-ceiling-light-card` … `ksh-ev-car-card`) plus `ksh-icon-card`, each with a visual editor.
- **Weather cards:** 11 modular cards: now, next 24 hours, 7-day, rain radar, wind, UV, air quality, humidity, pressure, sun & moon, tides.
- **Integration:** `ksh_cards` serves the cards and loads them on every dashboard; no Lovelace resources needed.
- **HACS:** installable as a custom repository (type Integration).
- **Theme:** `KSH`, with a muted-grey light mode and a true-black dark mode.
