# Barber Shop Problem

## DEMO

### https://sauravhathi.github.io/sleeping-barber/

## Screenshot

#### HomePage
![image](https://user-images.githubusercontent.com/61316762/200036042-21fcc361-d3a8-489c-bf00-4a974067bbd8.png)

#### Input
![image](https://user-images.githubusercontent.com/61316762/200036321-5f83387c-ddaf-45dd-a611-d7603274781f.png)

#### Simulation Output
![image](https://user-images.githubusercontent.com/61316762/200036408-0a0d7d74-306d-4108-a74f-f8dd69b6dd11.png)

#### When No Customer
![image](https://user-images.githubusercontent.com/61316762/200036767-35f7f4d4-7252-4202-a417-ed72d152bf3f.png)

## Description

This is a solution to the barber shop problem using a queue data structure. The barber shop problem is a classic synchronization problem. The problem is that there is a barber shop with a waiting room and a barber chair. There are n chairs in the waiting room. If there are no customers to be served, the barber goes to sleep. If a customer enters the barber shop and all chairs are occupied, then the customer leaves the shop. If the barber is busy, but chairs are available, then the customer sits in one of the free chairs. If the barber is asleep, the customer wakes up the barber.

## Functions

- getValues() - This function gets the number of customers and chairs from the user.
- clr() - This function clears the output.
- start() - This function starts the simulation.
- sleep() - This function is used to delay the execution of the code.

## Classes

- FifoQueue - This class is used to create a queue data structure.

## Methods

- enqueue() - This method adds an element to the queue.
- dequeue() - This method removes an element from the queue.
- size() - This method returns the size of the queue.
- isEmpty() - This method checks if the queue is empty.

## How to use

- Enter the number of customers. e.g. 1 2 3 4 5 6 7 8 9 10
- Enter the number of chairs. e.g. 7

**Note:** Purpose of this project only visualizing the process. I didn't use any data structure or algorithm except `FifoQueue`. I just used the basic javascript and html. I will try to implement the data structure and algorithm in the future. If you have any suggestion or question please comment below. Thank you for reading.
