# Serban Afrasinei

Computer engineering student at the Technical University of Cluj-Napoca, final year, graduating
July 2027.

I work on real-time control and perception for small robots: C++17 firmware on ESP32 with
FreeRTOS, motion planning for two-axis machines, and camera pipelines in Python with OpenCV.
I started in FIRST Tech Challenge, where I ran the programming side of the team for two years.

Most of what is here is coursework, competition code, or something I wanted to see run on my own
hardware. It is not all finished.

## Projects

**[ESP32 Mecanum robot controller](https://github.com/AfraIsNotAvailable/esp32_robot_controller)**  
Real-time control firmware for a four-wheel Mecanum platform. A FreeRTOS task pinned to a core
keeps a deterministic 50 Hz loop, subsystems have a fixed read/control/write lifecycle, and wheel
speeds go out through 20 kHz hardware PWM.

**[Arduino plotter](https://github.com/AfraIsNotAvailable/arduino-plotter)**  
GRBL-compatible G-code subset on an ATmega328P: arc interpolation, corner detection, a look-ahead
ring buffer and synchronised stepping across two axes. The Python host streams G-code and handles
feed hold and resume.

**[HICS](https://github.com/AfraIsNotAvailable/hics)**  
Hand gesture input from a camera. 21 landmarks per hand go into an SVM pose classifier, and a
state machine turns the labels into input events. OpenCV and MediaPipe on the sensor side.

**[tm-rl](https://github.com/AfraIsNotAvailable/tm-rl)**  
Trackmania agent. A Gymnasium environment talks to the game over a TCP bridge, and a PPO policy
trains on speed and checkpoint rewards.

**[BugReporter](https://github.com/AfraIsNotAvailable/bugreporter)**  
Team project: issue tracker with a Spring Boot backend, React front end and PostgreSQL, built
with a branch-per-feature workflow and pull request review.

## Tools I use

C++17, C, Python, Java, TypeScript, Bash. FreeRTOS, PlatformIO, CMake, Git, Docker, Linux (Arch).
OpenCV, MediaPipe, scikit-learn, TensorFlow/Keras, Stable Baselines3.

## Elsewhere

LinkedIn: [afrasinei-serban](https://www.linkedin.com/in/afrasinei-serban/)

Open to working-student or internship work in robotics, embedded systems, or perception. Email is
on my profile if you want to ask about any of the above.
