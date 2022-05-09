# FYSETC-ERB
This is dedicated controller board for VORON ERCF

![](images/board1.png)

![](images/board2.png)

## Hardware

There are schemetic, silk and dwg file in `Hardware` folder.

## Firmware

### Compile options

![](images/makemenuconfig.png)

### Firmware upload

Step 1: Power on the board

Step 2: Connect ERB to your computer with USBC cable

Step 3: Push an hold `BOOTSEL` button

Step 4: Click `RST` button and release `BOOTSEL` button

Step 5: `RPI-RP2` folder will show up on your computer, copy your built firmware `klipper.uf2` to the folder.

![](images/upload1.png)

![](images/upload.png)

### Configuration

See `ercf_hardware.cfg` in this repository `config` folder.

