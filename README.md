# Car Building Factory Project

This project involves creating a car building factory using JavaScript. It covers creating car objects, adding parts to cars, displaying car details, and managing a factory of multiple cars.

## Part 1: Create a Car Object

### Step 1.1: Initialize the Project

- Create a new file named `carFactory.js`.

### Step 1.2: Define the Car Object

- Define a car object with properties like make, model, year, color, and parts array.
- Each car should have properties:
  - `make` (e.g., 'Toyota')
  - `model` (e.g., 'Corolla')
  - `year` (e.g., 2022)
  - `color` (e.g., 'Red')
  - `parts` (an empty array to store parts)

## Part 2: Be Able to Create Parts

### Step 2.1: Define the `addPart` Function

- Create a function named `addPart` that takes a car object, part name, type, and price as arguments.
- This function should create a part object with the provided name, type, and price, then add this part to the car's `parts` array.
- Use `console.log` to confirm the part was added successfully.

### Step 2.2: Add Parts to a Car

- Use the `addPart` function to add parts to the car object created in Part 1.
- Add at least three different parts, ensuring each part has a name, type, and price.

## Part 3: Display Car

### Step 3.1: Define the `displayCar` Function

- Create a function named `displayCar` that takes a car object as an argument.
- This function should log the car's details (make, model, year, color).
- Additionally, it should log the names of all parts added to the car (if any), or indicate that no parts have been added yet.

### Step 3.2: Display the Car Details

- Use the `displayCar` function to display the details of the car object created and updated in Parts 1 and 2.

## Part 4: Display Full Parts and Handle Missing Cars

### Step 4.1: Update the `displayCar` Function

- Modify the `displayCar` function to include detailed information about each part (name, type, price).
- Ensure the function handles cases where no parts have been added.

### Step 4.2: Handle Missing Cars

- Add a check in the `displayCar` function to handle cases where the car object passed to the function is `null` or `undefined`.
- Use `console.log` to indicate if the car is not found.

## Part 5: Add the Car Factory

### Step 5.1: Define the Factory Object

- Create a factory object that manages multiple cars.
- The factory object should have an array named `cars` to store car objects.
- Define a method `createCar` within the factory that creates a new car object (as defined in Part 1) and adds it to the `cars` array. This method should return the newly created car object.

### Step 5.2: Add the `addPart` Method to the Factory

- Define a method `addPart` within the factory that takes a car ID, part name, type, and price as arguments.
- This method should find the car by its ID in the `cars` array and add the part to it using the logic defined in Part 2.

### Step 5.3: Define the `displayCar` Method in the Factory

- Define a method `displayCar` within the factory that takes a car ID as an argument.
- This method should find the car by its ID and display its details using the logic defined in Parts 3 and 4.

### Step 5.4: Define the `displayAllCars` Method

- Define a method `displayAllCars` within the factory that displays the details of all cars stored in the factory.
- This method should iterate over the `cars` array and display each car's details.

### Step 5.5: Test the Factory

- Create multiple car objects using the factory's `createCar` method.
- Add parts to these cars using the factory's `addPart` method.
- Display individual car details using the factory's `displayCar` method.
- Display all cars in the factory using the factory's `displayAllCars` method.

By following these parts, you'll build a comprehensive car building factory that demonstrates key JavaScript concepts like objects, arrays, and functions. Happy coding!
