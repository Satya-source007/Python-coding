# Introduction to Python Programming - Capstone Project 1

Simple beginner Python exercises focusing on variables, basic arithmetic, percentages, and data types using real-world scenarios.

## What You'll Find Here

- Calculating cricket team points (scoreboard operator problem)
- Computing ingredient percentages in a nutrition bar
- Evaluating accuracy of a simple disease detection model
- Introduction to Python data types (int, float, boolean)
- Solving basic algebra expressions with Python

Perfect first project for anyone starting with Python!

## Project Highlights

### 1. Score Board Operator (Cricket Tournament)

Team London played 8 matches:  
- Won 4 → 3 points each  
- Drew 1 → 1 point  
- Lost 3 → 0 points  

**Result:** 13 points

```python
points_per_win = 3
points_per_draw = 1
points_per_loss = 0

wins = 4
draws = 1
losses = 3

total_points = (wins * points_per_win) + (draws * points_per_draw) + (losses * points_per_loss)
print("Total points earned by Team London:", total_points)   # 13
```
2. Nutrition Bar Ingredient Percentages
Nutrition bar contains:
```python
raisins = 45
almonds = 65
apricots = 30

total_weight = raisins + almonds + apricots

perc_raisins  = (raisins  / total_weight) * 100
perc_almonds  = (almonds  / total_weight) * 100
perc_apricots = (apricots / total_weight) * 100

print(f"Raisins:  {perc_raisins:.2f}%")   # ~32.14%
print(f"Almonds:  {perc_almonds:.2f}%")   # ~46.43%
print(f"Apricots: {perc_apricots:.2f}%")  # ~21.43%
```
3.Disease Model Accuracy
```python
# Patients and correct detections
diabetes_patients = 30
correct_diabetes = 25

heart_disease_patients = 45
correct_heart_disease = 35

cancer_patients = 25
correct_cancer = 20

# Total
total_patients = diabetes_patients + heart_disease_patients + cancer_patients
total_correct = correct_diabetes + correct_heart_disease + correct_cancer

# Overall accuracy
accuracy = (total_correct / total_patients) * 100
print(f"Model accuracy: {accuracy:.2f}%")  # Output: 80.00%
```

4. Basic Algebra in Python
```python
# f(x) = x² + 3x - 4
def f(x):
    return x**2 + 3*x - 4

print(f(2))   # 6
print(f(0))   # -4
print(f(-1))  # -6
```
*Learning Outcomes After completing this mini-project you should be comfortable with:

 * Creating and using variables
 * Basic arithmetic operations (+, -, *, /)
 * Calculating percentages
 * Printing formatted output
 * Understanding int, float, and simple logic
