# TWS Architecture

## 1. System Overview

A TWS Bluetooth audio system consists of:

- Host device
- Left earbud
- Right earbud
- Charging case
- Speakers
- Microphones
- Battery/power system
- Bluetooth communication

## 2. Simplified Architecture

Android Smartphone
        |
        | Bluetooth
        |
        v
TWS Device
   |          |
 Left       Right
 Earbud     Earbud
   |          |
Speaker     Speaker

Charging Case
     |
Battery / Charging

## 3. Audio Path

Phone
  ↓
Bluetooth Audio
  ↓
TWS Device
  ↓
Left / Right Earbuds
  ↓
Speakers

## 4. Media Control Path

Earbud Control
  ↓
Bluetooth Control
  ↓
Phone
  ↓
Media Application

## 5. Call Path

Phone
  ↕
Bluetooth Voice Communication
  ↕
TWS
  ↓
Speaker / Microphone

## 6. QA Testing Areas

### Host Device

- Bluetooth discovery
- Pairing
- Connection
- Audio routing
- Call routing

### Left Earbud

- Audio
- Connection
- Controls
- Charging

### Right Earbud

- Audio
- Connection
- Controls
- Charging

### Charging Case

- Charging
- Power behavior
- Earbud storage
- Connection state
