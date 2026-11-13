# Notices

Kadath is licensed under the PolyForm Noncommercial License 1.0.0
(LICENSE.md): free for personal and other noncommercial use. Commercial use
needs a separate licence from the copyright holder.

Required Notice: Copyright 2026 v-sklv (https://github.com/V-SKLV). Kadath. Licensing requests: open an issue in the project's GitHub repository.

Kadath is an independent project. It is not affiliated with, endorsed by or
sponsored by Bambu Lab. "Bambu Lab" and the printer and AMS model names are
trademarks of their owners and are used only to say which printers it works
with.

## Third-party software in the firmware

| Library | Licence |
|---|---|
| TFT_eSPI (Bodmer), in `lib/TFT_eSPI` with a small patch (`KADATH_PATCH.md`) | FreeBSD |
| ArduinoJson (Benoit Blanchon) | MIT |
| PubSubClient (Nick O'Leary) | MIT |
| NimBLE-Arduino (h2zero) | Apache-2.0 |
| ESPAsyncWebServer, AsyncTCP (ESP32Async) | LGPL-3.0 |
| Adafruit AHTX0 | BSD |
| VL53L0X (Pololu) | MIT (derived from ST's API, see its licence) |
| Arduino core for ESP32, ESP-IDF (Espressif) | LGPL-2.1 / Apache-2.0 |
| Open Sans (Steve Matteson): the Cyrillic letters of fonts 2 / 4, `include/cyrillic_glyphs.h`, `tools/fonts/` | SIL Open Font License 1.1 |

The LGPL libraries stay under their own licence. Their full source and this
project's source are public, so a user can change them and build their own
firmware.

## Data not included

Bambu Lab's HMS / error explanations are downloaded from Bambu Lab's own
server at setup (tools/sentinel_bridge/error_db.py) and are not part of
this repository.
