# Audio Visualizer

A real-time audio visualizer that creates colorful frequency bars from your microphone input. Features customizable colors, responsive design, and screen wake lock for mobile devices.

## Features

- **Real-time Audio Visualization**: Live frequency analysis with smooth bar animations
- **Customizable Colors**: Interactive color pickers for low, mid, and high frequencies
- **Brightness Control**: Adjustable intensity slider for optimal viewing
- **Fullscreen Mode**: Immersive full-screen visualization experience
- **Mobile Responsive**: Optimized layout and controls for mobile devices
- **Screen Wake Lock**: Keeps mobile screens awake during visualization (Chrome/Edge)
- **High-DPI Support**: Crisp visuals on retina displays

## Usage

1. Open `index.html` in your web browser
2. Click "Start Listening" to begin visualization
3. Allow microphone access when prompted
4. Customize colors using the color pickers
5. Adjust brightness with the slider
6. Click "Fullscreen" for immersive viewing
7. Click "Stop" to end visualization

## Browser Compatibility

- **Chrome/Edge**: Full support including wake lock
- **Firefox**: Full support except wake lock
- **Safari**: Full support except wake lock
- **Mobile browsers**: Responsive design with touch-optimized controls

## Technical Details

- Uses Web Audio API for real-time frequency analysis
- Canvas-based rendering with 60fps animations
- Screen Wake Lock API prevents mobile screen timeout
- Responsive design with CSS flexbox and media queries
- High-DPI canvas rendering for sharp visuals

## Controls

- **Start/Stop**: Begin or end audio capture and visualization
- **Fullscreen**: Toggle immersive full-screen mode (ESC to exit)
- **Low Freq Color**: Color for bass frequencies (red default)
- **Mid Freq Color**: Color for mid-range frequencies (green default)  
- **High Freq Color**: Color for treble frequencies (blue default)
- **Brightness**: Intensity multiplier from 0.1x to 2x

The visualizer smoothly interpolates colors across the frequency spectrum and applies amplitude-based intensity for dynamic visual effects.