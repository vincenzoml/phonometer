# Phonometer - Web-based Sound Level Meter

A simple, browser-based sound level meter that uses your device's microphone to measure and display audio levels in real-time.

🔴 [Live Demo](https://YOUR_USERNAME.github.io/phonometer/)

## Features

- Real-time audio level monitoring
- Logarithmic scale (dB) for natural audio level representation
- Adjustable sensitivity (up to 300%)
- Noise threshold control to filter out background noise
- Smooth visual updates with performance optimization
- Clean, minimalist user interface
- Works directly in the browser - no installation needed

## Usage

1. Open the `index.html` file in a modern web browser
2. Allow microphone access when prompted
3. Adjust controls as needed:
   - **Sensitivity**: Increase or decrease the meter's responsiveness (1-300%)
   - **Noise Threshold**: Filter out background noise by setting a minimum level

## Technical Details

- Uses the Web Audio API for audio processing
- Implements proper decibel (dB) calculation using `20 * log10(amplitude)`
- Updates at 10Hz (every 100ms) for optimal performance
- Includes signal smoothing for stable readings

## Browser Support

Works in any modern browser that supports the Web Audio API and `getUserMedia` API.

## Privacy

The application only processes audio data locally in your browser - no data is sent to any server. 