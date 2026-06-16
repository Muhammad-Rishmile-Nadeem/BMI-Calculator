# 🌐 Dynamic BMI Calculator Web App

A clean, modern, and light-weight single-page web application that computes **Body Mass Index (BMI)** dynamically based on user height (in feet) and weight (in kg). Built completely using semantic HTML, vanilla CSS, and event-driven JavaScript logic.

---

## 🚀 Key Features Built In

*   **Smart Metric Conversion:** Accepts height input in standard feet and automatically converts it internally to meters for standard BMI metric calculations.
*   **Dynamic DOM Manipulation:** Calculates results seamlessly instantly upon hitting the 'CALCULATE' button without any page reloads.
*   **Color-Coded Status Feedback:** Employs dynamic CSS inline style updates to color-code text status feedback based on user results (e.g., green for normal weight, red for high risk categories).
*   **Input Precision Handling:** Formats the final BMI decimal outputs up to exactly 2 decimal places using JavaScript's `.toFixed(2)` method.

---

## 🛠️ Project Architecture & Technologies

*   **Structure:** Semantic `HTML5` text layout wrappers.
*   **Styling:** Native `CSS3` focusing on centered margins, explicit box shadows, hover state transitions (`:focus`), and customized typography.
*   **Logic Engine:** Functional JavaScript (`ES6`) utilizing variables block sizing (`let`), data casting via `parseFloat()`, and conditional decision trees (`if-else` matrices).

---

## 🧮 Mathematical Engine Logic

The script converts user inputs and applies the metric Body Mass Index formula under the hood:

1. **Height Conversion:**
   $$Height_{(meters)} = Height_{(feet)} \times 0.3048$$

2. **BMI Calculation:**
   $$BMI = \frac{Weight_{(kg)}}{Height_{(meters)}^2}$$

### Dynamic Style Thresholds Triggered:

| Calculated BMI Score | Display Category Label | Visual Color Output |
| :--- | :--- | :--- |
| **Less than 18.5** | UNDERWEIGHT | Light Green 🟢 |
| **18.5 – 24.9** | NORMAL | Dark Green 🟢 |
| **25.0 – 29.9** | OVERWEIGHT | Yellow 🟡 |
| **30.0 – 34.9** | OBESE | Orange 🟠 |
| **35.0 or Higher** | EXTREMELY OBESE | Red 🔴 |

---

## 📸 Local Workspace Preview
