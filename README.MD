# Light Control


## Documentation


### Program Overview
The program is a Gtk-based application for controlling display brightness and color temperature on Linux systems, specifically designed for Debian and Ubuntu-based distributions. It provides a user-friendly interface to adjust display settings according to user preferences.


### Features
1. **Display Brightness Control:** Adjust the brightness level of the display.
2. **Color Temperature Control:** Modify the color temperature of the display to reduce eye strain during different times of the day.
3. **Monitor Selection:** Choose from available monitors connected to the system.
4. **Backlight Device Selection:** Select the backlight device for adjusting brightness.
5. **Graphical User Interface:** Intuitive GUI built using Gtk library for ease of use.


### Dependencies
- Python 3
- Gtk+ 3.0
- xrandr


### Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/EnSabahNurX/lightcontrol/


2. **Navigate to the project directory:**
   ```bash
   cd brightness-controller

3. **Install dependencies:**
   ```bash
   sudo apt-get install python3-gi


### Usage
1. **Run the program:**
   ```bash
   python3 brightness_controller.py

2. **Adjust Brightness:**
 - Use the brightness scale slider to adjust brightness level.
3. **Modify Color Temperature:**
 - Use the temperature scale slider to change color temperature.
 - Click "Day" or "Night" buttons to switch between predefined color temperature settings.
4. **Select Monitor and Backlight Device:**
 - Choose the monitor and backlight device from the dropdown menus.


### Notes
 - Ensure the script is run with root privileges for proper functionality.
 - The program supports Debian and Ubuntu-based distributions.
 - For advanced users, the code can be customized further to suit specific requirements.