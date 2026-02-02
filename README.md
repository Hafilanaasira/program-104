# program-104
import math

# Input sides of the triangle
a = float(input("Enter the length of side a: "))
b = float(input("Enter the length of side b: "))
c = float(input("Enter the length of side c: "))

# Semi-perimeter
s = (a + b + c) / 2

# Area using Heron's formula
area = math.sqrt(s * (s - a) * (s - b) * (s - c))

# Display the result
print("Area of the triangle is:", area)
output
Enter the length of side a: 5
Enter the length of side b: 6
Enter the length of side c: 7
Area of the triangle is: 14.696938456699069
