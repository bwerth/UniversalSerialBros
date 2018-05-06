# Universal Serial Bros
A brief USB-HID implementation of mouse and keyboard devices using an STM32F446ZE device for SP18 Software Systems at Olin College of Engineering

Adapted from Pax Instruments STM32CubeF4 Project Library

## Getting Started

1. Fork Pax Instruments' [STM32CubeF4 repository](https://github.com/PaxInstruments/STM32CubeF4.git) and [our project](https://github.com/PaxInstruments/UniversalSerialBros.git)

2. Clone both repositories
```
git clone https://github.com/<YOUR USERNAME HERE>/STM32CubeF4.git
git clone https://github.com/<YOUR USERNAME HERE>/UniversalSerialBros.git
```

For keyboard implementation:
```
cp -fR /UniversalSerialBros/Src/keyboard/Inc /STM32CubeF4/Projects/STM32F446ZE-Nucleo/Applications/USB_Device/HID_Standalone/Inc
cp -fR /UniversalSerialBros/Src/keyboard/Src /STM32CubeF4/Projects/STM32F446ZE-Nucleo/Applications/USB_Device/HID_Standalone/Src
```

For mouse implementation:
```
cp -fR /UniversalSerialBros/Src/mouse/Inc /STM32CubeF4/Projects/STM32F446ZE-Nucleo/Applications/USB_Device/HID_Standalone/Inc
cp -fR /UniversalSerialBros/Src/mouse/Src /STM32CubeF4/Projects/STM32F446ZE-Nucleo/Applications/USB_Device/HID_Standalone/Src
```

3. Use [OpenSTM32's Tutorials](https://www.youtube.com/playlist?list=PLrLYs4BdzrqhlRYUUfQXVJU9p9J8QnBtF) to download the IDE and import the project into the workspace

## Running the Program
1. Connect the STM Device's USB Power Port to your computer using a microUSB Adapter
2. Open up the main script under Application>User and press Ctrl+F11 to run

Check out the results [here](https://www.youtube.com/watch?v=yx8DOXDXk28&feature=youtu.be)!

If you're using the keyboard and you want to program the board to type something else, edit this line in main.c:
```
line 38   char *message = "Happy birthday to you, you live in a zoo, you look like a monkey, and you smell like one too!";
```

## Features
- Vertical and horizontal mouse movement
- Right clicking
- Shift key support
- Character support for alphabetical characters, commas, spaces, periods, exclamation marks, apostrophes, and question marks
