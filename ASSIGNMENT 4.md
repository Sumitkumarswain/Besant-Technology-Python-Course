Create a list named myList with the elements: 10, 20, 30, 'apple', True, 8.10.

a. Append values 30 and 40 to myList.
b. Reverse the elements of myList and store them in reversedList.

# Step 1: Create the initial list
myList = [10, 20, 30, 'apple', True, 8.10]

# Step 2: Append 30 and 40
myList.append(30)
myList.append(40)

# Step 3: Reverse the list and store in reversedList
reversedList = myList[::-1]

# Output the result
print("myList:", myList)
print("reversedList:", reversedList)

# OUTPUT
myList: [10, 20, 30, 'apple', True, 8.1, 30, 40]
reversedList: [40, 30, 8.1, True, 'apple', 30, 20, 10]


2. 
Create a dictionary with key-value pairs:

Keys: 1, 2, 3

Values: 'data', 'information', 'text'

a. Eliminate the 'text' value from the dictionary
b. Add 'features' to the dictionary
c. Fetch and display the 'data' element from the dictionary


# ANSWER
# Step 1: Create the dictionary
myDict = {1: 'data', 2: 'information', 3: 'text'}

# Step 2: Eliminate the 'text' value (key 3)
myDict.pop(3)

# Step 3: Add 'features' to the dictionary (let's assume key 4)
myDict[4] = 'features'

# Step 4: Fetch and display the 'data' element
data_element = myDict[1]

# Output the results
print("Updated Dictionary:", myDict)
print("Fetched element:", data_element)

Updated Dictionary: {1: 'data', 2: 'information', 4: 'features'}
Fetched element: data

3.
# Creating the tuple
my_tuple = (1, 2, 3, 'apple', 'mango')

# Output the result
print("my_tuple:", my_tuple)

# OUTPUT -
my_tuple: (1, 2, 3, 'apple', 'mango')

4.

Create a tuple named numeric_tuple with values: 10, 20, 30, 40, 50.

a. Find the minimum value from numeric_tuple
b. Concatenate my_tuple (from earlier) with numeric_tuple and store it in r1
c. Duplicate my_tuple 2 times and store it in newdupli

# Step 1: Existing tuple
my_tuple = (1, 2, 3, 'apple', 'mango')

# Step 2: Create numeric_tuple
numeric_tuple = (10, 20, 30, 40, 50)

# a. Find minimum value
min_value = min(numeric_tuple)

# b. Concatenate my_tuple and numeric_tuple
r1 = my_tuple + numeric_tuple

# c. Duplicate my_tuple 2 times
newdupli = my_tuple * 2

# Output results
print("Minimum value from numeric_tuple:", min_value)
print("Concatenated tuple (r1):", r1)
print("Duplicated my_tuple (newdupli):", newdupli)

# OUTPUT
Minimum value from numeric_tuple: 10  
Concatenated tuple (r1): (1, 2, 3, 'apple', 'mango', 10, 20, 30, 40, 50)  
Duplicated my_tuple (newdupli): (1, 2, 3, 'apple', 'mango', 1, 2, 3, 'apple', 'mango')

5.
Create two sets:

set1 = {1, 2, 3, 4, 5}

set2 = {2, 3, 7, 6, 1}

Perform the following operations:

a. set1 union set2
b. set1 intersection set2
c. set1 difference set2

# Step 1: Create sets
set1 = {1, 2, 3, 4, 5}
set2 = {2, 3, 7, 6, 1}

# a. Union of set1 and set2
union_result = set1.union(set2)

# b. Intersection of set1 and set2
intersection_result = set1.intersection(set2)

# c. Difference of set1 and set2 (elements in set1 but not in set2)
difference_result = set1.difference(set2)

# Output results
print("Union:", union_result)
print("Intersection:", intersection_result)
print("Difference (set1 - set2):", difference_result)

# OUTPUT
Union: {1, 2, 3, 4, 5, 6, 7}  
Intersection: {1, 2, 3}  
Difference (set1 - set2): {4, 5}




