# Miniproject
# Smart Anti-Theft Wallet using ESP32

## Project Overview
This project is a Bluetooth-based anti-theft wallet system using ESP32.  
The wallet connects to the user's smartphone through Bluetooth.  
If the wallet goes out of Bluetooth range or disconnects, the buzzer alerts the user immediately.

---

#  Objectives
- Prevent wallet loss or theft
- Provide real-time alert system
- Create compact portable security device
- Use Bluetooth communication with ESP32

---

#  Components Required

| Component | Quantity |
|----------|----------|
| ESP32 Development Board | 1 |
| Active Buzzer | 1 |
| 3.7V Li-Po Battery | 1 |
| TP4056 Charging Module | 1 |
| Slide Switch | 1 |
| Jumper Wires | Few |
| Vibration Sensor (Optional) | 1 |

---

# Circuit Connections

## Buzzer Connection
| Buzzer Pin | ESP32 Pin |
|------------|-----------|
| Positive (+) | GPIO 25 |
| Negative (-) | GND |

---

## Vibration Sensor Connection (Optional)

| Sensor Pin | ESP32 Pin |
|------------|-----------|
| VCC | 3.3V |
| GND | GND |
| OUT | GPIO 34 |

---

---

#  Working Principle

1. ESP32 starts Bluetooth with name "SmartWallet"
2. User connects phone to ESP32
3. ESP32 continuously checks Bluetooth connection
4. If connection is lost:
   - Buzzer turns ON
5. If vibration is detected:
   - Buzzer turns ON

---

