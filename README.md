Elevator Problem:

About: 
This program simulates an elevator dropping off people at different floors and calculating total number of stops.

Note:
The code is a structure specific to only the problem statement1.

Please use IDE: Eclipse or IntelliJ for the code. 
1. Create new project on the IDE
2. Create new class called Elevator under that project
3. Copy the contents of Elevator.java in the Git  to that created class
4. Run the program

Algorithm:
1. Initialize a HashMap with keys as person ID and values as weight of each person.
2. Generate a random number using Math function
3. Use random number generated to select person ID and add the weight associated with that ID to weight of elevator in a loop
4. Check weight of elevator
5. If weight<200 generate next random number without generating the previous random number again.
6. If weight is >200 remove weight that was just added and generate the next random number without generating the previous random number again.
7. If weight is 200, exit loop
8. Calculate number of stops using remaining elements in HashMap
9. Execute main function to get number of stops.
