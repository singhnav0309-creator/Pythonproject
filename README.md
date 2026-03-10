                                          HOW TO RUN?

#TASK_1
""" Create a Dictionary of Student Marks """

# Create a Dictionary that includes student names as keys and marks are value.
Students = {'Alice': 85, 'Elly': 60, 'Navi': 90}

# User give a input for student's name
name = (input("Enter the student's name: "))

# retrieves and displays the corresponding marks.
if name in Students: 
    # prints the student name with marks
    print(f"{name}'s marks: {Students[name]} ")

# if student does not exist in Dictionary.
else:
    # prints if student name is not found
    print("Student not found.")

    For Example, if we enter Elly as user input
    it shows (Enter the student's name: Elly)
    (Elly's marks: 60)

    If we enter another name which is not includes in Dictionary.
    For Example, John
    it shows (Student not found.)




#TASK_2
 """ Demonstrate List Slicing """

# Create a list of numbers from 1 to 10.
numbers = list(range(1, 11))

# prints original list
print(f"original list: {numbers}")

# Extracts the first five elements
first_five = numbers[:5]

# prints extracts first five elements
print(f"Extracted first five elements: {first_five}")

# Reverses the first five elements
reversed_list = first_five[::-1]

# prints reversed list elements
print(f"Reversed extracted elements: {reversed_list}")

For Example, original list = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
Extracted first five elements = [1, 2, 3, 4, 5]
Reversed extracted elements = [5, 4, 3, 2, 1]


