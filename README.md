# Audio Tones - Binaural Beats & Voice Pattern Matcher

A real-time audio application for binaural beats generation and voice pattern harmonization.

## Features

- **Parallel Waveform Visualization**: Side-by-side windows showing voice input and audio tone patterns
- **Voice Pattern Matching**: Real-time percentage matching of voice input to target frequencies
- **Binaural Beats**: Generate theta, alpha, beta, delta, and gamma frequency ranges
- **Isochronic Tones**: Rhythmic audio pulses for brainwave entrainment
- **White Noise**: Adjustable frequency filtering from 100Hz to 19kHz
- **Real-time Audio Processing**: Live microphone input with frequency analysis

## Technology Stack

- **Frontend**: React + TypeScript + Vite
- **Backend**: Express.js + Node.js
- **Audio**: Web Audio API
- **UI**: Tailwind CSS + shadcn/ui components
- **Visualization**: HTML5 Canvas

## Getting Started

### Prerequisites
- Node.js (v18 or higher)
- Modern web browser with microphone access

### Installation

1. Clone the repository:
```bash
git clone <your-repo-url>
cd audio-tones
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5000`

## Usage

1. **Grant microphone permission** when prompted
2. **Start recording** to enable voice input visualization
3. **Toggle audio tones** to play binaural beats
4. **Adjust frequency ranges** (delta, theta, alpha, beta, gamma)
5. **Monitor pattern matching** percentage in the right window
6. **Enable white noise** and adjust frequency filtering as needed

## Audio Controls

- **Binaural Beats**: Independent left/right ear frequencies for brainwave entrainment
- **Isochronic Tones**: Rhythmic pulses that can be layered with binaural beats
- **White Noise**: Broadband noise with adjustable frequency filtering
- **Volume Controls**: Independent volume adjustment for each audio component

## Pattern Matching

The voice pattern matcher analyzes your microphone input and compares it to the target audio patterns, showing a real-time percentage match. This enables voice-to-audio harmonization exercises.

## Browser Compatibility

- Chrome/Chromium (recommended)
- Firefox
- Safari (with microphone permissions)
- Edge

## License

MIT License - see LICENSE file for details