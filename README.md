# Lab-Arduino-Basics

These are two base labs for sharing Arduinos and enable online programming of them. Both labs feature a simple blinking LED program and the basics of serial communication.

These examples combines:

- editor:
  
  - [module-editor](https://github.com/edrys-labs/module-editor): Simple minimal and configurable code editor.
  - [module-blockly-duino-v2](https://github.com/edrys-labs/module-blockly-duino-v2): Blockly-Duino2 web-editor.

- [module-markdown-it](https://github.com/edrys-labs/module-markdown-it): Markdown viewer used for documentation.
- [module-pyxtermjs](https://github.com/edrys-labs/module-pyxtermjs): Terminal Server, this requires a running local server to be able to run the code.
- [module-station-stream](https://github.com/edrys-labs/module-station-stream): Camera stream viewer via WebRTC.

After importing one of the predefined configuration listed below, you have to open a station and start the pyxtermjs server, running on localhost.

The easiest way to do this, is by installing docker and running the following command:

```bash
docker run -it -p 5000:5000 --device=/dev/ttyACM0:/dev/ttyACM0 crosslab/edrys_pyxtermjs_arduino:latest
```
This will download the pyxtermjs terminal-server from docker-hub and run it in a secure environment.

Otherwise, you can install the server locally by following the instructions in the [module-pyxtermjs](https://github.com/edrys-labs/module-pyxtermjs).

## Arduino - Configuration

To reuse this lab import it as a new lab-configuration by copying the following URL into the import dialog of the lab-configuration or download it, change it and upload it to your lab:

https://raw.githubusercontent.com/edrys-labs/lab-arduino-basics/main/laboratory/arduino.yaml

https://raw.githubusercontent.com/edrys-labs/lab-arduino-basics/main/laboratory/arduino.json

## Blockduino - Configuration

and as blockly ... load as above ;-)

https://raw.githubusercontent.com/edrys-labs/lab-arduino-basics/main/laboratory/blockduino.yaml

https://raw.githubusercontent.com/edrys-labs/lab-arduino-basics/main/laboratory/blockduino.json

## Demo

This is a demo of a follow-up laboratory that is based on the Arduino-configuration:

https://raw.githubusercontent.com/edrys-labs/lab-arduino-basics/main/lab.yaml

https://github.com/edrys-labs/lab-arduino-basics/assets/3089101/3428fcc9-ce3e-4f99-bb97-e3ae34dd527a
