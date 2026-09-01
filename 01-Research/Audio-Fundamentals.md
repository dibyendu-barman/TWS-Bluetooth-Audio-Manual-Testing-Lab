# Audio Fundamentals

## 1. Purpose

This document records the audio concepts required for manual testing of TWS Bluetooth audio devices.

## 2. Digital Audio

Digital audio represents sound using discrete numerical samples.

Simplified flow:

Analog Sound
↓
Sampling
↓
Quantization
↓
Digital Audio

## 3. Frequency

Frequency represents the rate of oscillation of a sound signal.

Unit:

Hz (Hertz)

Testing relevance:

- Bass response
- Midrange response
- High-frequency response
- Missing frequencies
- Distortion

## 4. Amplitude

Amplitude represents the magnitude of an audio signal.

Testing relevance:

- Volume behavior
- Loudness changes
- Channel balance
- Minimum and maximum volume

## 5. Sample Rate

Sample rate represents the number of samples captured per second.

Examples:

- 8 kHz
- 16 kHz
- 44.1 kHz
- 48 kHz
- 96 kHz

## 6. Bit Depth

Bit depth represents the number of bits used for each audio sample.

Common examples:

- 8-bit
- 16-bit
- 24-bit
- 32-bit

## 7. PCM

PCM stands for Pulse Code Modulation.

PCM is a fundamental representation of digital audio.

## 8. Bitrate

Bitrate represents the amount of audio data processed or transmitted per unit time.

Common unit:

kbps

## 9. Bluetooth Audio Codecs

Common Bluetooth audio codecs include:

- SBC
- AAC
- aptX family
- LDAC
- Opus in supported implementations

Actual codec support depends on the host device, TWS device and software/firmware.

## 10. Audio Latency

Audio latency is the delay between an event and the corresponding audio output.

Testing relevance:

- Video synchronization
- Gaming
- Calls
- Audio start delay
- Recovery after interruption

## 11. Frequency Response

Frequency response describes system response across different frequencies.

Manual observations may include:

- Bass response
- Midrange response
- Treble response
- Channel imbalance
- Unusual sound

## 12. Signal-to-Noise Ratio

SNR compares desired signal level with unwanted noise.

Possible observations:

- Hiss
- Static
- Hum
- Background noise

## 13. Distortion

Distortion occurs when output does not accurately reproduce the input signal.

Possible audible observations:

- Crackling
- Buzzing
- Harshness
- Clipping

## 14. Stereo Testing

Stereo testing verifies correct left/right channel reproduction.

Left test signal:
→ Left earbud

Right test signal:
→ Right earbud

## 15. QA Principle

Audio testing should distinguish between:

- Objective measurement
- Subjective listening observation
- Expected behavior
- Actual behavior
- Confirmed defect
- Possible defect
