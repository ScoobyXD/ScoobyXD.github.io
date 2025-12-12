# ScoobyXD.github.io

# Embedded Software Engineer
![collage](/assets/collage.png)
Hi! I'm Jonathan Kim, I'm a former full stack web developer with 2 years of experience with a huge passion for embedded systems!
Working with hardware has been much more fun and every project I've done helped me learn a whole lot.
I'm currently pursuing a M.S. in Embedded Systems at UC Irvine.

## Education					       		
M.S. Embedded Systems	| UC Irvine (Sept. 2025 - Expected Dec. 2026)	 			        		
B.S. Management Information System| Santa Clara University (2018 - 2022)

## Work Experience
**Embedded Software Engineer Contractor @ Mirae Opus (Sept 2025 - Present)**
- Designed an ESP32-based speech-to-text and text-to-speech device integrated with LLM APIs over Wi-Fi. Implemented I²S interfaces for microphone, speaker, and amplifier, and I²C communication for a 9-axis IMU.
- Implemented FreeRTOS and interrupts to create a scalable system for additional features.
- Applied DMA transfer and transmitted audio/IMU data to a local web server providing a real-time dashboard of system activity. 
- Designed a 4-layer PCB board housing an ESP32 C6 WROOM module, USB-C port, speaker amplifier, battery management, impedance matching, and various ESD, hot-plug, and over-current protections.
- Worked in a Linux environment writing C/C++, not Arduino.


**Full Stack Software Developer @Leidos QTC (Jan 2023 - Oct 2024)**
- Developed and maintained .NET enterprise applications vital to the business’s core revenue stream, contributing to revenue growth from $500 million to over $1 billion annually. As a member of the team responsible for core user-facing applications, - I ensured seamless functionality during this period of rapid expansion.
- Core applications facilitated appointment scheduling between medical providers and veterans worldwide. They also efficiently displayed relevant information and medical documents, many spanning thousands of pages.
- Developed a robust backend using C#, frontend in JavaScript/jQuery, enhancing user experience for scheduling medical appointments.
- Integrated a PDF compression service, significantly improving document processing speeds and resolving critical business bottlenecks. 
- Developed 50% of the code for a feature that digitized labor-intensive medical paperwork, previously done manually. This improvement has enhanced the efficiency of care delivery for tens of thousands of veterans.


## Projects
### STM32 Sentry Turret
![turret](/assets/turret.png)
[Video Link To See It Shoot!](/assets/turretdemo.mp4)

- Built a sentry turret that shoots Nerf bullets using a STM32, no HAL library, direct bit register configuration. 
- Wrote and implement own drivers for PWM, UART, I2C, and interrupts without any libraries. 
- Controlled turret through interrupt-based UART wireless keyboard commands. 
- Modified Nerf gun, designed turret in Fusion 360, 3D-printed and assembled structure.

### First Project - Rover
![rover](/assets/rover.png)
[Video Link To See It Move!](/assets/roverdemo.mp4)

- A small rover that can zip around quickly using ESP32 UART commands (although it doesn't turn properly)
- Uses an ESP32, motor driver, 4 motors, and a 3D printed body I designed on Fusion 360

![test](/assets/openednerfgun.jpeg)
