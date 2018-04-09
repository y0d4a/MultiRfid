# Multiple RFID Readers

This is a multiple RFID Readers system designed specifically for an Escape Room. The door will open after the 4 right cards(Tags) are read and recognized.

## Requirements :
   #### Hardware :
        - Arduino UNO.
        - 4 x MFRC522 RFID Reader Modules.
        - Relay module.
        - Leds.
        - Jumper wires.
        - Push button (for manual openning).
   #### Software :
        - Arduino IDE.
        - Arduino [RFID Library for MFRC522 by miguelbalboa](https://github.com/miguelbalboa/rfid).     
## Functioning :
    - Green Led turns on when the door opens.
    - Red Led blinks slowly two times when system needs more tags.
    - Red Led blinks fast many times (4, maybe?) when the card isn't allowed.
    - A push button added for manual opening (intended for the cleaning staff).
