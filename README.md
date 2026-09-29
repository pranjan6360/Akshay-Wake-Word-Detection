# Akshay-Wake-Word-Detection
Akshay – Low-Latency Voice Activation for Edge Devices

Project Overview

This project aims to build a voice-activated system that can recognize the wake word “Akshay” directly on an edge device, without depending on cloud-based speech recognition.

The system uses an ESP32 microcontroller and an INMP441 microphone to capture audio. A lightweight machine-learning model processes the audio and detects when the wake word is spoken. When “Akshay” is detected, the ESP32 turns on an LED as a simple response.

How It Works

The microphone captures the user's voice.

The audio is processed into features for the trained model.

The model checks whether the wake word “Akshay” is present.

When the word is detected, the ESP32 activates the LED.

Main Components

ESP32 DevKit V1

INMP441 I2S microphone

LED and resistor

A lightweight TensorFlow Lite model

Arduino IDE

Project Goal

The goal is to develop a simple, low-latency, and efficient voice-activation system that runs locally on an edge device. This project can later be extended to trigger other actions or send commands to a server.

Current Status

A wake-word model has been trained and integrated into the ESP32-based prototype. The LED is used to indicate wake-word detection. Further testing is needed to evaluate reliability in different environments.
