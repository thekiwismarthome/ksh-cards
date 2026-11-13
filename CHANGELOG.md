# Changelog

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
