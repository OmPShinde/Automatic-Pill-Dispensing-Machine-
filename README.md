# Automatic-Pill-Dispensing-Machine-
SEM III Arduino based Mini Project
# Smart Pill Dispensing System (Arduino)

An Arduino-based pill dispenser that releases medication at scheduled times and adds safety and monitoring features to improve medication adherence.

## Project Details

| Field      | Details                                                          |
|------------|------------------------------------------------------------------|
| Course     | SY Sem-III, Mini Project I                                       |
| Department | Electronics and Telecommunication Engineering                    |
| College    | Pillai College of Engineering, University of Mumbai              |
| Year       | A.Y. 2024-25                                                     |
| Guide      | Prof. Sweta Waghmare                                             |
| Team Size  | 5 members                                                        |

## Features

- Scheduled dispensing: a DS3231 real-time clock (RTC) triggers a servo motor to release pills at set times.
- Dispense confirmation: an IR sensor detects that a pill has been released.
- Pickup detection: a PIR sensor detects when the user approaches and collects the pill.
- Tilt safety: a tilt sensor pauses dispensing if the device is moved or tilted, preventing accidental release.
- Storage monitoring: a DHT11 sensor measures temperature and humidity, with alerts if readings go out of range.
- User feedback: a 16x2 LCD shows time, temperature, humidity and status messages, while a buzzer provides audible alerts.

## Components

| Component    | Role                              |
|--------------|-----------------------------------|
| Arduino      | Main controller                   |
| Servo motor  | Pill release mechanism            |
| DS3231 RTC   | Accurate scheduling               |
| DHT11        | Temperature and humidity sensing  |
| IR sensor    | Confirms pill dispensed           |
| PIR sensor   | Detects user presence and pickup  |
| Tilt sensor  | Pauses system when tilted         |
| 16x2 LCD     | Status display                    |
| Buzzer       | Audible alerts                    |

## Working

1. The RTC keeps track of time.
2. At the scheduled time, the servo motor dispenses a pill.
3. The IR sensor confirms the pill was released.
4. The PIR sensor detects that the user has picked up the pill.
5. The LCD displays the status.

In parallel:

- The DHT11 readings are shown on the LCD, with alerts if they go out of range.
- The tilt sensor pauses the system if the device is tilted and triggers alerts.


## Future Scope

- Mobile app integration
- User-adjustable dispensing times
- Data logging
- Caregiver remote monitoring
- Support for multiple medications

## Note

This repository contains the project documentation only. The original Arduino source code is not included.
