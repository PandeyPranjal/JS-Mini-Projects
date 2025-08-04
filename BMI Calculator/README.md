# Project: BMI Calculator 🧮

This is a **minor JavaScript project** that calculates a user's Body Mass Index (BMI) based on height and weight inputs. Built using **vanilla JavaScript** without any frameworks.

---

## 📌 Features

- Takes height (in cm) and weight (in kg) as input
- Calculates BMI using the standard formula
- Classifies BMI into:
  - Underweight
  - Normal Range
  - Overweight
- Validates input and handles errors

---

## 🔍 How It Works

```js
const bmi = weight / ((height * height) / 10000);
