# Bluetooth Connection States

## 1. Purpose

This document describes the major Bluetooth/TWS connection states and the transitions that will be tested during the 30-day manual testing project.

## 2. Simplified State Model

Power OFF
    ↓
Discovery
    ↓
Pairing
    ↓
Connected
    ↓
Audio / Call / Control
    ↓
Disconnected
    ↓
Reconnection
    ↓
Connected

## 3. Discovery

The host searches for available Bluetooth devices.

QA areas:

- Device visibility
- Device name
- Discovery consistency
- Discovery timing

## 4. Pairing

The host establishes the required relationship/security information with the TWS device.

QA areas:

- First-time pairing
- Cancelled pairing
- Failed pairing
- Re-pairing

## 5. Connected

The host and TWS device have an active Bluetooth connection.

QA areas:

- Audio
- Media control
- Calls
- Microphone
- Connection stability

## 6. Disconnected

The active connection is lost.

Possible causes:

- Bluetooth OFF
- Device powered OFF
- Out of range
- Host restart
- Device restart
- Connection failure

## 7. Reconnection

The previously connected device attempts to establish the connection again.

QA areas:

- Automatic reconnection
- Manual reconnection
- Reconnection time
- Audio recovery
- Control recovery

## 8. Re-Pairing

The existing pairing relationship is removed and the device is paired again.

## 9. Important State Transitions

### Transition 1

Discovery → Pairing

### Transition 2

Pairing → Connected

### Transition 3

Connected → Disconnected

### Transition 4

Disconnected → Reconnection

### Transition 5

Reconnection → Connected

### Transition 6

Paired → Forget → Discovery → Pairing

## 10. QA Principle

Every important state transition should be considered a potential test scenario.

Expected behavior should be based on documented requirements or established product behavior.

Observed behavior should be recorded separately.
