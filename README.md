# assignment-1
first project
# problem one Student Grade Calculator
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


# problem -2
# simple shopping cart
customer_name = input("Enter your name: ")

product1 = input("Enter the name of product 1: ")
price1 = float(input(f"Enter the price of {product1}: "))

product2 = input("Enter the name of product 2: ")
price2 = float(input(f"Enter the price of {product2}: "))

product3 = input("Enter the name of product 3: ")
price3 = float(input(f"Enter the price of {product3}: "))

total_price = price1 + price2 + price3
print(f"Total price: {total_price}")

if total_price >= 5000:
    discount = total_price *0.2
    print(f"congratulations {customer_name},you got 20% discount = {discount}")
elif total_price < 5000 and total_price >= 3000:
    discount = total_price *0.1
    print(f"congratulations {customer_name},you got 10% discount = {discount}")
elif total_price < 3000 and total_price >= 1000:
    discount = total_price *0.05
    print(f"congratulations {customer_name},you got 5% discount = {discount}")
else:
    print("sorry to say , you are not eligible for any discount")

new_total = total_price - discount
print(f"your final price after discount is : {new_total}")

