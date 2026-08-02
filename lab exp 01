import numpy as np

# 1. Create the 4x4 Matrix (Rows = Students, Columns = Subjects: Math, Science, English, History)
student_scores = np.array([
    [85, 90, 78, 92],  # Student 1
    [72, 88, 85, 80],  # Student 2
    [90, 94, 88, 85],  # Student 3
    [68, 75, 82, 78]   # Student 4
])

# 2. Define subject names in the matching order
subjects = ['Math', 'Science', 'English', 'History']

# 3. Calculate the average score for each subject (axis=0 computes the mean down each column)
subject_averages = np.mean(student_scores, axis=0)

# 4. Identify the index of the subject with the highest average score
highest_avg_index = np.argmax(subject_averages)
highest_subject = subjects[highest_avg_index]
highest_avg_score = subject_averages[highest_avg_index]

# 5. Print out the raw data and analysis formatting results
print("Student Scores Matrix (4x4):")
print(student_scores)
print("\nAnalysis Results:")
for i in range(len(subjects)):
    print(f"{subjects[i]} Average Score: {subject_averages[i]:.2f}")

print(f"\nSubject with the Highest Average Score: {highest_subject} ({highest_avg_score:.2f})")
