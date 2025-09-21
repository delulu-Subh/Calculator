# 🧮 All-in-One Python Calculator

A mobile-style, swipe-enabled calculator built using Python Tkinter, designed to function like the modern calculator app on PCs or smartphones. It includes Standard, Scientific, and Unit Converter modes, along with memory functions, history panel, dark/light theme, and smooth swipe animations between tabs.

Features
1. Standard Calculator

Basic arithmetic: +, -, *, /, ., =

Clear button C

Memory operations: MC, MR, M+, M-

2. Scientific Calculator

Trigonometric functions: sin, cos, tan, asin, acos, atan

Logarithms: log (base 10), ln (natural)

Exponentials: exp, pow

Square root: sqrt

Factorial: fact

Constants: pi, e

3. Unit Converter

Length: km ↔ m

Weight: kg ↔ g

Temperature: C ↔ F

4. User Interface

Swipe-enabled tabs: Standard, Scientific, Converter

Gradient circular buttons

Floating, scrollable history panel

Dark/Light theme toggle

Fully resizable and responsive layout

Keyboard input support

Installation & Setup

Make sure Python 3.x is installed.

Tkinter must be available (usually comes pre-installed with Python).

If not, install via:

pip install tk


Run the calculator in Jupyter Notebook:

%gui tk
# Paste the calculator code here


Or run as a standalone .py script:

python calculator.py

Usage

Launch the calculator.

Use swipe tabs or click buttons to switch between Standard, Scientific, and Converter modes.

Perform calculations using buttons or keyboard.

Use memory buttons for storing/retrieving numbers.

Check your previous calculations in the history panel.

Toggle dark/light theme using the theme button (if implemented).

Screenshots

(Add screenshots of your calculator in different modes for GitHub)

Notes

Swipe animations and canvas-based buttons work best on desktop Python, slightly slower in Jupyter Notebook.

The layout is resizable, but for best display use ~500×750 px window size.

Supports up to 50 history items.

Future Improvements

Add hover shadow effects on buttons for a modern mobile feel.

Add more scientific functions (hyperbolic, mod, factorial with error handling).

Add currency and more unit conversions.

Smooth swipe animations optimized for Jupyter Notebook.
