#Create a code which prints ' * ' this symbol in a right half pyramid.

pyramid = 5
for i in range(1, pyramid + 1):
    print('* ' * i)

# Create a code which prints left hald pyramid.

    n = 5  # You can change this number to increase/decrease the size

for i in range(n, 0, -1):
    for j in range(i):
        print("*", end=" ")
    print()
