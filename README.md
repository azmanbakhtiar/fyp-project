![picture2](https://github.com/azmanbakhtiar/fyp-project/assets/145319590/c22f3616-b5c3-4be1-b812-c78c7ac2fed0)
# STM PWM Generator for BLDC Motor Control

This repository contains code and documentation for a PWM generator designed for controlling BLDC (Brushless DC) motors using an STM microcontroller. The PWM (Pulse Width Modulation) signals are essential for controlling the speed and direction of BLDC motors. This project utilizes STM32CubeIDE and potentiometers to adjust various parameters such as frequency and duty cycle for generating the PWM signals.

## Features

- **Adjustable Frequency**: Utilize a potentiometer to set the PWM frequency dynamically.
- **Adjustable Duty Cycle**: Fine-tune the duty cycle of the PWM signal using another potentiometer.
- **Setup Mode**: Configure high and low thresholds for frequency and duty cycle using dedicated potentiometers without generating PWM signals.
- **Output Mode**: Generate PWM signals based on the configured settings.
- **LCD Display**: Utilize a 16x2 LCD to display current settings and mode information.
- **User-friendly Interface**: Use buttons to toggle between setup and output modes, and to switch between adjusting frequency and duty cycle.

## Hardware Requirements

- STM microcontroller board (e.g., STM32F4 Discovery or similar)
- Potentiometers (6 in total)
- Push buttons (1 or more, depending on the user interface design)
- 16x2 LCD display

## Usage

1. Connect the STM microcontroller board to the potentiometers, push buttons, and LCD display based on the circuit diagram provided in the repository.
2. Set up the STM32CubeIDE project and configure the GPIOs, ADC channels, and LCD display drivers as required.
3. Compile and flash the project onto the STM microcontroller board.
4. Power up the system and navigate through the modes using the push buttons.
5. In setup mode, adjust the high and low thresholds for frequency and duty cycle using the respective potentiometers.
6. Switch to output mode to generate PWM signals based on the configured settings.
7. Monitor the current settings and mode information on the LCD display.

## Contributing

Contributions are welcome! If you have any suggestions, improvements, or feature requests, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code for your own purposes.

