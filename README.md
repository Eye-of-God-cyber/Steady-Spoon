# SteadySpoon – Tremor Stabilizing Spoon

SteadySpoon is an assistive device designed for Parkinson’s patients to reduce hand tremors while eating.

The system uses an MPU6050 gyroscope sensor and servo motors to stabilize the spoon in real time.

## Features
- Real-time tremor detection
- Gyroscope + accelerometer sensing
- PID based stabilization
- Portable battery powered design
- Low-cost assistive technology

## Hardware Used
- Arduino Nano / ESP32
- MPU6050 (Gyroscope + Accelerometer)
- SG90 / MG90S Servo Motors
- Li-ion Battery
- TP4056 Charging Module

## Working Principle
1. MPU6050 detects tremor motion
2. Microcontroller processes sensor data
3. Stabilization algorithm calculates correction
4. Servo motors counteract tremor movement
5. Spoon remains stable during eating

## Applications
- Parkinson’s disease assistance
- Motor disorder support
- Medical robotics research

## Future Improvements
- Machine learning tremor prediction
- Bluetooth monitoring
- Smaller actuator design
