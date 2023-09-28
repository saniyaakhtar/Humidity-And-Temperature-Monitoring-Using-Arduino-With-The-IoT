# Humidity and Temperature Monitoring using Arduino and IoT

## Description
With the advent of the Internet of Things (IoT) in homes and industries, it is now possible to control and monitor electrical or electronic equipment remotely. This project demonstrates humidity and temperature monitoring using Arduino microcontroller (MCU) and IoT technology. It allows for the collection and visualization of data from a DHT-11 sensor on the ThingSpeak platform. IoT applications with Arduino are accessible and enjoyable for beginners in the field of electronics and programming.

## Components
Here is a list of components used in this project:

- **Arduino MCU:** The central microcontroller responsible for data collection and transmission.
- **DHT11 Sensor:** A sensor used to measure humidity and temperature.
- **ESP8266 Wi-Fi Module:** Enables the MCU to connect to the Internet and transmit data.
- **ThingSpeak Platform:** An open-source data platform for storing and visualizing IoT data.
- **Wi-Fi Modem:** Provides the local Internet connection.
- **PC/Smartphone:** Used for monitoring and configuring the system.

## Use Cases
This project has several potential use cases, including:

1. **Home Climate Control:** Monitor and control humidity and temperature in your home.
2. **Industrial Applications:** Use in industries to ensure optimal environmental conditions.
3. **Agriculture:** Monitor environmental conditions in greenhouses or farms.
4. **Server Room Monitoring:** Keep track of temperature and humidity in server rooms.
5. **Research and Education:** Used for scientific experiments and educational purposes.
6. **Remote Monitoring:** Monitor conditions in remote locations from anywhere in the world.

## Working Principle
The project utilizes a DHT11 sensor to measure humidity and temperature. The sensor sends this data to a digital pin on the Arduino MCU. From there, the MCU, with the help of an ESP8266 Wi-Fi module, uploads the humidity and temperature values to the ThingSpeak cloud platform at regular intervals.

To set up the project:
1. Register on ThingSpeak and create a new channel for humidity and temperature.
2. Obtain the write API key and replace it in the program.
3. Configure the Wi-Fi settings in the program to match your network.
4. Compile and upload the program to the Arduino MCU.
5. Once uploaded, the MCU will start uploading data to ThingSpeak.
6. Access the ThingSpeak platform to view the humidity and temperature data graphically.

This project enables real-time monitoring and control of environmental conditions using IoT technology.

Author's prototype:
![Prototype](insert_image_url_here)

