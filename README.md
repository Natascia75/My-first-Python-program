# My-first-Python-program
My first program in Python 
# This is the main function of Python 
def main():
    numbers = []

    # executes "x" iterations
    for x in range(7):
        print("Iteration: ", x)
        numberx = int(input("Enter your number: "))
        numbers.append(numberx)

    # print the list of numbers
    print(numbers)

    # compute the total sum of numbers
    sum = 0
    for y in numbers:
        sum = sum + y

    # print the final result
    print("The total sum is: ", sum)
    print("Thanks for watching")

# This is the entry point of my code
if __name__ == "__main__":
    main()

