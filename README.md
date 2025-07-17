Objective:
Remotely control the direction and speed of a DC motor using HTTP requests sent between two ESP32 modules.

Setup & Tools:

2 × ESP32

DC Motor + L298N Motor Driver

Buttons, Jumper Wires

Arduino IDE, same WiFi/HTTP libraries

Summary:
A client ESP32 sends "Forward", "Backward", and "Stop" commands via HTTP based on button inputs. The server ESP32 receives these and drives the motor accordingly using PWM and H-bridge logic. Speed is smoothly ramped using ledcWrite().

🔗 Demo Video  
https://www.youtube.com/shorts/ECScYEonM-E?feature=share
