# new_demo
Hello Git<br>
my first git repository
<br> by - Adesh Kalamkar



Class Car:
    Properties:
        Make
        Model
        Year

    Method __init__(self, make, model, year):
        Set self.make = make
        Set self.model = model
        Set self.year = year

    Method display_details(self):
        Print “Car Make:”, self.make
        Print “Car Model:”, self.model
        Print “Car Year:”, self.year

    Method start(self):
        Print “The car is starting…”

Main Function:
    Create an object myCar with make=”Toyota”, model=”Corolla”, year=2020
    Call myCar.display_details()
    Call myCar.start()
… .. 
# Defining the Car class
Class Car:
    # Constructor to initialize car properties
    Def __init__(self, make, model, year):
        Self.make = make
        Self.model = model
        Self.year = year

    # Method to display car details
    Def display_details(self):
        Print(f”Car Make: {self.make}”)
        Print(f”Car Model: {self.model}”)
        Print(f”Car Year: {self.year}”)

    # Method to simulate starting the car
    Def start(self):
        Print(“The car is starting…”)

# Main function to demonstrate the use of the Car class
Def main():
    # Creating an object of the Car class
    myCar = Car(“Toyota”, “Corolla”, 2020)
    
    # Displaying car details
    myCar.display_details()
    
    # Starting the car
    myCar.start()

# Call the main function
If __name__ == “__main__”:
    Main()
,… .. … .. … .. . . . . . … 

Function find_largest_number(numbers):
    Initialize largest = numbers[0]  # Assume first element is the largest

    For each number in numbers:
        If number > largest:
            Set largest = number  # Update largest if a larger number is found

    Return largest

Main Function:
    Define an array numbers = [3, 5, 7, 2, 8]
    Call find_largest_number(numbers) and store the result in largest_number
    Print "The largest number is:", largest_number

… .. . . . . . . . . . . . . . . … … 


Flowchart:
1.	Start.
2.	Initialize largest = numbers[0].
3.	Loop through the array:
o	For each element in the array:
	Compare it with largest.
	If the element is greater than largest, set largest = element.
4.	End of loop.
5.	Output largest.
6.	Stop.
… . … …. . . … 


# Function to find the largest number in an array
def find_largest_number(numbers):
    largest = numbers[0]  # Assume the first number is the largest
    for number in numbers:
        if number > largest:
            largest = number  # Update largest if a bigger number is found
    return largest

# Main function to test the algorithm
def main():
    numbers = [3, 5, 7, 2, 8]  # Array of numbers
    largest_number = find_largest_number(numbers)
    print(f"The largest number is: {largest_number}")

# Call the main function
if __name__ == "__main__":
    main()

