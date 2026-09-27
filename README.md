numbers = []
print("Enter the numbers one by one. (Enter '0' to finish)")

while True:

    num = int(input("Provide a number : "))
    if num == 0:
        break
    numbers.append(num)
if numbers:

    largest = max(numbers)
    smallest = min(numbers)
    print("\n---Result---")
    print("MAX Numbe:", largest)
    print("MINI Numbe:", smallest)
else:

    print("No numbers were included")
