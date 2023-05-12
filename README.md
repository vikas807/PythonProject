# PythonProject# Email Validation Python Project

This Python project aims to validate an email address based on certain criteria. It checks whether the provided email address meets the following requirements:

1. The length of the email should be at least 6 characters. 
2. The first character of the email should be a letter.
3. The email should contain one and only one "@" symbol.
4. The domain extension should be either three or four characters long, preceded by a dot.
5. The email address should not contain any spaces.
6. The email address should not have any uppercase letters, except for the domain extension.
7. The email address can only contain letters, digits, underscores (_), dots (.), and the "@" symbol.

## Getting Started

1. Clone the repository or download the Python script to your local machine.
2. Make sure you have Python installed on your system.
3. Open a terminal or command prompt and navigate to the project directory.

## Usage

1. Run the script using the following command:

   ```
   python email.py
   ```

2. Enter the email address you want to validate when prompted.

## Validation Criteria

1. Email Length: The email should be at least 6 characters long. If the length is less than 6, the script will display the message "Wrong Email 1".

2. First Character: The first character of the email should be a letter. If it is not, the script will display the message "Wrong Email 2".

3. "@" Symbol: The email should contain exactly one "@" symbol. If there are more or less than one "@", the script will display the message "Wrong Email 3".

4. Domain Extension: The domain extension should be either three or four characters long, preceded by a dot. If the domain extension is not in the correct format, the script will display the message "Wrong Email 4".

5. Valid Characters: The email address should only contain letters, digits, underscores (_), dots (.), and the "@" symbol. It should not contain any spaces. If there are any invalid characters or spaces, the script will display the message "Wrong Email 5".

## Example

```
Enter your email: john.doe@example.com
```

Output:
```
```

In this example, the provided email address is valid, so no error message is displayed.

