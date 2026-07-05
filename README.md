# 🍽️ Weekly Canteen Meal Plan Generator (Python + Tkinter + CSP)

## 📌 Project Overview

The **Weekly Canteen Meal Plan Generator** is a Python desktop application that automatically creates a **7-day meal schedule** for a canteen using **Constraint Satisfaction Problem (CSP)** techniques. The application helps users generate a balanced weekly meal plan based on their **diet preference** and **weekly budget** while satisfying predefined constraints.

This project demonstrates the practical implementation of **Artificial Intelligence (AI)** concepts, specifically **Backtracking Search**, along with Python GUI development using **Tkinter**.

---

## ✨ Features

* Generate a complete **7-day meal plan**
* Select dietary preference:

  * Any
  * Vegetarian
  * Non-Vegetarian
* Enter a weekly budget
* Automatic meal selection using CSP Backtracking
* User-friendly graphical interface built with Tkinter
* Displays:

  * Day
  * Meal Name
  * Category
  * Cost
  * Calories
* Calculates the total weekly cost
* Shows an error message if no valid solution exists

---

## 🧠 AI Concept Used

This project is based on the **Constraint Satisfaction Problem (CSP)** model.

The meal planner uses the **Backtracking Search Algorithm** to assign meals for each day while satisfying all constraints.

### Constraints Implemented

* No meal is repeated during the week (**AllDifferent Constraint**)
* Total meal cost must remain within the user's weekly budget
* Consecutive days cannot have meals from the same category (Veg/Non-Veg)
* Meals must match the user's selected diet preference

If a meal violates any constraint, the algorithm **backtracks** and searches for another valid assignment until a complete solution is found.

---

## 🛠️ Technologies Used

* python 3
* Tkinter (GUI)
* Object-Oriented Programming (OOP)
* Constraint Satisfaction Problem (CSP)
* Backtracking Algorithm

---

## 📂 Project Structure

* **Meal Class** – Stores meal information such as name, category, cost, and calories.
* **Menu Dataset** – Contains all available meal options.
* **CSP Solver** – Uses recursive backtracking to generate a valid weekly meal plan.
* **GUI Module** – Allows users to interact with the application through an intuitive interface.

---

## 🚀 How to Run

1. Clone this repository.
2. Make sure Python 3 is installed.
3. Run the project:

```bash
python meal_planner.py
```

4. Select your diet preference.
5. Enter your weekly budget.
6. Click **Generate Meal Plan**.

---

## 🎯 Learning Outcomes

This project demonstrates:

* Artificial Intelligence using Constraint Satisfaction Problems (CSP)
* Backtracking Search Algorithm
* Recursive programming
* Object-Oriented Programming in Python
* GUI development with Tkinter
* Input validation and event-driven programming

---

## 📌 Future Improvements

* Export meal plans to PDF or Excel
* Add breakfast, lunch, and dinner planning
* Store meals in a database
* Include nutritional recommendations
* Add calorie and protein goals
* Support custom meal entries
* Improve UI with themes and icons

---

## 👩‍💻 Author

**Urooj Fatima**

Developed as a Python project to demonstrate the practical implementation of **Artificial Intelligence (Constraint Satisfaction Problems)**, **Backtracking Algorithms**, and **Tkinter GUI Development**.
