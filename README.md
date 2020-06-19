# Button_Controller

This software is designed to be used on Raspberry Pi handheld systems, such as the Gameboy Zero projects. This software handles battery monitoring, GPIO pins as control inputs, an analog joystick and safe shutdown. You will need specific hardware for some of these functions, which is listed below. The easiest way is to use Helders Retro PSU.

#Build instructions:
git clone --recursive https://github.com/codeman-pi-projects/Button_Controller.git

make

#How to use it:
Configure (edit) the monitor script accordingly to your hardware configuration

sudo python monitor_evdev.py
