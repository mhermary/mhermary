# Hi there 👋, my name is Matthew Hermary
#### Firmware Developer


Skills: C, C++, Python, System Verilog, VHDL, MATLAB, ARM assembly

Tools: Altium, KiCAD, LTSPICE, Xilinx Vivado, Cadence Simvision, Synopsys Spyglass

- 💻  I’m currently working on this page. 
- 🌏  I’m currently learning image processing in Python, and Mandarin 

![GitHub stats](https://github-readme-stats.vercel.app/api?username=mhermary&show_icons=true)  

[<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/github.svg' alt='github' height='40'>](https://github.com/mhermary)  [<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg' alt='linkedin' height='40'>](https://www.linkedin.com/in/hermary/)  [<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/icloud.svg' alt='website' height='40'>](mhermary.github.io)  

## Projects
### [Augmented Reality Bike Helmet](https://brandenjvoss.github.io/AR_bike_helmet/) - *C++, Arduino*
**First Place - IEEE Victoria Technical Project Award**

As bike usership has increased, as well as the growth of e-bikes, awareness of ones surroundings has become more important, especially with the high speeds of e-bikes.
This project includes a rear-facing camera which was programmed to use object detection (TinyYOLOv2) to detect cars approaching from the rear, and indicate on a heads up display which side the car is approaching from. The project included an OLED display and a visor to let the cyclist keep their eyes on the road, as well as an Arduino to relay the message from the rear camera (HuskyLens) to the OLED. A battery pack was used to power the electronics, and it all fit snugly a standard bike helmet.

### [Side Channel Attack defense](https://github.com/mhermary/Side-channel-attack) - *C, ARM assembly*
Side Channel attacks are security exploits that gather information based on the implementation of a computer protocol or algoritm, rather than targeting flaws in the algorithm itself. This project features limitations on measurements due to the University Campus being closed for health issues.
This is an embedded system that includes redundant operations to mask in a password character has been properly or improperly guessed. A large portion of this project was combing through the assembly to look for optimizations. 


### [PWM Signal Generator and Monitor](https://github.com/mhermary/pot_monitor_PWM_signal_generator) - *C*
This embedded system monitors a potentiometer's voltage and relays that to a 555 circuit to generate a PWM signal whose frequency varies based on the relayed voltage.
This project included diving into the STM32 registers to manually set bits for timers, interrupts, and other functions to measure the incoming PWM signal frequency.
The frequency and potentiometer resistance were displayed on an LCD using manual handshaking.

### [Smart Alarm Clock Blinds](https://github.com/mhermary/Alarm_clock_blinds) - *C++, Arduino*
Programmed an ESP32 to automatically open blinds with alarm times and commands being passed through MQTT while using NTP to sync time.
