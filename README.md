# STM32F407 to Arduino UART Communication Projects

This repository contains three projects that demonstrate communication between an STM32F407 Discovery board and an Arduino using UART protocol. Each project utilizes different UART communication modes to transfer ADC conversion results from the STM32 to the Arduino.

## Projects Overview:

### 1. UART Polling Mode ✨
- **Description**: This project implements UART communication in polling mode. When a button is pressed on the STM32F407 Discovery board, it triggers an ADC conversion. The converted ADC value is then sent to an Arduino board using UART in a synchronous polling manner.
- **Key Features**:
  - Button-triggered ADC conversion.
  - UART communication handled synchronously via polling.
  
### 2. UART Interrupt Mode ⚡
- **Description**: This project utilizes UART communication in interrupt mode. Similarly, pressing a button on the STM32F407 initiates an ADC conversion. Upon completion, the ADC value is transmitted to the Arduino via UART, with interrupts handling the data transfer.
- **Key Features**:
  - Button-triggered ADC conversion.
  - UART communication managed asynchronously with interrupt-driven approach.

### 3. UART DMA Mode 🚀
- **Description**: In this project, UART communication operates in DMA (Direct Memory Access) mode. Pressing the button triggers ADC conversion on the STM32F407. Once the conversion is complete, the DMA controller transfers the ADC value to the UART transmitter, which then sends it to the Arduino.
- **Key Features**:
  - Button-triggered ADC conversion.
  - Efficient data transfer using DMA for UART communication.

---

## Technologies Used:
- STM32F407 Discovery board
- Arduino
- UART protocol
- ADC (Analog-to-Digital Converter)
- STM32CubeMX (for project configuration)
- STM32 HAL (Hardware Abstraction Layer)

---

## Setup Instructions 🛠️:
1. Clone the repository.
2. Open each project folder in your preferred IDE (e.g., STM32CubeIDE).
3. Configure the projects according to the README file in each project folder.
4. Compile and flash the STM32 project onto the STM32F407 Discovery board.
5. Upload the Arduino sketch to the Arduino board.
6. Connect the STM32F407 Discovery board and Arduino via UART (TX/RX pins).

---

## Usage 📝:
- Press the button on the STM32F407 board to trigger ADC conversion and observe the ADC values received on the Arduino's serial monitor.

---

## Contributions 🌟:
Contributions are welcome! Feel free to fork the repository, make improvements, and submit pull requests.

---

## License 📄:
This project is licensed under the [MIT License](LICENSE).

---

## Contact 📬:
For questions or feedback, you can reach out to me via [LinkedIn](https://www.linkedin.com/in/mohamed-amine-najjar-2808a726b/) or open an issue in the repository.
