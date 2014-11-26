num_of_digits = input("How many digits? ")

for c in range(num_of_digits + 1):
    if c > 0:
        if c % 3 == 0 and c % 5 == 0:
            print ("FizzBuzz")
        elif c % 3 == 0:
            print("Fizz")
        elif c % 5 == 0:
            print("Buzz")
        else:
            print c
