# PythonProject

## Email Validation Python Project

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

---------------------------------------------------------------------------------------------------------------------------------------------------


# ShutDown App

The ShutDown App is a simple graphical application built using Tkinter, a Python GUI toolkit, that allows users to perform various shutdown operations on their computer. The application provides four options: Restart, Restart Time, Log-Out, and ShutDown.

## Requirements

To run the ShutDown App, make sure you have the following:

- Python 3 installed on your system.
- Tkinter library installed. (Note: Tkinter is usually included in the standard Python installation)

## How to Run the Application

1. Open a text editor and create a new Python file.
2. Copy and paste the provided code into the Python file.
3. Save the file with a `.py` extension (e.g., `shutdownapp.py`).
4. Open a terminal or command prompt and navigate to the directory where the Python file is saved.
5. Run the application by executing the command: `python shutdownapp.py`.

## Usage

Once the ShutDown App is running, you will see a window with four buttons:

- Restart: Clicking this button will immediately restart the computer.
- Restart Time: Clicking this button will schedule a restart after 20 seconds.
- Log-Out: Clicking this button will log out the current user from the computer.
- ShutDown: Clicking this button will immediately shut down the computer.

Note: Some of the operations (such as restarting or shutting down) may require administrator privileges on the system.

## Contributing

This application is a basic implementation and does not include any advanced error handling or additional features. Contributions to enhance the functionality or improve the code are welcome. If you find any issues or have suggestions, please feel free to create an issue or submit a pull request.


## Disclaimer

Please use the ShutDown App responsibly. Be cautious when performing shutdown operations, especially if you have unsaved work or other important processes running on your computer. The author and contributors of the ShutDown App are not responsible for any data loss or damages that may occur due to the use of this application.

