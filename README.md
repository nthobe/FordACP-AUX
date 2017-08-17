# Ford CD changer emulator with AUX audio and stock playback control using Arduino UNO

### *Keep the retro stereo. Bring your own tunes. *

Add AUX audio input to your older Ford vehicle using an Arduino UNO and use the stock radio to control playback on your iPhone. 

#### [Read about the development of this.](http://ansonliu.com/2017/07/ford-acp-cd-changer-emulator-aux-audio/)

  - Adapted from Dale Thomas's [*Ford Bluetooth Interface*](http://www.instructables.com/id/Ford-Bluetooth-Interface-Control-phone-with-stock-/) and Krysztof Pintscher's  [Ford CD Emulator](http://www.instructables.com/id/Ford-CD-Emulator-Arduino-Mega/).
  - Uses Ford Audio Control Protocol (ACP) to emulate stock 6 CD Changer.
  - Modified for use with Arduino Uno with **switchPin** set to pin 8.
  - Protoshield hand wiring diagram included in `Resources` folder. 
  - EAGLE PCB files in `eagle` folder.

### Directions

  - Open **Ford_Uno.ino** located in *Sketch/Ford_Uno* and upload to Arduino UNO.
  - Do one of the following
    1. Wire up Arduino UNO like shown below.
    2. Print PCB using provided EAGLE files.

![top](https://raw.githubusercontent.com/ansonl/fordacp-aux/master/Resources/top.jpg) ![bottom](https://raw.githubusercontent.com/ansonl/fordacp-aux/master/Resources/bottom.jpg)
![uno protoboard](https://raw.githubusercontent.com/ansonl/fordacp-aux/master/Resources/uno-protoboard.png)
![side](https://raw.githubusercontent.com/ansonl/fordacp-aux/master/Resources/side.jpg) ![connected side](https://raw.githubusercontent.com/ansonl/fordacp-aux/master/Resources/connected-side.jpg)

### License

Any adaptation of this work must comply with licenses of previous works (those in `Resources` folder) and include references to the previous authors. 

  - Andrew Hammond
  - [Krysztof Pintscher](http://www.instructables.com/id/Ford-CD-Emulator-Arduino-Mega/)
  - [Dale Thomas](http://www.instructables.com/id/Ford-Bluetooth-Interface-Control-phone-with-stock-/)
  - [Anson Liu](http://ansonliu.com)