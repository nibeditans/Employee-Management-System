# Employee-Management-System
The Employee Management System is a basic Python application designed to showcase object-oriented programming concepts, particularly inheritance. It defines two primary classes: Employee and Engineer. The Employee class serves as a base class, encapsulating common attributes such as role, department, and salary. The Engineer class extends Employee, adding specific attributes like name and age, to demonstrate simple inheritance and method overriding in Python.

## Features
* **Employee Class:** Manages basic employee details including role, department, and salary.
* **Engineer Class:** Inherits from the Employee class and adds additional attributes for name and age, tailored for engineering roles.

## Requirements
Python 3.12.1
(You may be using a different version, so, no need to worry about that.)

## Installation
This script does not require installation beyond having Python installed on your computer. Simply download the employee_management_system.py (note: you'll name the script when saving) file to your local machine to get started.

## Usage
To use the Employee Management System, perform the following steps:

1. Ensure Python 3.x is installed on your system.
2. Save the provided code snippet as employee_management_system.py or another preferred script name.
3. Open a terminal or command prompt.
4. Navigate to the directory containing the saved script.
5. Execute the script by running:

       python employee_management_system.py

6. By default, the script is set up to instantiate an Engineer object with predefined attributes and display its details. Modify the script to create and interact with Employee and Engineer objects as needed.

## Example
Running the script with the provided example will output:

    NS
    role: Engineer
    Department: IT
    Salary: 75,000

## Customization
To create different types of employees or to adjust the attributes of the Engineer class, modify the constructor arguments in the Engineer class instantiation or directly in the class definitions. For example, to change the department and salary of the engineer, adjust the super().__init__() call in the Engineer class.

## Contributing
We welcome contributions and suggestions to improve the Employee Management System. Feel free to fork the repository, make changes, and submit pull requests. If you encounter any issues or have new features in mind, please open an issue in the repository.

## License
This project is freely available for free use and modification under the terms of the MIT License.

## Contact
For questions, feedback, or suggestions, please submit an issue through the GitHub repository.
