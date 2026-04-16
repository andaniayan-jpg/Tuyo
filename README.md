# Tuyo
<img width="1065" height="1476" alt="ChatGPT Image Apr 16, 2026, 12_56_30 PM" src="https://github.com/user-attachments/assets/e08fde71-1200-44c2-85e0-323048dcdb58" />

Tuyo is an interactive AI speaker that connects to an external device with an embedded LLM. It has a  MCU that manages the operations, which makes it responsive and intelligent.
This project is a smart voice assistant speaker inspired by Alexa.

You can speak to it using your voice, and it can:

Play music
Respond using AI
Understand voice commands

The whole system is built using:

ESP32 as the main controller
Microphone as the input
Speaker as the output

What Makes It Special?

This is not an off-the-shelf product
I designed the complete PCB by myself
It connects to an AI model (LLM) and gives responses in real time
It is a compact Alexa-like device built completely from scratch

Why I Built It

I wanted to:

Understand how smart voice assistants actually work
Build my own AI-powered hardware device
Learn both hardware and software together

Instead of only using Alexa,
I wanted to create my own version

How It Works

Here is the simple workflow:

You speak into the microphone
The ESP32 captures and processes the voice input
It sends the request to an AI model (LLM)
The AI generates a response
The speaker plays the response back

Components Used

ESP32-WROOM-32 (main controller)
ICS-43434 I2S Microphone
MAX98357A Audio Amplifier
External Speaker
TP4056 Battery Charging IC
AMS1117 3.3V Regulator
CH340C USB-to-UART Converter
USB-C Port
LiPo Battery

How to Use It

Connect the battery or plug in USB-C
Turn on the device
Speak commands such as:

“Play music”
“Tell me a fact”
“What is AI?”

The device will then respond through the speaker

<img width="963" height="765" alt="image" src="https://github.com/user-attachments/assets/1b2a9ee0-9495-458d-ada0-d4079647eedd" />
<img width="1406" height="1024" alt="Screenshot 2026-04-13 220718" src="https://github.com/user-attachments/assets/c96e4882-ee7f-40f7-91fb-ac39fd491f04" />

