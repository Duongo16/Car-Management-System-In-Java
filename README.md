# Car Management System Readme

## Overview
This Java program, named CarManager, serves as a simple car management system. It allows users to perform various operations related to brands and cars, such as listing, adding, searching, updating, and saving data to files.

## How to Use

### 1. Setup
Before running the program, make sure to update the file paths for the car and brand data files in the `CarManager` class.

```java
String fileCarsName = "path/to/cars.txt";
String fileBrandsName = "path/to/brands.txt";
```

### 2. Menu Options
The program provides the following menu options:

1. **List all brands**
2. **Add a new brand**
3. **Search a brand based on its ID**
4. **Update a brand**
5. **Save brands to the file, named brands.txt**
6. **List all cars in ascending order of brand names**
7. **List cars based on a part of an input brand name**
8. **Add a car**
9. **Remove a car based on its ID**
10. **Update a car based on its ID**
11. **Save cars to file, named cars.txt**

### 3. Running the Program
Execute the `main` method in the `CarManager` class. The program will display the menu, and you can choose options by entering the corresponding numbers.

### 4. Brand and Car Classes
- `Brand` class represents a car brand with attributes like brand ID, name, sound brand, and price.
- `BrandList` class extends `ArrayList<Brand>` and provides operations for loading, saving, searching, adding, and updating brands.
- `Car` class represents a car with attributes like car ID, brand, color, frame ID, and engine ID.
- `CarList` class extends `ArrayList<Car>` and provides operations for loading, saving, searching, adding, and updating cars.

### 5. Menu Class
The `Menu` class handles user input for menu options and brand selection.

## Notes
- The program uses text files (`brands.txt` and `cars.txt`) to store brand and car data.
- Brands and cars are displayed in a structured manner, and the program ensures unique IDs for each brand and car.

Feel free to explore and modify the code according to your needs. If you encounter any issues or have suggestions for improvement, please let me know.
