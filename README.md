# Smart Timer Plug 🔌 (Web Controlled)

A DIY Smart Plug powered by an ESP32 that hosts its own web interface. You can control the socket and set timers directly from any web browser (Phone/Laptop) connected to the same WiFi network.

![Project Image](smart plug.jpg)

## 🌟 Features
* **Web Interface:** No apps required. Access control via a browser (Chrome/Safari).
* **Wireless Control:** Turn the socket ON/OFF remotely via WiFi.
* **Timer Settings:** Set duration or specific times via the web page.
* **Compact Design:** Stacked custom enclosure using ESP32.

## 🛠️ Hardware Components (Bill of Materials)
| Component | Description | Qty |
| :--- | :--- | :--- |
| **Microcontroller** | ESP32 Development Board | 1 |
| **Relay Module** | 5V 1-Channel Relay (Active High/Low) | 1 |
| **AC Socket** | 5-Pin Universal Socket (Type D/M compatible) | 1 |
| **Power Supply** |  5V DC Converter (Internal) | 1 |
| **Enclosure** | Custom DIY Insulated Housing | 1 |

## 🔌 Circuit Diagram
* **Relay Pin:** GPIO 16 (RX2)
* **Power:** 5V External Source to ESP32 VIN
* **Mains:** Live wire switched via Relay NO/COM

## 🚀 How to Use
1. **Power On:** Plug the device into a wall socket.
2. **Connect:** Ensure your phone is on the same WiFi network as the plug.
3. **Access:** Open your browser and type the ESP32's IP address (e.g., `192.168.1.X`).
   *(You can find this IP in the Arduino Serial Monitor initially).*
4. **Control:** Use the web page buttons to toggle power or set the timer.

## 💻 Software & Libraries
* **WiFi.h** (Standard)
* **WebServer.h** (Standard)
* **NTPClient** (For accurate timekeeping over WiFi)



