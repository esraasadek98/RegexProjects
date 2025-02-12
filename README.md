# RegexProject Credit Card Type Detector
This UiPath automation project is designed to determine the type of a credit card based on its number. It uses regular expressions to validate and classify the card as one of the following types:
Visa
MasterCard
American Express
Discover
# How It Works
Input:
The user is prompted to enter their credit card number via an input dialog.

Validation:

The project checks if the card number is valid by ensuring it has between 13 and 16 digits.
Pattern Matching:
The card number is matched against predefined regex patterns for each card type:

Visa: Starts with 4 and has 13, 16 digits.

MasterCard: Starts with 5and has 13 to 16 digits.

American Express: Starts with 37 

Discover: Starts with 6 
Output:

The project logs the type of the credit card (if valid) or notifies the user if the card number is invalid.

How to Use
Open the Project:

Open the Main.xaml file in UiPath Studio.

Run the Workflow:

Click the Run button in UiPath Studio to execute the workflow.

Enter Card Number:

When prompted, enter your credit card number in the input dialog.

View Results:

The type of the credit card (if valid) will be displayed in the Output panel. If the card number is invalid, a message will be logged.

Workflow Details
The workflow consists of the following steps:

Input Dialog:

Prompts the user to enter their credit card number.

Digit Count Validation:

Checks if the card number has between 13 and 16 digits.

Regex Matching:

Matches the card number against the regex patterns for Visa, MasterCard, American Express, and Discover.

Logging:

Logs the card type or an error message if the card number is invalid.



