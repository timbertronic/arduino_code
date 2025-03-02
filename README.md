# arduino_code

I'll create Arduino code to control relays based on current sensor readings. This is a common application for monitoring and controlling electrical devices.

This Arduino code reads values from a current sensor (like the ACS712) and controls two relays based on current thresholds. Here's what the code does:

1. **Hardware Setup:**
   - Connects a current sensor to analog pin A0
   - Controls two relays connected to digital pins 2 and 3

2. **Functionality:**
   - Reads current values from the sensor
   - Activates Relay 1 when current falls below 1.0A
   - Activates Relay 2 when current exceeds 5.0A
   - Displays readings and relay status via Serial Monitor

3. **Calibration Values:**
   - The code uses default values for an ACS712 30A sensor (66mV/A sensitivity)
   - You can adjust these parameters based on your specific sensor model

To use this code with your hardware:
- Adjust the pin assignments if needed
- Modify the current thresholds based on your application requirements
- Calibrate the sensor values if your readings aren't accurate

Would you like me to explain any specific part of the code in more detail, or would you like to modify it for your particular application?
