# T-Smart-Home-IoT
Control lights/fans via RainMaker App. Send alerts if unauthorized motion is detected. RTOS ensures sensor monitoring, alerts, and control run in parallel. Voice assistant integration for hands-free smart home control. OTA updates for adding new security features. 

# Key Features
1. Real-Time Multitasking with FreeRTOS - Manages concurrent tasks such as sensor data collection, cloud communication, push notifications, voice commands, and OTA firmware updates efficiently.
   
3. Cloud Integration via ESP RainMaker - Allows remote monitoring and control of devices through the cloud, providing real-time insights via the Espressif Insights Dashboard.
   
5. Voice Assistant Support - Integrates with Google Assistant, enabling hands-free control of home devices using natural language commands.
   
7. Security Alerts - Implements real-time motion detection to identify unauthorized intrusions and sends immediate push notifications to homeowners.
   
9. Over-the-Air (OTA) Firmware Updates - Facilitates secure and scalable firmware updates without the need for physical access, ensuring the system remains up-to-date with new features and bug fixes.

# Components Used
1. ESP32-C3 Microcontroller: The central processing unit of the system, chosen for its Wi-Fi and Bluetooth capabilities.​

2. Motion Sensors: Detect unauthorized movements within the premises to trigger security alerts.​

3. ESP RainMaker: Provides cloud connectivity for remote device management and monitoring.​

4. FreeRTOS: An open-source real-time operating system that enables efficient multitasking within the microcontroller.​

5. Espressif Insights Dashboard: Offers real-time visualization and insights into device performance and status.​

6. Google Assistant Integration: Allows users to control devices using voice commands for enhanced user interaction.​

