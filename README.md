# Expansion odule : 8 position switch and 4 buttons 

Control Input Module for Smartboard

![Hardware](https://img.shields.io/badge/Hardware-PCB-red)
![Design](https://img.shields.io/badge/Design-Schematic-blue)
![made-with-eagle](https://img.shields.io/badge/Made%20with-Eagle-blue.svg)
![license](https://img.shields.io/badge/license-MIT-green)

## Overview
This repository hosts the design and implementation details of a Control Input Module for the smartboard. Incorporating an 8-position switch, 4 buttons, and a single digit 7-segment display, this module is powered by an ATtiny48 microcontroller. It is designed to serve as a versatile control interface for smartboard applications, utilizing two smartboard connectors for enhanced functionality.

## Key Features
- **8-Position Switch and 4 Buttons**: Provides a comprehensive set of inputs for control and selection tasks.
- **Single Digit 7-Segment Display**: Offers visual feedback for settings or values.
- **ATtiny48 Microcontroller**: A compact, low-power microcontroller from Microchip, known for its versatility and efficiency in handling I/O operations, making it ideal for embedded applications.
- **Smartboard Compatibility**: Designed to connect seamlessly with two smartboard connectors, facilitating easy integration with existing systems.
- **Customizable Input Handling**: The ATtiny48 allows for flexible programming to accommodate various input scenarios and application requirements.

### Schematic
![Schematic](media/sch.png)
*Detailed schematic showing the connections between the ATtiny48, the switch, buttons, and the 7-segment display.*

### Board Design
![Board Design](media/brd.png)
*A visual representation of the PCB layout, highlighting the placement of the ATtiny48, the input controls, and the display.*

## Programming and Configuration
The ATtiny48 microcontroller can be programmed via the ISP interface, allowing for easy customization of the module's behavior. Users can develop and upload their own firmware to tailor the module's operation for specific applications or to add new features.

## Contributions and Feedback
We encourage contributions to this project. If you have suggestions for improvement or have developed additional features, please fork the repository, make your changes, and submit a pull request. For any questions or issues, please open an issue in the GitHub repository.

## License
This project is licensed under the MIT License, permitting use, modification, and distribution in both private and commercial settings. Attribution to the original author, Adam Łuczak, is appreciated but not required. The design is provided "as is" without warranty; the author is not liable for any damages arising from its use.

## Contact
For inquiries or suggestions, contact Adam Łuczak at adam.luczak@outlook.com.
