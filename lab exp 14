import pandas as pd
import matplotlib.pyplot as plt

# Read CSV file
data = pd.read_csv("student_data.csv")

print("Student Data")
print(data)

# Calculate correlation
correlation = data["StudyTime"].corr(data["ExamScore"])

print("\nCorrelation Coefficient =", correlation)

# Scatter Plot
plt.figure(figsize=(6,4))
plt.scatter(data["StudyTime"], data["ExamScore"], marker='o')
plt.title("Study Time vs Exam Score (Scatter Plot)")
plt.xlabel("Study Time (Hours)")
plt.ylabel("Exam Score")
plt.grid(True)
plt.show()

# Line Plot
plt.figure(figsize=(6,4))
plt.plot(data["StudyTime"], data["ExamScore"], marker='o')
plt.title("Study Time vs Exam Score (Line Plot)")
plt.xlabel("Study Time (Hours)")
plt.ylabel("Exam Score")
plt.grid(True)
plt.show()
