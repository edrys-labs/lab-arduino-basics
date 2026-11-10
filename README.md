# Lab-Arduino-Basics

These are two base labs for sharing Arduinos and enable online programming of them. Both labs feature a simple blinking LED program and the basics of serial communication.

These examples combines:

- editor:
  
  - [module-monaco-editor](https://github.com/edrys-labs/module-monaco-editor): Collaborative code editor with real-time sync.
  - [module-blockly-duino-v2](https://github.com/edrys-labs/module-blockly-duino-v2): Blockly-Duino2 web-editor.

- [module-markdown-it](https://github.com/edrys-labs/module-markdown-it): Markdown viewer used for documentation.
- [module-pyxtermjs](https://github.com/edrys-labs/module-pyxtermjs): Terminal Server, this requires a running local server to be able to run the code.
- [module-streaming](https://github.com/edrys-labs/module-streaming): Camera stream viewer via WebRTC.

After importing one of the predefined configuration listed below, you have to open a station and start the pyxtermjs server, running on localhost.

The easiest way to do this, is by installing docker and running the following command:

```bash
docker run -it -p 5000:5000 --device=/dev/ttyACM0:/dev/ttyACM0 edryslabs/module-pyxtermjs:latest
```
This will download the pyxtermjs terminal-server from docker-hub and run it in a secure environment.

Otherwise, you can install the server locally by following the instructions in the [module-pyxtermjs](https://github.com/edrys-labs/module-pyxtermjs).

## Arduino - Configuration

To reuse this lab import it as a new lab-configuration by copying the following URL into the import dialog of the lab-configuration or download it, change it and upload it to your lab:

[<img src="https://img.shields.io/badge/%F0%9F%9A%80%20-%20Deploy%20Lab%20-%20light?style=plastic" height="25" />](https://edrys-labs.github.io/?/deploy/https://raw.githubusercontent.com/edrys-labs/lab-arduino-basics/main/laboratory/arduino.yaml)

https://raw.githubusercontent.com/edrys-labs/lab-arduino-basics/main/laboratory/arduino.yaml

https://raw.githubusercontent.com/edrys-labs/lab-arduino-basics/main/laboratory/arduino.json

## Blockduino - Configuration

and as blockly ... load as above ;-)

[<img src="https://img.shields.io/badge/%F0%9F%9A%80%20-%20Deploy%20Lab%20-%20light?style=plastic" height="25" />](https://edrys-labs.github.io/?/deploy/https://raw.githubusercontent.com/edrys-labs/lab-arduino-basics/main/laboratory/blockduino.yaml)

https://raw.githubusercontent.com/edrys-labs/lab-arduino-basics/main/laboratory/blockduino.yaml

https://raw.githubusercontent.com/edrys-labs/lab-arduino-basics/main/laboratory/blockduino.json

## Demo

This video shows the Arduino configuration in action: a student opens the station, changes the blink speed, runs the code and watches the Uno react through the station camera.

https://github.com/user-attachments/assets/3efe5c44-e63a-4cfb-9fa7-e6b284c6d6f4
