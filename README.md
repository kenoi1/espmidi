# espmidi
using esp32 s3 wroom & UDA1334A I2S Stereo Decoder Module  
turning midi controller to piano keyboard

**my i2s module pin interface:**
| uda1334a | ESP32 S3 WROOM |
|----------|----------|
| VIN  |  5V  |
|  GND | GND  |
| WSEL | GPIO6 |
| DIN | GPIO18 |
| BLCK | GPIO4 |

| sd card         | GPIO |
|--------------|-------|
| SD_MMC_CMD    | 38    |
| SD_MMC_CLK   | 39    |
| SD_MMC_D0    | 40    |


## Setup:
arturia keystep 32 is connected to usb hub with external power
![IMG_20250516_1606562](https://github.com/user-attachments/assets/8d5b9bb2-7c6c-4870-89f5-000666dd6abe)


30/12/2024
sdcard->audio jack - plays note sounds
![{7CAF3D2C-48E9-414B-98FD-5C34E8DB1F9F}](https://github.com/user-attachments/assets/84a15a84-02c5-480c-a23a-a16f6fab88c0)
