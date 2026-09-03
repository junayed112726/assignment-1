# assignment-1
first project
# problem one 
student_name = input("enter your name : ")

math = int(input("enter your marks in math : "))
english = int(input("enter your marks in english : "))
physics = int(input("enter your marks in physics : "))

total_marks = math + english + physics
percentage = (total_marks / 300) * 100

print(f"Total Marks: {total_marks}")
print(f"Percentage: {percentage}%")

if percentage >= 80 and percentage <= 100:
    print(f"Congratulations {student_name}, your grade is A+.")

elif percentage >= 70 and percentage < 80:
    print(f"Congratulations {student_name}, your grade is A.")

elif percentage >= 60 and percentage < 70:
    print(f"Congratulations {student_name}, your grade is B.")

elif percentage >= 50 and percentage < 60:
    print(f"Congratulations {student_name}, your grade is C.")

elif percentage < 50:
    print(f"Sorry {student_name}, your grade is F.")

else:
    print("Invalid input. Please enter valid marks.")

    
