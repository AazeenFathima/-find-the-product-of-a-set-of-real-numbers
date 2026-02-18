# -find-the-product-of-a-set-of-real-numbers

i = 0
product = 1
count = int(input("Enter the number of real numbers: "))
for i in range(count):
    x = float(input("Enter a real number: "))
    product = product * x
print("The product of the numbers is: ", product)

OUTPUT :
Enter the number of real numbers: 3
Enter a real number: 2
Enter a real number: 3
Enter a real number: 4
The product of the numbers is:  24.0
