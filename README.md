🩺 Medicine Reminder System
A microcontroller-based embedded system designed to remind users to take their medicine on time using RTC, LCD, keypad, buzzer, and switches.

🔹 Features
Displays real-time clock on LCD
Set/edit medicine times via keypad
Alerts with buzzer and LCD when it's time
User acknowledges alert with a button press

🔧 Hardware
LPC2148 Microcontroller
16x2 LCD Display
4x4 Keypad
On-chip RTC
Buzzer
Switch1 (set schedule), Switch2 (acknowledge)
USB-UART/DB9 for programming

💻 Software
Embedded C (Keil IDE)
Flash Magic (for flashing code)

⚙️Working
Press Switch1 → Set medicine time via keypad
LCD displays current time and saved schedules
On schedule match → Alert with buzzer + message
Press Switch2 to stop alert and return to clock display

📘 Instructions:
Power on the device
LCD shows current date & time
Press Switch1 → Enter time using keypad
System saves and displays schedule
At set time → Alert triggers
Press Switch2 to acknowledge

