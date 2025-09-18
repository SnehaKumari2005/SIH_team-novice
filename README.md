Automated plant leaf detection monitoring with CNN + Raspberry Pi and pesticide spraying system

Features:
Capture leaf images with a USB camera.
Classify leaves as Healthy, Moderately Healthy, or Unhealthy using a CNN
Trigger pesticide spraying automatically via GPIO-controlled relay
Lightweight and fully deployable on a Raspberry Pi

Setup:
1)Install Dependencies:pip install tensorflow opencv-python numpy RPi.GPIO
2)Connect Hardware
Connect water pump to the relay
Connect relay to GPIO pin 14
3)Place your Model:Copy infectionclassifier.h5 to /home/pi/ or update the path in the code
4)Run the Script

Folder Structure:
Data
-healthy
-moderately healthy
-unhealthy

Acknowledgements:
The core Python code for leaf health detection and automated spraying was generated with the help of ChatGPT by OpenAI.
- TensorFlow, OpenCV, and RPi.GPIO libraries were used for machine learning, image processing, and hardware control.

