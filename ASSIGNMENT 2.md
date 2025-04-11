#Create a code which prints ' * ' this symbol in a right half pyramid.

pyramid = 5
for i in range(1, pyramid + 1):
    print('* ' * i)

# Create a code which prints left half pyramid.

    n = 5  # You can change this number to increase/decrease the size

for i in range(n, 0, -1):
    for j in range(i):
        print("*", end=" ")
    print()

# Create a code which prints right half pyramid.
pyramid = 5
for i in range(1, pyramid + 1):
    print('* ' * i)
Output - 
* 
* * 
* * * 
* * * * 
* * * * * 
# Create a code which prints reverse left half pyramid.
n = 5  # You can change this number to increase/decrease the size

for i in range(n, 0, -1):
    for j in range(i):
        print("*", end=" ")
    print()
Output -
* * * * * 
* * * * 
* * * 
* * 
*

# Create a code which prints reverse right half pyramid.
n = 5  # height of the pyramid

for i in range(n):
    # print leading spaces
    for j in range(i):
        print("  ", end="")
    # print stars
    for k in range(n - i):
        print("*", end=" ")
    print()
Output - 
* * * * * 
  * * * * 
    * * * 
      * * 
        *
# Create a code which prints pyramid.
pyramid = 5
for i in range(pyramid):
    print(" " * (pyramid - i - 1) + "*" * (2 * i + 1))
    *
   ***
  *****
 *******
*********

# Create a code which prints a reverse pyramid.
n = 5

for i in range(n):
    # Print leading spaces
    for j in range(i):
        print(" ", end="")
    # Print stars
    for k in range(n - i):
        print("* ", end="")
    print()

Output - 
* * * * * 
 * * * * 
  * * * 
   * * 
    *


















