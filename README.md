# Daylight Year

A single-file interactive view of solar geometry for any latitude and date.

Double-click `Daylight Year.bat`. It unpacks the page to your temp folder and opens it in your default browser.

## What it shows

- **Live clock and weather** for the chosen place (weather from Open-Meteo, no API key).
- **Sun path** for the selected day, the Earth side-on, and the 24-hour colour strip.
- **Around you:** a sky dome with the sun, the moon's track, and stars that turn with the Earth.
- **Earth from space:** a textured 3D Earth with day and night, clouds, your location, a satellite view with a window frame, and a moon at its real distance.
- **Year views:** every minute of the year, daylight by latitude, and the daily change in daylight.
- **Full-screen stat views:** each stat opens a picture of its own.

## Notes

- The 3D Earth and the weather need an internet connection. The rest works offline.
- Times use standard time for each place, with no daylight-saving shift.
- The sun and moon positions are approximate (the moon to about a degree).

## Outside services

The page contacts these services when it runs:

- **Open-Meteo** (weather): receives the coordinates of the chosen place.
- **jsDelivr** (3D library and Earth images).
- **Google Fonts** (typefaces).

Your saved location is kept only in your browser.
