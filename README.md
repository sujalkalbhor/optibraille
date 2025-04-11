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
