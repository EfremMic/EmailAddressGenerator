#EmailAddressGenerator

This is a simple Java program that generates an email address and a random password for a user based on their first and last name and chosen department.

How to Use
Clone the repository to your local machine.
Open the project in your preferred IDE.
Run the Email.java file.
Follow the prompts to enter your first name, last name, and department.
Your email address and password will be generated and displayed.
Program Overview
The Email class has several private methods that are used to collect user input and generate the email address and password.

firstNameInput() and lastNameInput() methods prompt the user to enter their first and last name, respectively.
setDepartment() method prompts the user to choose their department from a list of options and returns their selection.
passwordGenerator() method generates a random password of a specified length.
emailConstructor() method combines the user's first name, last name, and department to create their email address.
The Email class also has a constructor that calls these methods to create a new email object for the user.

Future Improvements
Add validation to ensure that the user enters a valid department choice.
Allow the user to specify the length of the generated password.
Provide an option for the user to change their password after it has been generated.
