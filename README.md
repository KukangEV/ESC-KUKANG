![Logo](docs/assets/logo.png)

[![License](https://img.shields.io/badge/License-Apache2-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0) [![Wiki](https://img.shields.io/badge/Read-Wiki-blue)](https://github.com/KukangEV/ESC-KUKANG/wiki)

## Why are We Building Electronic Speed Controller?

Creating an open source ESC can provide a significant contribution to the development of electric vehicles and EV technology in general. By making this technology openly available, developers and EV enthusiasts in Indonesia and around the world can easily access and modify the ESC.

In addition, by accelerating the development of EV, we can reduce our dependence on dwindling fossil fuels and produce fewer carbon emissions that harm the environment. Through open source ESC, we can encourage the development of more efficient and environmentally friendly technologies for future vehicles.

Moreover, this project can inspire young Indonesians to become more active in the automotive and EV technology industry. With an open source platform, we can develop creativity and innovative ideas that can help produce better technology and advance the automotive industry in Indonesia and around the world. Thus, this project will have a long-term positive impact on society and the environment.

## What is the ESC-KUKANG?

ESC (Electronic Speed Controller) is an important component in electric vehicles, including for the purposes of the Shell Eco-marathon. The ESC functions to control the current and voltage supplied to the DC motor in electric vehicles. The ESC usually uses a MOSFET as a switch which is regulated by a control circuit, and uses PWM (Pulse Width Modulation) to control the speed of the motor.

In the context of the Shell Eco-marathon, the ESC used must be designed in such a way that it is efficient in energy use, lightweight, and can produce power output as needed. This is very important because the vehicle must have enough endurance to cover the required distance with minimal battery usage.

To achieve this goal, several things that need to be considered in the ESC design for Shell Eco-marathon are the selection of components that are efficient and can work at high frequencies (around 16 kHz), the use of MOSFETs with low Rds-on values, the use of appropriate capacitors at input and output regulators to minimize noise and ripple, and the use of a PCB (Printed Circuit Board) with a good layout to minimize noise and EMI (Electromagnetic Interference). In addition, the ESC design must also consider safety factors and protection against overcurrent, overvoltage and overheating.

## How does it work?

ESC (Electronic Speed Controller) is an electronic circuit that functions to control the speed of an electric motor. When given a control signal from the remote or other controller, the ESC will convert the signal into a control signal to speed up or slow down the motor rotation.

ESC works by adjusting the amount of energy supplied to the motor. The ESC regulates the electric current that is supplied to the motor via a MOSFET or other power transistor. When the ESC receives a stronger control signal, the MOSFET opens wide and allows a greater amperage to flow to the motor, causing the motor to spin faster. Conversely, when the ESC receives a weaker control signal, the MOSFET will close more and limit the amperage flowing to the motor, causing the motor to rotate more slowly.

The ESC is also equipped with security protections such as protection from overcurrent, overheat and low voltage which will turn off the motor if there is a problem with the system.

## Installation
coming soon
## Contributors

<a href="https://github.com/KukangEV/ESC-KUKANG/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=KukangEV/ESC-KUKANG" />
</a>

## License

This project is licensed under the Apache 2 License - see the [LICENSE](LICENSE) file for details.

## Version

See `library.json` (PlatformIO) or `library.properties` (Arduino).

v0.0.1

[KUKANG-EV]: <https://kukang-ev.tech/>

