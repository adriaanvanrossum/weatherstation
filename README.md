### Useful links

- Code examples from Xinyuan LilyGO on [GitHub](https://github.com/Xinyuan-LilyGO/LilyGO-T-A7670X/blob/main/examples).
- Board LILYGO® TTGO T-SIM-A7670E ESP32 4G LTE on [AliExpress](https://www.aliexpress.com/item/1005003036514769.html).
- Wireless Weather Station on [AliExpress](https://www.aliexpress.com/item/1005002879253918.html).
- Add ESP32 board to Arduino IDE [tutorial](https://randomnerdtutorials.com/installing-the-esp32-board-in-arduino-ide-windows-instructions/)

### Add board to Arduino IDE

1. Add `https://dl.espressif.com/dl/package_esp32_index.json` to Arduino IDE settings:

    <img width="800" alt="image" src="https://user-images.githubusercontent.com/1079135/142244604-05675d59-0617-4d8c-a865-9413126ddf05.png">

1. Search for `esp32`

    <img width="800" alt="image" src="https://user-images.githubusercontent.com/1079135/142245041-98a954bc-9b76-4657-88ca-524d6c9669ca.png">

1. Connect board, select port:

    <img width="921" alt="image" src="https://user-images.githubusercontent.com/1079135/142266384-6480e6ed-a01b-4d44-ae21-98b454be8ac0.png">

1. Install libraries:
   - TinyGsmClient
   - ArduinoHttpClient
   - Ticker
   - Time (search for `timelib`)
   <img width="800" alt="image" src="https://user-images.githubusercontent.com/1079135/142267014-ed3632c2-2a43-42d6-9893-70ba351c8787.png">

1. Follow [these instructions](https://github.com/Xinyuan-LilyGO/LilyGO-T-A7670X/issues/1) to connect from macOS

### Pin schema for the LILYGO TTGO T-SIM-A7670E

![LILYGO-TTGO-T-SIM-A7670E](images/LILYGO-TTGO-T-SIM-A7670E.jpg)
