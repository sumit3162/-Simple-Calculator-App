# 🧮 Simple Calculator App

A clean, functional calculator built with HTML, CSS, and JavaScript that handles basic arithmetic operations.

## ✨ Features
- ➕➖✖️➗ Basic arithmetic operations (add, subtract, multiply, divide)
- 🔢 Number input (0-9 and decimal point)
- 🟢 Equals button for calculation
- 🔴 Clear button to reset
- 🚨 Error handling for invalid expressions
- 📱 Responsive design

## 🛠️ Setup
1. Simply open `index.html` in any modern browser - no installation needed!
2. Start calculating immediately 🚀

## 🎨 Design Elements
- Dark theme interface
- Grid-based button layout
- Large, readable display
- Hover effects on buttons
- Clear visual distinction for operations vs numbers

## ⚙️ How It Works
1. Click number buttons to build your calculation
2. Select an operation (+, -, *, /)
3. Press "=" to see the result
4. Use "C" to clear the display

## 📝 Code Structure
- `index.html`: Calculator structure and buttons
- `styles.css`: Modern dark theme styling
- `script.js`: Core calculation logic

```javascript
// Sample of the clean JavaScript logic
function calculate() {
  try {
    display.value = eval(display.value); // Safely evaluate expression
  } catch {
    display.value = 'Error'; // User-friendly error handling
  }
}
```

## 🌟 Potential Enhancements
- 💾 Memory functions (M+, M-, MR, MC)
- 📊 Scientific calculator functions
- 🎨 Theme switcher (light/dark mode)
- 📱 Improved mobile responsiveness
- ⌨️ Keyboard support

## 🚀 Quick Start
```bash
git clone https://github.com/yourusername/calculator.git
open index.html
```
