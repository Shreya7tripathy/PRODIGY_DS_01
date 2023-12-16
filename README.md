# PRODIGY_DS_01
Data Science Internship at Prodigy Infotech Task 01
import matplotlib.pyplot as plt

# Data for age distribution in world population
age_groups = ["0-14", "15-64", "65+"]
age_percentages = [25, 65, 10]

# bar chart
plt.figure(figsize=(5, 6))
plt.bar(age_groups, age_percentages, color=['orange', 'purple', 'red'])
plt.xlabel("Age Groups")
plt.ylabel("Percentage of Population")
plt.title("Age Distribution of a Population")
plt.xticks(rotation=45, ha='right')
plt.grid(axis='y', linestyle='--', alpha=0.7)
plt.tight_layout()

# Display the bar chart
plt.show()

# Data for gender distribution in world population
gender_labels = ["Male", "Female", "Non-binary"]
gender_percentage = [49.7, 50, 0.03]

# histogram
plt.figure(figsize=(6, 6))
plt.hist(gender_percentage, bins=3, edgecolor='black')
plt.xlabel("Gender")
plt.ylabel("Number of People")
plt.title("Gender Distribution of a Group")
plt.xticks(rotation=45, ha='right')
plt.grid(axis='y', linestyle='--', alpha=0.7)
plt.tight_layout()

# Display the histogram
plt.show()
