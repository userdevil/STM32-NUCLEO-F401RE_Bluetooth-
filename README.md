# Voice-Based Home Automation System

This project implements a voice-based home automation system using STM32-F401RE microcontroller and HC-05 Bluetooth module. The system allows users to control various home appliances and devices using voice commands.

## Features

- Voice-controlled operation of home appliances and devices.
- Integration with STM32-F401RE microcontroller and HC-05 Bluetooth module.
- Easy setup and configuration.
- Support for multiple voice commands and actions.
- Expandable and customizable for specific home automation requirements.

## Hardware Requirements

- STM32-F401RE microcontroller
- HC-05 Bluetooth module
- Home appliances/devices (e.g., lights, fans, etc.)
- Jumper wires
- Power supply

## Software Requirements

- STM32CubeIDE
- Embedded C programming language

## Getting Started

1. Copy the repository URL:
```shell
git clone https://github.com/userdevil/STM32-NUCLEO-F401RE_Bluetooth-.git
```
2. Connect the STM32-F401RE microcontroller and HC-05 Bluetooth module according to the wiring diagram provided in the repository.
![Wiring Diagram](https://embeddedthere.com/wp-content/uploads/2023/02/circuit_diagram_2-min.png)
3. Open the project in STM32CubeIDE and compile the code.

4. Upload the compiled code to the STM32-F401RE microcontroller.

5. Power on the system and ensure the HC-05 Bluetooth module is discoverable.

6. Pair your smartphone or Bluetooth-enabled device with the HC-05 module.

7. Launch the home automation application on your smartphone.

8. Start giving voice commands to control the home appliances/devices.

## Usage

- Use the provided smartphone application to send voice commands to the HC-05 Bluetooth module.
- The STM32-F401RE microcontroller will receive the voice commands and process them accordingly.
- The microcontroller will control the connected home appliances/devices based on the voice commands received.

## Contributing

Contributions to this project are welcome. If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes in the new branch.
4. Commit your changes.
5. Push the branch to your forked repository.
6. Submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- STM32CubeIDE - Integrated Development Environment for STM32 microcontrollers.
- HC-05 Bluetooth Module - Bluetooth module for wireless communication.

Feel free to modify the template to suit your specific project requirements. Make sure to include any necessary instructions, dependencies, or documentation related to your project.
