# Calculator Project

## 📌 Project Description
This project is a simple calculator built using:
- **HTML** for the structure (screen + buttons).
- **CSS** for styling and layout.
- **JavaScript** for the logic and calculations.

---

## ⚙️ How the Application Works

### 1. Display Screen
- Implemented with an `<input>` element.
- Shows the numbers and operations entered by the user.

### 2. Buttons
- Each button is connected to a JavaScript function:
  - `appendValue(value)` → adds the number or operator to the display.
  - `clearDisplay()` → clears the display.
  - `calculate()` → evaluates the expression and shows the result.

### 3. Calculation Logic
- `appendValue` uses `+=` to concatenate the new input to the existing text in the display.
- `calculate` uses `eval()` to interpret the string (e.g., `"7+3"`) as a real calculation and return the result.
- If the input is invalid, the display shows `"Error"`.

---

## 🧩 Example Usage
1. User presses "7" → display shows `7`.
2. User presses "+" → display shows `7+`.
3. User presses "3" → display shows `7+3`.
4. User presses "=" → result displayed is `10`.

---

## 🚀 How to Run
1. Open the file `index.html` in any modern browser.
2. Use the buttons to perform calculations.

---
