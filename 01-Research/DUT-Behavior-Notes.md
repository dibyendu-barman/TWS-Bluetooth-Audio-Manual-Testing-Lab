# DUT Behavior Notes

## Device Under Test

boAt Airdopes Joy

## 1. Power

Questions to investigate:

- How do the earbuds power ON?
- How do they power OFF?
- Does removing them from the case power them ON?
- What happens when they are placed back in the case?

## 2. Bluetooth Discovery

Questions:

- Does the device appear in Android Bluetooth settings?
- What device name is displayed?
- How long does discovery take?
- Does the device appear consistently?

## 3. Pairing

Questions:

- Can the device pair successfully?
- Does pairing require user confirmation?
- What happens after unpairing?
- Can the device pair again?

## 4. Audio

Questions:

- Does music start correctly?
- Is audio present in both earbuds?
- Does pause work?
- Does resume work?
- Does volume control work?

## 5. Calls

Questions:

- Can an incoming call be answered?
- Can the call be terminated?
- Does the microphone work?
- Does audio switch correctly between music and call?

## 6. Reconnection

Questions:

- Does the device reconnect automatically?
- What happens after Bluetooth OFF/ON?
- What happens after phone restart?
- What happens when the device goes out of range?

## 7. Battery

Questions:

- Is battery information visible?
- What happens at low battery?
- Does charging behavior work correctly?

## 8. Observations

## Day 2 Observations
Date: 28/08/2026
Time: 8:49 PM

Device Name: Airdopes Joy
Device discovered: Yes
Approximate discovery time: 3 Sec
Device previously paired: Yes
Observation: Device appeared approximately 2-3 seconds after opening the case.

Pairing successful: Yes

Pairing time: Approximately 3 seconds

User interaction required: Yes

Device status after pairing: Active

Observation: Displaying DUT name: Airdopes Joy. Status: Active; Battery: 100%

Audio playback: Pass
Left audio: Pass
Right audio: Pass
Pause: Pass
Resume: Pass
Volume control: Pass

Observation: Audio playback is working fine.

Bluetooth OFF behavior: Music Pause

Bluetooth ON behavior: Auto-connected

Automatic reconnection: Yes

Manual reconnection required: No

Audio recovered: No

Observation: Automatic reconnection happens after Bluetooth turns on, but music pauses.

# Day 4 Audio Observations

## Stereo

Left-channel test: Sounds Good

Right-channel test: Sounds Good

Left/right balance: Both are ok

## Silence / Noise

Background noise observed: No background noise

Observation: In silence audio, there is no background noise

## Frequency

100 Hz:

1 kHz:

10 kHz:

## Volume

Minimum:

Low:

Medium:

High:

Maximum:

## Audio Interruption

Bluetooth OFF: Audio paused due to disconnection

Bluetooth ON: Audio paused after Bluetooth turned ON.

Audio recovery: Must be turned ON to play the audion/music.

## Windows Comparison

Android audio behavior: After connecting Airdopes Joy to my Android mobile, if I am playing music, both the left and right channels work well.

Windows audio behavior: After connecting Airdopes Joy to my Windows system, if I am playing music, both the left and right channels work well.

Differences observed: No differences, for both device Airpodes Joy working as expected.
