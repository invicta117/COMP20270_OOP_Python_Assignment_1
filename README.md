# COMP20270 Object Oriented Programming in Python_Assignment

The aim of this project is to develop a system to manage a kitty for shared expences among a group of people. This project makes use of OOP in Python.

## Design
The design that was decided upon for this assignment was to use objects:

- individual, representing an individual that is using the Kitty application
- event, representing the activity that individuals participitae in

These were again broken down to smaller components

- Individual
    - name
   
- Event
    - participants
    - total
    - transaction names
    - personal balance
    
- Event methods
    - check participant
    - transaction
    - reconcile
    - balance
    - positive and negatively balanced indivduals
    
The individual class was decided upon as it allowed a way to handle many participants all which are based on the same class. This also allowed for attributes like name to be associated with an instance of individual something that would be of use later on. This also allowed for individuals to be passed to the event more easily rather than handling all of this together and allows for a more logical set up.

Event was chosen as another class as it allowed for many attributes like total and participants to be grouped together easily. This seemed like a logical place to store transactions related to an event as well as methods to allow balancing and reconciliation. This grouping of data and methods seemed like a perfect example of an object during the design phase.