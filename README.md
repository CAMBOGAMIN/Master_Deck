# **Master Deck – Raspberry Pi Cybersecurity Multi-Tool**  

**Master Deck** is a Raspberry Pi-powered, open-source **penetration testing and cybersecurity tool**. It integrates several wireless communication modules to help you analyze and interact with networks and devices for **cybersecurity research**. Think of it as a **Flipper Zero** on steroids, with the power and flexibility of a Raspberry Pi.

## **🚀 Features**
- **Wireless Communication**: Interact with devices and networks using the **NRF24L01+PA+LNA (2.4GHz)** RF module.
- **WiFi Scanning & Communication**: Use **ESP8266** or **ESP32** for scanning WiFi networks and capturing packets.
- **Bluetooth Interaction**: Use **HC-05 Bluetooth Module** to sniff, pair, and interact with Bluetooth devices.
- **Custom PySimpleGUI Interface**: User-friendly GUI for controlling and automating operations.
- **Real-time Signal Monitoring**: Monitor and analyze wireless signals in real time.

## **🛠 Hardware Used**
- **Raspberry Pi 3B** (Main Controller)
- **NRF24L01+PA+LNA** (2.4GHz RF Module for wireless communication)
- **ESP8266/ESP32** (WiFi Scanning and Communication)
- **HC-05 Bluetooth Module** (Bluetooth Hacking & Sniffing)
- **Capacitors & Logic Level Shifters** (for stability)
  
## **📜 Software & Dependencies**
- **Python 3**: The main programming language.
- **PySimpleGUI**: Simple Python GUI framework.
- **spidev**: SPI interface library for communication with NRF24L01.
- **RPi.GPIO**: Python library for controlling the GPIO pins on Raspberry Pi.
- **libnrf24**: Library to interact with the NRF24L01 module.
- **pyserial**: Library for serial communication (for ESP8266/HC-05).
  
## **📖 Setup & Installation**

### 1. **Clone the Repository**

git clone https://github.com/CAMBOGAMIN/Master_Deck.git
cd Master-Deck
