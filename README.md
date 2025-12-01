# Smart Timer Plug 🔌

A DIY Timer Plug project that allows you to [Control the switching of plug  via WiFi, turn off automatically after the timer].


## 🌟 Features
* **Automated Control:** [e.g., Turns off device after 30 minutes]
* **User Interface:** [e.g., OLED Display / Push Buttons / Mobile App]
* **Safety:** [e.g., Overheat protection / Relay isolation]

## 🛠️ Hardware Components (Bill of Materials)
* Microcontroller: [e.g., Arduino Nano / ESP32 / NodeMCU]
* Relay Module: [e.g., 5V 1-Channel Relay]
* Display: [e.g., 0.96" OLED I2C]
* Power Supply: [e.g., 5V AC-DC converter]
* Socket & Enclosure

## 🔌 Circuit Diagram
You can find the wiring diagram in the `hardware` folder.
![Schematic](hardware/schematic.png)

## 💻 Software & Libraries
This project uses the following libraries:
* `Wire.h` (Standard)

## 🚀 How to Install
1.  Download this repository.
2.  Open `firmware/TimerPlug.ino` in the Arduino IDE.
3.  Install the required libraries via the Library Manager.
4.  Upload the code to your board.
5.  **Note:** If using WiFi, rename `secrets_template.h` to `secrets.h` and add your WiFi credentials.

## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.