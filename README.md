A beautifully designed calculator with a retro-inspired UI featuring a custom window interface, smooth animations, and full keyboard support.
<img width="1560" height="1096" alt="calculator (1)" src="https://github.com/user-attachments/assets/3afa4d36-5943-4738-9e1c-082840b1f25f" />
✨ Features
🎨 Design
Retro-Inspired UI: Custom window interface with pink and cream color scheme
Smooth Animations: Hover effects and button press feedback
Responsive Layout: Adapts to different screen sizes (mobile-friendly)
Custom Header: Window controls (minimize/close buttons) and branding
🔢 Functionality
Basic Arithmetic Operations: Addition (+), Subtraction (-), Multiplication (×), Division (/)
Real-time Display: Shows current input and full expression
Continuous Calculations: Chain multiple operations together
Error Handling: Prevents division by zero and invalid operations
Smart Input Reset: Automatically clears after getting a result
⌨️ Keyboard Support
Number Keys (0-9): Input numbers
Operator Keys (+, -, *, /): Perform operations
Enter/=: Calculate result
Escape/C: Clear calculator
📱 Dual Implementation
Web Version: Interactive browser-based calculator (HTML/CSS/JS)
Python Version: Command-line calculator with additional power operator (**)
🚀 Getting Started
Prerequisites
Modern web browser (Chrome, Firefox, Safari, Edge)
Python 3.x (for Python version)
Installation
Clone the repository

Simply open index.html in your web browser
Or use a local server:
# Python 3
python -m http.server 8000

# Then open http://localhost:8000
Run Python Version

python calculator.py
📂 Project Structure
day1/
├── index.html              # Main HTML structure
├── style.css              # Styling and animations
├── script.js              # Calculator logic and event handlers
├── calculator.py          # Python CLI version
├── README.md              # Documentation
└── images/
    ├── icon.png           # Logo icon
    └── rocket.png         # Calculator header icon
🎯 How to Use
Web Calculator
Click Numbers: Click on number buttons (0-9) to input values
Select Operator: Click +, -, ×, or / to choose operation
Get Result: Click "Result" button or press Enter to calculate
Continue Calculation: After a result, click an operator to continue with that result
Start Fresh: After a result, click a number to start a new calculation
Clear: Press Escape or C to clear everything
Python Calculator
Enter the first number
Enter an operator (+, -, *, /, **)

🐛 Known Issues
Division operator shows / but internally uses × for multiplication display
No decimal point functionality currently implemented
Expression display shows partial expressions during chained calculations
📝 Learning Outcomes
This project helped practice:

Event-driven programming in JavaScript
State management in vanilla JS
CSS Grid and Flexbox layouts
Responsive design principles
Error handling and edge cases
Keyboard event handling
Creating custom UI components
Enter the second number
View the result
Choose to continue or exit
