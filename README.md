
Temperature Monitoring System Using Arduino and LCD


### **Objective**  
The objective of this project is to design a **temperature monitoring system** using an **Arduino Uno, NTC thermistor, and a 16x2 LCD display**. The system continuously measures the temperature and displays the real-time temperature readings on an LCD screen, making it useful for **home automation, industrial monitoring, and weather stations**.  

---

### **Key Elements of the Project**  
1. **Temperature Sensor (NTC Thermistor)**  
   - Measures temperature based on resistance changes.  
   - Converts analog readings into temperature values.  

2. **Microcontroller (Arduino Uno)**  
   - Reads the analog temperature data.  
   - Processes and converts data into Celsius.  
   - Sends data to the LCD for display.  

3. **16x2 LCD Display**  
   - Displays real-time temperature readings.  
   - Provides user-friendly output without requiring a computer or serial monitor.  

4. **Resistor (10kΩ)**  
   - Acts as a pull-down resistor to form a voltage divider circuit with the thermistor.  

5. **Power Supply (5V from Arduino)**  
   - Provides power to the circuit components.

### **Technology Used**  
1. **Embedded Systems**  
   - The project is based on **Arduino Uno**, which processes temperature data using embedded programming.  

2. **Analog-to-Digital Conversion (ADC)**  
   - The **Arduino’s ADC** converts the analog voltage from the thermistor into a digital value for processing.  

3. **Mathematical Computation**  
   - The system uses the **Steinhart-Hart equation** to convert resistance values into temperature readings in **Celsius**.  

4. **Liquid Crystal Display (LCD) Interface**  
   - The **LiquidCrystal.h** library is used to interface the 16x2 LCD with Arduino.  

5. **Simulation (Wokwi)**  
   - The project can be simulated in **Wokwi**, a cloud-based **Arduino simulator**, before hardware implementation.
  OUTPUT
![Screenshot 2025-01-11 172325](https://github.com/user-attachments/assets/70ec81db-919d-4795-a8f9-71db5031bf8b)
