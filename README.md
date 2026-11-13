# VTU Lab Programs

Arduino and IoT lab programs for VTU coursework.

## Programs

### 1. Serial LED Control (`serial_led_control.ino`)
Controls the onboard LED (connected to digital pin 13) via Arduino Serial Monitor.

#### Operation
- **Baud Rate:** 9600 bps
- **Commands:**
  - Send `'1'`: Turns the LED **OFF** (`LOW`)
  - Send `'2'`: Turns the LED **ON** (`HIGH`)
- Reads the character sent through the Serial Monitor, prints it back for verification, and updates the LED state accordingly.
