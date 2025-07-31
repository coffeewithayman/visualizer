# Audio Visualizer

A real-time audio visualizer that creates colorful frequency bars from your microphone input. Features customizable colors, responsive design, and screen wake lock for mobile devices.

## Features

- **Real-time Audio Visualization**: Live frequency analysis with smooth bar animations
- **Customizable Colors**: Interactive color pickers for low, mid, and high frequencies
- **Brightness Control**: Adjustable intensity slider for optimal viewing
- **Fullscreen Mode**: Immersive visualizer-only fullscreen optimized for mobile landscape
- **Mobile Responsive**: Optimized layout and controls for mobile devices
- **Screen Wake Lock**: Keeps mobile screens awake during visualization (Chrome/Edge)
- **High-DPI Support**: Crisp visuals on retina displays
- **Multiple Visualizations**: Five styles that cycle every 10 seconds with manual selection

## Usage

1. Open `index.html` in your web browser
2. Click "Start Listening" to begin visualization
3. Allow microphone access when prompted
4. Customize colors using the color pickers
5. Adjust brightness with the slider
6. Pick a visualization style from the dropdown or watch it change every 10 seconds
7. Click "Fullscreen" for immersive visualizer-only viewing (rotate to landscape on mobile)
8. Click "Stop" to end visualization

## Browser Compatibility

- **Chrome/Edge**: Full support including wake lock
- **Firefox**: Full support except wake lock
- **Safari**: Full support except wake lock
- **Mobile browsers**: Responsive design with touch-optimized controls

## Technical Details

- Uses Web Audio API for real-time frequency analysis
- Canvas-based rendering with 60fps animations
- Screen Wake Lock API prevents mobile screen timeout
- Visualizer-only fullscreen API for immersive experience
- Mobile landscape optimization with responsive design
- High-DPI canvas rendering for sharp visuals

## Controls

- **Start/Stop**: Begin or end audio capture and visualization
- **Fullscreen**: Enter visualizer-only fullscreen mode with floating exit button
- **Low Freq Color**: Color for bass frequencies (red default)
- **Mid Freq Color**: Color for mid-range frequencies (green default)  
- **High Freq Color**: Color for treble frequencies (blue default)
- **Brightness**: Intensity multiplier from 0.1x to 2x
- **Visualizer**: Dropdown to choose a visualization style or let it cycle automatically

The visualizer smoothly interpolates colors across the frequency spectrum and applies amplitude-based intensity for dynamic visual effects.