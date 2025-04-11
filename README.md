# optibraille
OptiBraille is a smart assistive device for visually imparied. It uses a camera to detect text or faces and converts printed or digital text into real-time tactile Braille using dynamic cells, helping visually impaired users access both audible and textual information effectively.
Features:
Camera-Based Text to Braille Conversion-Captures printed text using a camera and converts it into Braille using 6 solenoids (1 Braille character at a time).
Braille Display-Electro-mechanical solenoids controlled via 4-channel and 2-channel relay modules for tactile Braille output.
Fall Detection-Detects accidental falls using sensors and sends alerts to caretakers.
GPS Tracking-Real-time location tracking of the user, accessible via a web interface for caretakers.
Health Monitoring-Tracks basic health parameters like heart rate and temperature.
Face Recognition-Identifies familiar faces and notifies the user via audio or tactile feedback.

Hardware Used:
Raspberry Pi 4 Model B, Camera Module, 6 x Solenoids, 4-Channel Relay Module, 2-Channel Relay Module, GPS Module, Accelerometer/Gyroscope (e.g., MPU6050), Heart Rate Sensor, Temperature Sensor, Speaker / Audio Output (optional for alerts)

Software Tools & Libraries:
Python (OpenCV, GPIO, etc.),
Raspberry Pi OS,
Face Recognition Library,
GPS & Sensor Communication Libraries,
Flask (for web dashboard, if implemented).

Working
1. Text Capture & Braille Conversion:The smart glasses capture text using the camera. The Raspberry Pi processes the image and converts recognized text into Braille patterns, activating solenoids to form one character at a time.
2. Fall Detection:The device constantly monitors motion. Sudden impacts or falls trigger an emergency alert.
3. GPS Tracking:The user's location is tracked and sent to the caretaker's web dashboard or mobile interface.
4. Health Monitoring:Real-time heart rate and temperature data are collected and logged for analysis and alerts.
5. Face Recognition:When the device detects a face, it compares it against a trained database and informs the user if the person is recognized.

Use of project:
Use of smart glasses for face recognization:
When a known face is detected by the camera, the system announces their name through audio output (via earphones/speaker).This helps the visually impaired user know who is nearby.
Use of fall detection:
Wearer doesn’t need to press anything.Falls are automatically detected and help is alerted instantly.
Use of Live Location Tracking:
Caretakers can view the live location of the user anytime.Adds safety and tracking in outdoor environments.
Use of braille output:
Accessibility for the Visually Impaired, Real-Time Reading, Supports Literacy, Portability, etc.

Here’s an example of a 3D design of Vision Aid smart glasses:
(https://drive.google.com/file/d/1lJXC0LVtqAoDdlRDR8MLiYQhKt4AmH-Z/view?usp=sharing)
website for the care taker:
(https://drive.google.com/file/d/1GCj9LUtgGstAuyvdAIvFyx2cA3plLgtC/view?usp=sharing)
location tracking:
(https://drive.google.com/file/d/1GBjUMsxiWvr86hDa00s407lgi-ID-38f/view?usp=sharing)
smart glasses with embedded raspberry pi camera:
(https://drive.google.com/file/d/1GAvSNjvQtWQRGIguRckCu8iQLTe_mEm2/view?usp=sharing)
stick with health monitoring system:
(https://drive.google.com/file/d/1G8mS5LHzPDgXRE6yjdcH3rB6As8oetHI/view?usp=sharing)
braille output:
(https://drive.google.com/file/d/1GJpqPt-GmextBNcORV2PrmpXCd3PhT1M/view?usp=sharing)
