# Spectre Numbers
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)

A simple C++ command-line tool to validate international phone numbers and identify their country of origin based on E.164 standard calling codes.

##  Features

- **Input Sanitization:** Automatically removes spaces, dashes, brackets, and other unnecessary characters.
- **Format Validation:** Checks if the number is in the correct international format (`+` followed by digits) and has a valid length (10–15 digits).
- **Worldwide Country Detection:** Recognizes calling codes for almost 200 countries and territories around the world.
- **User-Friendly Output:** Displays clear, color-coded results in the terminal (green for valid, red for invalid).

##  Requirements

- A C++ compiler (e.g., `g++`, `clang++`).

##  How to Compile and Run

1. Open a terminal in the project folder.
2. Compile the program using `g++` (output file named `number`):
   ```bash
   g++ number.cpp -o number
