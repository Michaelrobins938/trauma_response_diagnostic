# 🚀 Trauma Response Diagnostic Tool - Cyberpunk Edition

An interactive, immersive trauma response diagnostic tool with a dark cyberpunk aesthetic. This tool helps users identify their primary trauma response pattern (Fight, Flight, Freeze, or Fawn) through a series of humorous, relatable questions.

## ✨ Features

### 🎨 Visual Design
- **Cyberpunk Aesthetic**: Dark theme with neon accents and glitch effects
- **Dynamic Animations**: Floating particles, glitch overlays, and smooth transitions
- **Interactive Elements**: Hover effects, click animations, and visual feedback
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices

### 🔊 Audio Experience
- **Web Audio API**: Dynamic sound effects for interactions
- **Immersive Feedback**: Click sounds, progress tones, and result celebrations
- **Optional Audio**: Respects user preferences and browser settings

### 🧠 Enhanced Functionality
- **9 Thoughtful Questions**: Expanded from original 6 questions
- **Smart Scoring**: Advanced algorithm for accurate trauma response detection
- **Result Persistence**: localStorage integration for result tracking
- **Share Functionality**: Social media integration and clipboard sharing
- **Accessibility**: Full keyboard navigation and screen reader support

### 🎯 User Experience
- **Smooth Transitions**: CSS3 animations with cubic-bezier easing
- **Loading States**: Visual feedback during interactions
- **Progress Tracking**: Animated progress bar with gradient effects
- **Result Animations**: 3D reveal effects for results

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required

### Installation
1. Clone or download this repository
2. Open `index.html` in your web browser
3. Start the diagnostic!

### Usage
1. Click "Start Diagnostic" to begin
2. Answer each question honestly
3. View your personalized trauma response result
4. Share your result or restart the quiz

## 🛠️ Technical Details

### Technologies Used
- **HTML5**: Semantic markup and modern features
- **CSS3**: Advanced animations, gradients, and effects
- **Vanilla JavaScript**: No frameworks, pure performance
- **Web Audio API**: Dynamic sound generation
- **localStorage**: Client-side data persistence

### Browser Support
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 📱 Mobile Optimization

The tool is fully responsive and optimized for mobile devices:
- Touch-friendly interface
- Optimized animations for mobile performance
- Responsive typography and spacing
- Mobile-specific hover states

## 🎨 Customization

### Color Scheme
The tool uses CSS custom properties for easy theming:
```css
:root {
    --fight-color: #ff073a;
    --flight-color: #00f5ff;
    --freeze-color: #7209b7;
    --fawn-color: #f1c40f;
    --accent-toxic: #39ff14;
    /* ... more variables */
}
```

### Adding Questions
Questions are defined in the HTML with the following structure:
```html
<div class="question-container" data-question="X">
    <div class="question">Your question here? 🤔</div>
    <div class="options">
        <div class="option" data-response="response-type">Answer option</div>
        <!-- ... more options -->
    </div>
</div>
```

## 🔧 Development

### File Structure
```
trauma-response-diagnostic/
├── index.html          # Main application file
├── README.md           # Project documentation
└── .gitignore          # Git ignore rules
```

### Key Functions
- `initializeApp()`: Initializes the application
- `nextQuestion()`: Handles question progression
- `showResult()`: Displays final results
- `shareResult()`: Handles result sharing
- `playSound()`: Generates audio feedback

## 📊 Analytics & Privacy

- **No Data Collection**: All data stays in your browser
- **localStorage Only**: Results stored locally for your convenience
- **No External Requests**: Completely client-side operation
- **Privacy First**: No tracking or analytics

## 🤝 Contributing

This is a personal project, but suggestions and improvements are welcome! Feel free to:
- Report bugs or issues
- Suggest new questions or features
- Improve accessibility
- Enhance the visual design

## 📄 License

This project is open source and available under the MIT License.

## 🎯 About the Author

Created as part of a book project about ADHD and mental health, this tool provides an engaging way to explore trauma responses through interactive technology.

---

**⚠️ Disclaimer**: This tool is for entertainment and self-reflection purposes only. It is not a substitute for professional mental health care or diagnosis.
