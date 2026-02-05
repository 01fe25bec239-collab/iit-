#s1
birth_year_input = input("Enter your birth year: ")
birth_year = int(birth_year_input)
current_year = 2026
age = current_year - birth_year
print(f"You are {age} years old.")

#s2
user_input = input("Enter the model accuracy: ")
if user_input.replace('.', '', 1).isdigit():
    accuracy = float(user_input)
else:
    print("Invalid input. Please enter a numeric value.")

#s3
name = input("Enter your name: ")
age_input = input("Enter your age: ")
age = int(age_input)
status_input = input("Are you an active user? (True/False): ")
is_active = status_input.strip().capitalize() == "True"
print(f"User {name} is {age} years old. Active status: {is_active}")
