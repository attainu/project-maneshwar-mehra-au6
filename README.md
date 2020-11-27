# Parking Lot

## Introduction :

Off-street parking is an important part of the transportation system. As it is very difficult to manage and maintain the huge parking lot so there were this project comes in the scenario. This project can keep the record based on the **Registration number**(Number Plate no.) and the **Color of the car**.


## Description

This repository gives an overview of how we can design a basic parking lot in Python. It creates parking lot with given number of slots. The cars follow Greedy approach while being parked in the slots.

ParkingLot.py script defines the following functions :

1. create_parking_lot n
> Given n number of slots, create a parking lot with n spaces.

2. park car_regno car_color
> Parks a vehicle with given registration number and color in the nearest empty slot possible. If there are no more empty slots available, it shows a message "Sorry, parking lot is full".

3. status
> Prints the slot number, registration number and color of the parked vehicles.

4. leave x 
> removes vehicle from slot number x 

5. You can use help command to see all the commands.

6. note 
> **Vehicle.py**  is a separate class where we can define the type of vehicles that can be parked. As of now, it only contains class Car


## How To Run :

To create your own parking lot :

1. Clone the repository.

2. Run ```python ParkingLot.py``` to run the program. This opens a shell where you can write your commands like :


3. Example :

**Input**

>create_parking_lot 6  
park KA-01-HH-1234 White  
park KA-01-HH-9999 White  
park KA-01-BB-0001 Black  
park KA-01-HH-7777 Red  
park KA-01-HH-2701 Blue  
park KA-01-HH-3141 Black  
leave 4  
status  
park KA-01-P-333 White  
park DL-12-AA-9999 White  
registration_numbers_for_cars_with_colour White  
slot_numbers_for_cars_with_colour White  
slot_number_for_registration_number KA-01-HH-3141  
slot_number_for_registration_number MH-04-AY-1111  


**Output**

>Created a parking lot with 6 slots  
Allocated slot number: 1  
Allocated slot number: 2  
Allocated slot number: 3  
Allocated slot number: 4  
Allocated slot number: 5  
Allocated slot number: 6  
Slot number 4 is free  
Slot No. Registration No Colour  
1 KA-01-HH-1234 White  
2 KA-01-HH-9999 White  
3 KA-01-BB-0001 Black  
5 KA-01-HH-2701 Blue  
6 KA-01-HH-3141 Black  
Allocated slot number: 4  
Sorry, parking lot is full  
KA-01-HH-1234, KA-01-HH-9999, KA-01-P-333  
1, 2, 4  
6  
Not found

# Further changes :

We can also add, some very exciting and helpful features in the program by just making some changes in  our ```Vehicle.py``` class.

# Link to the [project video] (https://drive.google.com/drive/folders/1QfXrZkEhzjKkCPZFdxFjtUfv2Z0ta-KI) 







