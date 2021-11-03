# NFC2Serial

This repository contains code for exploring Speed Studio's configurable NFC tags
during the Open Hardware Training as part of [OpenDoTT](https://opendott.or€g.).

The Arduino Firmware send the detected NFC tag's identifiers via Serial
connection to the host machine. On the host machine *Node Red* is used to
program the receiving end.

# Setup

To install *Node Red* use a terminal and run `npm install` in this folder.

Use the [Arduino IDE](https://arduino.cc) to open `Arduino Firmware/NFC2Serial/NFC2Serial.ino` and upload to the board of your choice.

The Seeed Studio Grove NFC module was connected on the RS232 serial connector.


To run the *Node Red* flow, start it in the terminal with `npm run`.


# Acknowledgments

🇪🇺 This project is part of [OpenDoTT](https://opendott.org.) and has received
funding from the European Union’s Horizon 2020 research and innovation programme
under the Marie Skłodowska-Curie grant agreement No. 813508.