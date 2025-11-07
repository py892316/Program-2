# Program to calculate total marks, percentage, and grade

# Taking marks of 5 subjects
m1 = float(input("Enter marks of Subject 1: "))
m2 = float(input("Enter marks of Subject 2: "))
m3 = float(input("Enter marks of Subject 3: "))
m4 = float(input("Enter marks of Subject 4: "))
m5 = float(input("Enter marks of Subject 5: "))

# Calculate total and percentage
total = m1 + m2 + m3 + m4 + m5
percentage = (total / 500) * 100  # Assuming each subject is 100 marks

# Calculate grade
if percentage >= 90:
    grade = "A"
elif percentage >= 75:
    grade = "B"
elif percentage >= 60:
    grade = "C"
elif percentage >= 40:
    grade = "D"
else:
    grade = "F"

# Output results
print("Total Marks:", total)
print("Percentage:", percentage)
print("Grade:", grade)# Program-2
