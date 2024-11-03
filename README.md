# Hello World MQTT Application

This Python application demonstrates how to integrate SQLite3 for local data storage and MQTT for messaging. It creates and manages a simple SQLite database to store messages and uses MQTT to receive and insert messages into the database.

## Features

- **SQLite3 Database**: Creates and manages a database to store messages.
- **MQTT Integration**: Connects to an MQTT broker to receive messages and store them in the database.
- **Message Handling**: Inserts received MQTT messages into the SQLite database and retrieves the latest message.

## Requirements

- **Python 3**: Ensure you have Python 3 installed.
- **SQLite3**: Installed by default with Python 3.
- **paho-mqtt**: MQTT client library for Python.

## Installation

1. **Install Dependencies**:

   ```bash
   pip install paho-mqtt


dpkg-deb --build hello_world
dpkg -c device_management.deb
sudo dpkg -i hello_world.deb
hello

mosquitto_pub -h localhost -t hello-world/topic -m "Hello, MQTT!"
