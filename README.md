# 🐱 Raspberry Pi Pico W – Doraemon OLED Display (MicroPython)

Displays a 128x64 pixel Doraemon bitmap image on an SSD1306 OLED screen using MicroPython’s `framebuf` library.

## ⚙️ Hardware Setup
| OLED Pin | Pico Pin | Description |
|-----------|-----------|-------------|
| VCC | 3.3V | Power |
| GND | GND | Ground |
| SDA | GPIO16 | Data |
| SCL | GPIO17 | Clock |

## 🧠 Concept
- Uses `framebuf` to map raw byte data (bitmap).
- Blits the buffer to OLED via I²C.
- Demonstrates basic image rendering on microcontrollers.

## 🎨 Future Ideas
- Animate Doraemon sliding or blinking.
- Add “Hello from Doraemon!” text overlay.
- Combine with sensor readings or clock display.
