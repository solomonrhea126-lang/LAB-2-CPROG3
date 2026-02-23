print("====")
print(" PART 1: Simple Calculator")
print("====")
# Get input and convert to int
num1 = int(input("Enter the first whole number: "))
num2 = int(input("Enter the second whole number: "))
total = num1 + num2
print(f"The sum of {num1} and {num2} is: {total}\n")


print("====")
print(" PART 2: Average Calculator")
print("====")
# Get input and convert to float
val1 = float(input("Enter the first value (decimals allowed): "))
val2 = float(input("Enter the second value (decimals allowed): "))
average = (val1 + val2) / 2
print(f"The average is: {average}\n")


print("===")
print(" PART 3: Grade Evaluator")
print("====")
# Get input and evaluate
grade = float(input("Enter your final grade: "))
if grade >= 75:  # Assuming 75 is the passing mark
    print("Result: Pass")
else:
    print("Result: Fail"
