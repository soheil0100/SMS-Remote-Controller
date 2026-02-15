# SMS Remote Controller System
 
A GSM-based remote control system developed using Arduino.  
The system allows users to control electrical devices remotely via SMS commands.

--- 

## Overview

The SMS Controller is designed to provide remote device management using GSM communication.

Users can send predefined SMS commands to control connected loads such as:

- Lights
- Motors
- Pumps
- Industrial relays

The system verifies authorized numbers and executes commands accordingly.

---

## Features

- Remote control via SMS
- Authorized number verification
- Multiple device control capability
- Relay-based output switching
- Proteus simulation included
- HEX file available

---

## Hardware Components

- Arduino Uno
- GSM Module (SIM800 / SIM900 compatible)
- Relay Module
- Power Supply
- Controlled Load (Lamp / Motor / etc.)

---

## Software

- Arduino IDE (.ino source included)
- AT command-based GSM communication
- Proteus simulation project
- Compiled HEX file

---

## Project Structure

```
SMS-Controller/
/
/// firmware/
/ /// sms_controller.ino
/
/// simulation/
/ /// proteus-project.pdsprj
/
/// images/
    /// simulation.png
```

---

## Working Principle

1. GSM module receives incoming SMS.
2. Arduino reads message using AT commands.
3. System verifies sender authorization.
4. If command is valid:
   - Corresponding relay output is triggered.
5. Optional feedback message is sent to user.

---

## Security Note

Authorized phone number is defined inside the source code.  
Modify it before deployment.

---

## Future Improvements

- Password-based command verification
- Encrypted SMS parsing logic
- IoT cloud integration
- Mobile app control
- PCB design for compact deployment

---

## License

This project is licensed under the MIT License.

---

## 👥 Authors

Developed collaboratively by:

- Soheil Ahmadi
- Omid Menbari
  
Open-source embedded system project.
