# Acoustic Signal Monitoring for Drilling operation
This project aims to develop a system that monitors the operational state of drilling machines using acoustic sensors by capturing and analyzing acoustic signals.
The system can detect variations in machine behavior, abnomality and enables in-situ process monitoring and machine health in process.

**Sound Library of Drilling materials**
<br>
An experiment was conducted to capture mechanical sound waves generated during the drilling materials while recording sound using a Logitech C920 camera.
Drilling was performed at two feed rates are 50 and 150 mm/min, three power levels are 60, 80, and 100 Watt and drill bit had a diameter of 2.4 mm.
<br>
<br>
The experiment start with Power 60W at feed rate 50 mm/min. The drill moves down, press into the material and penetrates the material. We observed the frequency that occurs and there may be other frequencies because that frequency also occurs resonance. The power level was increased to 80 and 100W that observed high frequency, correlating with the increased force applied to the material.
<br>
<br>
Acrylic drilling, this material is a thickness of 3 mm.
<br>
[![Drilling Acrylic](https://img.youtube.com/vi/ywRKRw5kEJM/0.jpg)](https://www.youtube.com/watch?v=ywRKRw5kEJM)
<br>
<br>
Plastic PTFE drilling, this material is a thickness of 5 mm.
<br>
[![Drilling PTFE](https://img.youtube.com/vi/8MmbGZMqn0s/0.jpg)](https://www.youtube.com/watch?v=8MmbGZMqn0s)
<br>
<br>
Hardwood drilling, this material is a thickness of 10 mm.
<br>
[![Drilling Hardwood](https://img.youtube.com/vi/IHWydRdQkqU&t=1s/0.jpg)](https://www.youtube.com/watch?v=IHWydRdQkqU&t=1s)

## TXT File
The file contains a G-code script for CNC drilling operations.
<br>
It includes:
- Servo Control: Adjustable servo widths for different operations.
- Feedrate Settings: Adjustable feedrates for speed.
- Coordinates: Adjustable positions for drilling at X-axis, Y-axis and Z-axis.

**How to Use**
1. Download `TXT File`.
2. If you have software of CNC or 3D printer, can upload to open the file.

## CSV File
The file contains a time and event data for drilling operations.
<br>
It includes:
- Time: time for each event.
- Event: the description of drilling event.

**How to use**
1. Download `CSV File`.
2. If you have MATLAB or other program, can upload to open the file.
3. 
