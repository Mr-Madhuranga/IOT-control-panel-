# 🏠 Smart Home Control Panel

A modern, responsive web-based smart home control interface with a sleek dark theme and interactive elements. Built with vanilla HTML, CSS, and JavaScript.

![Smart Home Control Panel](https://img.shields.io/badge/Status-Active-brightgreen) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## ✨ Features

### 🎛️ **Device Management**
- Interactive device cards with real-time status updates
- Toggle devices on/off with visual feedback
- Support for multiple device types (lights, thermostat, TV, security, etc.)
- Animated hover effects and state transitions

### 🏠 **Quick Actions**
- Pre-configured scene modes:
  - 🌙 Good Night Mode
  - 🚗 Away Mode
  - 🎉 Party Mode
  - 🎬 Movie Mode
  - 🔋 Energy Saver Mode

### 🌡️ **Climate Control**
- Temperature and humidity sliders
- Real-time value updates
- Auto mode toggle
- Smooth slider animations with custom styling

### 💡 **Lighting Control**
- Brightness adjustment
- Color temperature control (Warm/Natural/Cool)
- Schedule mode toggle
- Gradient-styled custom sliders

### 🛡️ **Security Dashboard**
- Real-time security status monitoring
- Door/window status indicators
- Camera feed status
- Alarm system controls

### ⚡ **Energy Monitoring**
- Current power usage display
- Monthly cost tracking
- Usage comparison with previous month
- Animated weekly usage chart

### 🎵 **Media Controls**
- Floating music player widget
- Play/pause, next/previous controls
- Currently playing track display

### 🔔 **Smart Notifications**
- Real-time system notifications
- Animated slide-in effects
- Auto-dismiss functionality
- Random system updates simulation

## 🚀 Demo

[Live Demo](your-demo-url-here) | [Screenshots](#screenshots)

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/smart-home-control-panel.git
   cd smart-home-control-panel
   ```

2. **Open in browser**
   ```bash
   # Simply open the HTML file in your preferred browser
   open smart_home_control.html
   # or
   python -m http.server 8000  # For local server
   ```

3. **That's it!** No build process or dependencies required.

## 🎨 Design Features

- **Modern Glassmorphism UI** with backdrop blur effects
- **Responsive Design** - works on desktop, tablet, and mobile
- **Dark Theme** with gradient accents and smooth animations
- **Interactive Elements** with hover effects and state changes
- **Custom Sliders** with gradient styling
- **Animated Charts** for energy usage visualization

## 📱 Responsive Design

The interface automatically adapts to different screen sizes:
- **Desktop**: Full grid layout with sidebar
- **Tablet**: Adjusted grid columns
- **Mobile**: Single column layout with optimized touch targets

## 🎯 Usage

### Adding New Devices
1. Add a new device card in the `devices-grid` section
2. Include appropriate emoji icon and device name
3. Add toggle functionality in the `toggleDevice()` function

### Customizing Quick Actions
1. Modify the `executeAction()` function
2. Add new action buttons in the quick actions section
3. Define custom notification messages

### Styling Customization
- **Colors**: Modify CSS custom properties for theme colors
- **Animations**: Adjust transition durations and easing functions
- **Layout**: Change grid configurations for different layouts

## 🔧 Technical Details

### Technologies Used
- **HTML5** - Semantic markup
- **CSS3** - Modern styling with flexbox/grid, animations, and glassmorphism
- **Vanilla JavaScript** - Interactive functionality and DOM manipulation

### Key Features Implementation
- **Glassmorphism Effect**: `backdrop-filter: blur(20px)` with semi-transparent backgrounds
- **Custom Sliders**: Styled using `::-webkit-slider-thumb` and `::-moz-range-thumb`
- **Animations**: CSS keyframes for smooth transitions and loading effects
- **Responsive Grid**: CSS Grid with `auto-fit` and `minmax()` for flexible layouts

### Browser Support
- Chrome/Edge 88+
- Firefox 87+
- Safari 14+
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📊 Performance

- **Lightweight**: No external dependencies
- **Fast Loading**: Optimized CSS and minimal JavaScript
- **Smooth Animations**: Hardware-accelerated CSS transitions
- **Memory Efficient**: Event delegation and cleanup
