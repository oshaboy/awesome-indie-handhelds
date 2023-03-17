Cheap microcontrollers and bitmap screens have led to a new class of game console. Which I nickname "Hobby Handhelds" or "Indie Handhelds". Unlike traditional handheld game consoles these systems are meant to run games made by hobbyists and easily programmed by the user. I decided to compile a list of them.

## Bitmap Screen Games
| Name | Processor | RAM | Resolution | Color | Sound | Languages | Flash Size | Storage | Price | Schematic Available | URL |
| ---- | --------- | --- | ---------- | ----- | ----- | ---------- | ---------- | ---------- | --- | ---------- | ---------- |
| 32blit   | STM32H750 (480 MHz Cortex M7) | 1 MiB |  320x240   | RGB | TBD |  C++, Lua  |  32 MiB | Micro SD | TBD  | TBD  |  https://32blit.com/ |
| Arduboy | ATMega 32u4 (16 MHz AVR)  | 2.5 KiB | 128x64 | 1-bit | 2x1-bit Buzzer| C/C++ (Arduino) | 32 KiB | 128 MiB Flash (FX Model Only) | 54 USD (Clones at Various Prices)| Yes | https://arduboy.com |
| Attiny Arcade   | ATtiny85 (20 MHz AVR) | 512 B  | 128x64  | 1-bit  |  1-bit Buzzer |  C/C++ (Arduino) | 8 KiB  | N/A  | 29.98 USD  | Yes  |  https://webboggles.com/attiny85-game-kit-assembly-instructions/ |
| Brainpad Arcade |  STM32F401 (84 MHz Cortex M4) | 96 KiB    | 160x128  | RGB  |1-bit Buzzer| VPL (MakeCode Arcade)  |  512KiB  |  N/A |  34.95 USD | No  |  https://www.brainpad.com/brainpad-family/arcade/ |
| Brainpad Pulse | SC13048Q (80 MHz Cortex M4) | 128 KiB |128x64    |1-bit   |1-bit Buzzer| VPL (MakeCode), C#, MicroPython  |  	220K  | N/A  | Quote  |  Yes | https://www.brainpad.com/brainpad-family/pulse/  |
| Dodo   | 65C02  (1 MHz)  | 32KiB | 128x64  | 1-bit   |1xBuzzer| C (CC65), 65C02 Assembly  | N/A  |  8 KiB FRAM | 199 USD  |  Yes |  http://www.dodolabs.io/ |
| Elecfreaks | ? (Some sort of STM32F4) | ? | 320x200 | RGB | 1-bit Buzzer | VPL (Makecode Arcade) | ? | N/A | 59.90 USD | No | https://www.elecfreaks.com/retro-arcade-for-education.html | 
| ESPboy  | ESP8266 (160 MHz Xtensa)   | 80 KiB  |  128x128 | RGB |1-bit Speaker| C/C++ (Little Game Engine, Arduino, Arduboy, Gamebuino META), Lua, BASIC, MicroPython, Z80 Assembly (Gameboy, ZX Spectrum), SChip-8  | 4 MiB  |  App Store | 99 USD  | Yes   | https://www.espboy.com/  |
|ESPlay Micro V2   |  ESP32 WROVER (2x240 MHz Xtensa) |  4MiB-8MiB  | 320x240  | RGB | UDA1334A (16-bit DAC) |  MicroPython, C/C++ (Arduino), Z80 Assembly (Gameboy (Color), Master System, Game Gear, Colecovision), 6502 Assembly (NES) | 4MiB   | Micro SD |  32.90 USD   | Yes  |  https://hackaday.io/project/166707-esplay-micro |
| Gamebuino/MAKERbuino | ATMega 328 (16 MHz AVR) | 2 KiB | 84x48  | 1-bit| 4x1-bit Speaker | C/C++ (Arduino) | 32KiB |  Micro SD | ~70 USD (Clones at Various Prices)| Yes | http://legacy.gamebuino.com/wiki/index.php?title=Main_Page |
| Gamebuino META | ATSAMD21 (48 MHz Cortex M0+) | 32 KiB | 160x128 | RGB |10-bit DAC| C/C++ (Arduino) | 256KiB | Micro SD | 70 EUR | No | https://gamebuino.com/ |
| GameGo   |  STM32F401 (84 MHz Cortex M4) | 96 KiB  | 160x128  |  RGB |1-bit Speaker | VPL (MakeCode Arcade)  |  512 KiB  |  N/A | 41.90 USD  | No  |  https://www.seeedstudio.com/GameGo-p-4847.html |
| Kitronik ARCADE | ATSAMD51J19 (120MHz Cortex M4F)  | 192 KiB   |  160 x 128 | RGB  | 1-bit Piezo | MicroPython, VPL (MakeCode Arcade) | 512KiB	  | N/A  |  36.00 GBP  | No  | https://kitronik.co.uk/products/5311-arcade-for-makecode-arcade  |
| KOKO   | ATtiny85 (20 MHz AVR) | 512 B  | 120x64  | 1-bit  |1-bit Buzzer|  C/C++ (Arduino) | 8 KiB  | N/A  | 37.50 USD  | Yes  |  https://www.tindie.com/products/el9000/koko-a-retro-game-console-kit-diy-and-hackable/ |
| MeowBit  | STM32F401 (84 MHz Cortex M4)   |   96 KiB    | 160x128    | RGB     | 1-bit Buzzer| CircuitPython, VPL (MakeCode Arcade)   | 512KiB    | SD  | 39.95  USD    | Yes  |  https://meowbit.kittenbot.cc   |
| MicroByte  |  ESP32 WROVER E (2x240 MHz Xtensa) | 8 MiB  | 240x240  | RGB  |1-bit Buzzer| MicroPython, C/C++ (Arduino), Z80 Assembly (Gameboy (Color), Sega Master System, Game Gear), 6502 Assembly (NES)  | 16 MiB  | N/A  | TBD  | Yes  | https://www.crowdsupply.com/byte-mix-labs/microbyte  |
| Nibble  |  ESP8266 (160 MHz Xtensa) | 80 KiB  | 128x128  | RGB  |1-bit Buzzer|  C/C++ (Arduino), Python, VPL (CircuitBlocks)  |  4MiB | N/A  |  75.99 USD |  Yes |  https://circuitmess.com/nibble/ |
| Xtron Pro   |  STM32F41x (100 MHz Cortex M4) |   256 KiB | 160x128  | RGB  | 1-bit Speaker |  VPL (MakeCode Arcade, Xmaker), 6502 Assembly (NES) |  1 MiB | 16 MiB Flash  | 85 USD  | No  | https://store.ovobot.cc/products/xtron-pro  |
| PewPew M4   |  ATSAMD51G19A |  192 KiB | 160x128  | RGB  | 1-bit Buzzer| CircuitPython | 512 KiB  |  N/A |  25 USD | Yes  | https://pewpew.readthedocs.io/en/latest/pewpew-m4/overview.html https://makerfabs.com/circuitpython-pewpew-m4.html  |
| PicoSystem   |  RP2040  (2x133 MHz Cortex M0+) | 264 KiB  |  240x240 | RGB  |1-bit Buzzer| C++,MicroPython,CircuitPython   | 16 MiB  |  N/A | 58.50 GBP  | No  |  https://shop.pimoroni.com/products/picosystem |
| Playdate | STM32F746IGK (180MHz Cortex M7) | 16 MiB  | 400x240    | 1-bit    |  2x1-bit Speaker | Lua, C  |  1 MiB  | 4GB Flash, Weekly Digital Download  | 179 USD            |  No  | https://play.date/   |
| Pokitto         | LPC11U6x (72 MHz Cortex M0+) | 36 KiB | 220x176    | 8-bit |8-bit Speaker| MicroPython, C/C++ (Native, Arduboy, Gamebuino), Java | 256kiB   | Micro SD   | 49.90 EUR        |    Yes  | https://www.pokitto.com/ |
| PyBadge   |  ATSAMD51J19 (120MHz Cortex M4F)  |  192 KiB   | 160x128    | RGB    | 1-bit Speaker | CircuitPython, VPL (MakeCode Arcade), C++ (Arduino) | 512KiB |   2 MiB Flash  | 24.95 USD - 39.95 USD | Yes  | https://learn.adafruit.com/adafruit-pybadge |
| PyGamer | ATSAMD51J19 (120MHz Cortex M4F)  |  192 KiB   | 160x128    | RGB    | 1-bit Speaker | CircuitPython, VPL (MakeCode Arcade), C++ (Arduino) | 512KiB | 8 MiB Flash, Micro SD  | 44.95 USD - 59.95 USD | Yes  | https://learn.adafruit.com/adafruit-pygamer |
| PYXA | ATMega 328 (16 MHz AVR) | 2 KiB | 160x128 | RGB | 1-bit Buzzer | C/C++ (Arduino) | 32KiB | Micro SD  |  99 GBP | No | https://www.creoqode.com/pyxa |
| Retro Game Tiny    | ATtiny85 (20 MHz AVR) | 512 B  | 120x64  | 1-bit  |1-bit Buzzer |  C/C++ (Arduino) | 8 KiB  | N/A  | 19.99 USD  | Yes  |  https://www.tindie.com/products/jasonkits/retro-game-tiny-oled-arcade-console/ |  
| Thinkbox | STM32F41x (100 MHz Cortex M4) | 256 KiB | 320x240 | RGB | 1-bit Speaker | VPL (Makecode Arcade) | 512 KiB | N/A | 50 USD | No | https://www.aliexpress.com/item/1005004511119421.html |
| Thumby | RP2040  (2x133 MHz Cortex M0+) | 264KiB    |   72x40  | 1-bit  | 1-bit Buzzer | MicroPython , C/C++ (Arduino) | N/A  | 2 MiB Flash | 29.95 USD | Yes | https://www.kickstarter.com/projects/kenburns/thumby-the-tiny-playable-keychain  |
| TinyArcade/PocketArcade | ATMega 328P (16 MHz AVR) | 2 KiB   |   96x64  | RGB | 1-bit Speaker  | C/C++ (Arduino) | 32 KiB    | Micro SD | 59.95  USD    | Yes | https://tinycircuits.com/collections/all/products/tinyarcade  |
| Tiny Joypad  | ATtiny85 (in cartridge) (20 MHz AVR)|  512 B | 128X64   |  1-bit |   1-bit Speaker | C/C++ (Arduino) |  N/A  | 8 KiB  |  25 USD | Yes  | https://www.tinyjoypad.com/  |
| TomatoCube* | STM32F41x (100 Mhz Cortex M4) | 256 KiB | 160x128 | RGB | 1-bit Buzzer | VPL (Makecode Arcade) | 512 KiB | N/A | 159 RM | No | https://tomatocube.com/product/makecode-arcade-console/ |
| µgame | ATSAMD21 (48 MHz Cortex M0+)  | 32 KiB | 128×128 | RGB | 1-bit Speaker | MicroPython , CircuitPython | 256KiB | 2 MiB Flash | 24.99 USD | Yes | https://github.com/python-ugame https://www.tindie.com/products/deshipu/game-10-python-game-console-kit/ |

## LED Matrix Games
These have a Rectangular Matrix of LEDs as opposed to an LCD, TFT or OLED screen and therefore usually have <200 dots. You could still make crude games on them but not much more than snake.

| Name | Processor | RAM | Resolution | Color | Sound | Languages | Flash Size | Storage | Price | Schematic Available | URL |
| ---- | --------- | --- | ---------- | -------- | --- | ---------- | ---------- | ---------- | --- | ---------- | ---------- |
| 2048   | ATMega2560 (16 MHz AVR)  | 8 KiB  |  64x32 |  RGB  | N/A |   C/C++ (Arduino)|256KiB   | N/A  | 189 GBP  |  No |  https://www.creoqode.com/2048 |
| Meggy Jr. RGB   | ATmega168  (16MHz AVR) | 1 KiB  | 8x8  | 3-bit | 1-bit Buzzer | C/C++ (Arduino)  |  16 MiB | N/A  | 75 USD  |  Yes |  https://shop.evilmadscientist.com/productsmenu/tinykitlist/760 |
| PewPew  | ATSAMD21 (48 MHz Cortex M0+)  | 32 KiB |  8x8  | 2-bit    | N/A  | CircuitPython|  256KiB   | N/A |  9.99 USD + Feather M0 Express (19.95 USD) | Yes  |  https://makerfabs.com/pewpew-standalone.html |

## Shields and Add Ons

Finally we have shields and Add Ons. To Qualify for this list you need to add buttons and a display.

| Name | Interface | Display Type| Resolution | Color | Sound | Storage| Price |  Schematic Available| URL |
| --- | ------------- | -------| ---------- | ---- | ------ | ----| -----| ----| - |
|  DigiPixel |  Arduino |LED Array| 8x8  |  3-bit | N/A| N/A |  19.95 USD | No  | http://digistump.com/products/108  |
| Gamby   |  Arduino | Screen | 96x64  | 1-bit  |  1-bit Buzzer | N/A  | 25 USD  | Yes  |http://logicalzero.com/gamby/   |
|   GAME ZIP 64  |  micro:bit | LED Array| 8x8  |  1-bit   |   1-bit Buzzer | N/A  | 36.60 GBP  | Yes  |  https://kitronik.co.uk/products/5626-game-zip-64-for-the-bbc-microbit |
| Newbit Arcade Shield   | micro:bit V2  | Screen | 160x128  | RGB  |  N/A | N/A  | 26.90 USD  | No  |  https://www.kittenbot.cc/products/newbit-arcade-shield |
| TomatoCube* | micro:bit V2 | Screen | 160x128 | RGB | 1-bit Buzzer | N/A | 130 RM | No | https://tomatocube.com/product/makecode-arcade-shield-for-microbit/ |

## How to Contribute
If I missed a console leave a Pull Request or an Issue. The criteria to be included is.

0. Be a handheld device (not a console ala Hackivision or computer ala Commander X16)
1. Purchasable in either kit form or as a product (No one off hobby projects and DIY instructions)
2. Must be programmable by the end user (No LCD Games, Or Clone Consoles and Emulation Boxes that aren't for Homebrew)
3. Mustn't run Linux or BSD (No Raspberry Pi based handhelds)
4. Have buttons and a Pixel Grid Screen (No character LCDs or Touchscreen Only Devices)

## Related Lists
https://github.com/paladin-t/fantasy (For Fantasy Computers, game engines intended to look or act like a Retro Computer).  
https://aced.io/oshw-gaming/ (A similar list that includes consoles)
