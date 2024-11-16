while True:
    while True:
        a = input("Enter the number of rows: ") 
        if a.isdigit():
            a = int(a)
            break
        else:
            print("Please enter a valid number.")  # Ask again if the input is invalid

    c = input("Enter the character: ")

    for x in range(1, a + 1):  # Loop to create the pattern
        print(c * x)  # Print the character multiplied by the current loop number

    repeat = input("Do you want to create another pattern? (yes/no): ").strip().lower()     # ask to repeat.
    if repeat != 'yes':
        break 
