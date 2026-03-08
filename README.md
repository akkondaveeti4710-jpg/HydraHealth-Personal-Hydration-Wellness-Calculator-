# HydraHealth: Personal Hydration & Wellness Calculator 💧

## Overview

**HydraHealth** is a simple Python-based health assistant that helps users understand basic wellness metrics using personal data. By entering information such as age, height, weight, activity level, and daily water intake, the program calculates key health indicators and generates personalized recommendations.

The goal of this project is to make health awareness more accessible by providing quick insights about hydration, body composition, and daily energy needs.

This project was designed as a hackathon prototype to demonstrate how simple data analysis can help individuals better understand their daily health habits.

---

## Features

* Calculates **BMI (Body Mass Index)** to assess body weight category
* Estimates **recommended daily water intake** based on body weight and activity level
* Evaluates hydration status and dehydration risk
* Estimates **daily calorie needs** using a basal metabolic rate formula
* Provides **personalized health advice** based on results
* Option to **save a health report** as a text file

---

## How It Works

The program asks users to input:

* Name
* Age
* Gender
* Height
* Weight
* Activity level
* Daily water intake

Using this information, the system calculates:

1. **BMI**
2. **Recommended hydration level**
3. **Hydration risk status**
4. **Estimated daily calories**
5. **Health suggestions**

The program then displays a formatted health report and allows the user to save it locally.

---

## Project Structure

```
health_hackathon_project
│
├── main.py
├── bmi_calculator.py
├── hydration_calculator.py
├── calorie_calculator.py
├── health_advice.py
└── report_generator.py
```

### File Descriptions

**main.py**
Controls the user interface and connects all modules together.

**bmi_calculator.py**
Calculates BMI and determines the BMI category.

**hydration_calculator.py**
Calculates recommended water intake and hydration risk.

**calorie_calculator.py**
Estimates daily calorie needs based on user data.

**health_advice.py**
Generates personalized health recommendations.

**report_generator.py**
Saves the user's health report to a text file.

---

## Requirements

* Python 3.8 or later
* A Python IDE such as **PyCharm**

No external libraries are required.

---

## How to Run

1. Open the project folder in **PyCharm**.
2. Make sure all Python files are inside the same project directory.
3. Run the file:

```
main.py
```

4. Enter your health information when prompted.
5. View your generated health report.

---

## Example Output

```
----- HEALTH REPORT -----

Name: Alex
Age: 18

BMI: 22.6
BMI Category: Normal weight

Recommended Water Intake: 2.4 L
Your Water Intake: 1.5 L
Hydration Status: Moderate dehydration risk

Estimated Daily Calories: 2200

Health Advice:
- Drink more water throughout the day.
- Aim for at least 7–9 hours of sleep per night.
- Regular physical activity improves overall health.
```

---

## Disclaimer

This project is intended for educational and demonstration purposes only. It does **not** replace professional medical advice, diagnosis, or treatment.

---

## Future Improvements

Possible upgrades for future versions include:

* Graphical user interface (GUI)
* Data visualization for hydration trends
* Integration with wearable health devices
* Personalized nutrition suggestions
* Expanded health risk analysis

---

## Author

Developed as a health technology hackathon project exploring how simple computational tools can support personal wellness awareness.
