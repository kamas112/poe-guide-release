# Third-party notices

PoE 길잡이 bundles or uses the following. Their licenses apply to those parts.

| Component | Use | License |
|---|---|---|
| [ooz](https://github.com/powzix/ooz) via [pyooz](https://github.com/zao/pyooz) | Oodle decompression of the player's own game files (first run) | GPL-3.0 |
| [dat-schema](https://github.com/poe-tool-dev/dat-schema) (`schema.min.json`) | layout of the game's data tables | MIT (below) |
| Python 3.13 | runtime | PSF License |
| NumPy, SciPy | image / geometry math | BSD-3-Clause |
| Pillow | screen capture, images | MIT-CMU (HPND) |
| OpenCV (opencv-python) | image matching | Apache-2.0 |
| PyInstaller bootloader | the portable exe | GPL-2.0 with bootloader exception |

Not bundled: no file of Path of Exile. The first run reads the player's own installed Kakao client (read-only) and
downloads the passive tree export from Grinding Gear Games' public repository
[grindinggear/skilltree-export](https://github.com/grindinggear/skilltree-export). For the gem vendors (not in the
game files) it downloads `quests.json` of [exile-leveling](https://github.com/HeartofPhos/exile-leveling) (MIT, by
HeartofPhos), whose vendor lists come from the [Path of Exile Wiki](https://www.poewiki.net). Path of Exile is a
trademark of Grinding Gear Games; this is an unofficial fan tool.

## dat-schema (MIT)

MIT License

Copyright (c) 2021 Alexander Drozdov

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
