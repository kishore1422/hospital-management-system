# Hospital Management System

A simple Hospital Management System project built using C++ compiled to WebAssembly (WASM) along with HTML, CSS, and JavaScript. This project demonstrates running C++ logic directly in the browser using WebAssembly.

## Features

- Core logic implemented in C++
- Compiled to WebAssembly (WASM)
- Web-based user interface
- Runs fully on the client side
- No backend or database required

## Project Structure

hospital-management-system/
- index.html
- styles.css
- script.js
- hms.cpp
- hms.js
- hms.wasm

## How to Run

1. Clone the repository  
   git clone https://github.com/kishore1422/hospital-management-system.git

2. Open the project folder

3. Open index.html in a web browser

## Rebuilding WebAssembly (Optional)

1. Install Emscripten SDK  
2. Compile the C++ file  
   emcc hms.cpp -o hms.js -s WASM=1 -O3

This will generate hms.js and hms.wasm files.

## Purpose

This project is created for learning and demonstration of:
- Hospital management system basics
- WebAssembly
- C++ integration with web technologies

## Author

Nanda Kishore  
GitHub: https://github.com/kishore1422

## License

This project is open for educational and personal use.