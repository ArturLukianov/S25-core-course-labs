# Moscow Time Display 🕰️

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
![Flask Version](https://img.shields.io/badge/flask-3.1.0-lightgrey)

A production-ready web application displaying current Moscow time with retro pixel styling and automatic refresh.

![Moscow Time Screenshot](screenshot.png) *Replace with actual screenshot*

## Features ✨

- 🌑 Dark theme with retro CRT aesthetic
- 🖥️ Pixel-styled display using VT323 font
- ⚡ Real-time updates (1-second refresh)
- 🌍 Timezone-aware calculations (pytz)
- 📈 Production-ready configuration
- 📊 Comprehensive logging
- 🛡️ Error handling with graceful degradation
- 📱 Responsive design

## Installation 💻

### Prerequisites
- Python 3.9+
- pip 23.0+

### Quick Start
```bash
# Clone repository
git clone https://github.com/yourusername/moscow-time-app.git
cd moscow-time-app

# Install dependencies
pip install -r requirements.txt

# Run application
python app.py
