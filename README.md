# Smart Timer Plug 🔌

A DIY Timer Plug project that allows you to [Control the switching of plug  via WiFi, turn off automatically after the timer].


## 🌟 Features
* **Automated Control:** [e.g., Turns off device after 30 minutes]
* **User Interface:** [e.g. Mobile App]
* **Safety:** [e.g., Overheat protection / Relay isolation]

## 🛠️ Hardware Components (Bill of Materials)
* Microcontroller: [ESP32]
* Relay Module: [5V 1-Channel Relay]
* Power Supply: [e.g., 5V DC supply]
* Socket & Enclosure

## 🔌 Circuit Diagram
You can find the wiring connections in the `connections` folder.
![Schematic](timerplug.png)

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

