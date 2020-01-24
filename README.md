# Unit-2-Hybrid
import math
print("This program calculates cost per square inch of a circular pizza.")
radius = float(input("Please enter the radius: "))
price = float(input("Please enter the cost without the dollar sign: "))
squareInch = (math.pi * (radius * radius))
squareCost = (price / squareInch)
print("The cost per square inch is: ", round(squareCost, 2))
