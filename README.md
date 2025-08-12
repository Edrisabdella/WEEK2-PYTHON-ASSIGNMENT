# WEEK2-PYTHON-ASSIGNMENT
python second week assignment
# --------------------------------------------
# WEEK 2 PYTHON ASSIGNMENT
# Author: Edris Abdella
# Description:
# This program demonstrates Python list operations such as
# appending, inserting, extending, removing, sorting, and
# finding an element's index.
# --------------------------------------------

# 1. Create an empty list called my_list
my_list = []
print("Step 1 - Empty list created:", my_list)

# 2. Append the following elements to my_list: 10, 20, 30, 40
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)
print("Step 2 - After appending 10, 20, 30, 40:", my_list)

# 3. Insert the value 15 at the second position in the list (index 1)
my_list.insert(1, 15)
print("Step 3 - After inserting 15 at second position:", my_list)

# 4. Extend my_list with another list: [50, 60, 70]
my_list.extend([50, 60, 70])
print("Step 4 - After extending with [50, 60, 70]:", my_list)

# 5. Remove the last element from my_list
removed_element = my_list.pop()  # pop() removes and returns the last element
print(f"Step 5 - After removing last element ({removed_element}):", my_list)

# 6. Sort my_list in ascending order
my_list.sort()
print("Step 6 - After sorting in ascending order:", my_list)

# 7. Find and print the index of the value 30 in my_list
if 30 in my_list:
	index_of_30 = my_list.index(30)  # index() returns the position of the element
	print(f"Step 7 - The index of value 30 is: {index_of_30}")
else:
	print("Step 7 - The value 30 is not in the list.")

# Final confirmation of list
print("Final my_list contents:", my_list)

