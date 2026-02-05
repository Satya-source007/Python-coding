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
2. How Can We Detect Disease Accurately Using a Model?
```python
# Disease Detection Model Accuracy
diabetes_correct = 25
diabetes_total = 30

heart_correct = 35
heart_total = 45

cancer_correct = 20
cancer_total = 25

# Individual accuracies
diabetes_accuracy = (diabetes_correct / diabetes_total) * 100
heart_accuracy = (heart_correct / heart_total) * 100
cancer_accuracy = (cancer_correct / cancer_total) * 100

print(f"Diabetes detection accuracy: {diabetes_accuracy:.2f}%")
print(f"Heart disease detection accuracy: {heart_accuracy:.2f}%")
print(f"Cancer detection accuracy: {cancer_accuracy:.2f}%")

# Overall accuracy
total_correct = diabetes_correct + heart_correct + cancer_correct
total_patients = diabetes_total + heart_total + cancer_total
overall_accuracy = (total_correct / total_patients) * 100

print(f"Overall model accuracy: {overall_accuracy:.2f}%")
```
3. Fruit Sales Data Structuring (Dictionary)
```python
# Fruit Sales Data Structuring
fruit_list = ['Mango', 'Mango', 'Mango', 'Pineapple', 'Pineapple',
              'Apple', 'Mango', 'Banana', 'Apple', 'Banana',
              'Apple', 'Pineapple', 'Apple', 'Apple', 'Pineapple', 'Pineapple']

fruit_dict = {}
for fruit in fruit_list:
    if fruit in fruit_dict:
        fruit_dict[fruit] += 1
    else:
        fruit_dict[fruit] = 1

print("Fruit sales count:", fruit_dict)
```

4. Shipping Cost Calculator with Conditions
```python
# f(x) = x² + 3x - 4
def f(x):
    return x**2 + 3*x - 4

print(f(2))   # 6
print(f(0))   # -4
print(f(-1))  # -6
```
*Learning Outcomes After completing this mini-project you should be comfortable with:

 * In short: Python bridges problem and solution—automating, analyzing, structuring, ruling, and modeling the real world through code.
 * Basic arithmetic operations (+, -, *, /)
 * Calculating percentages
 * Printing formatted output
 * Understanding int, float, and simple logic
