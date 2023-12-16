# PRODIGY_DS_01
Data Science Internship at Prodigy Infotech Task 01
import matplotlib.pyplot as plt

# Example data for age distribution
age_groups = ["0-17", "18-24", "25-34", "35-44", "45-54", "55-64", "65+"]
age_percentages = [20, 15, 22, 18, 12, 10, 3]

# Create a bar chart
plt.figure(figsize=(8, 6))
plt.bar(age_groups, age_percentages, color=['skyblue', 'lightgreen', 'orange', 'purple', 'gold', 'red', 'gray'])
plt.xlabel("Age Groups")
plt.ylabel("Percentage of Population")
plt.title("Age Distribution of a Population")
plt.xticks(rotation=45, ha='right')
plt.grid(axis='y', linestyle='--', alpha=0.7)
plt.tight_layout()

# Display the bar chart
plt.show()

# Example data for gender distribution
gender_labels = ["Male", "Female", "Non-binary"]
gender_counts = [600, 400, 50]

# Create a histogram
plt.figure(figsize=(6, 6))
plt.hist(gender_labels, bins=3, edgecolor='black')
plt.xlabel("Gender")
plt.ylabel("Number of People")
plt.title("Gender Distribution of a Group")
plt.xticks(rotation=45, ha='right')
plt.grid(axis='y', linestyle='--', alpha=0.7)
plt.tight_layout()

# Display the histogram
plt.show()
