**DISCLAIMER: THIS IS FOR EDUCATIONAL PURPOSES ONLY. This tool was made as a research project in order to gain a further understanding of the offensive tools that red teamers possess.**

# SMTP-Keylogger
The  keylogger code I wrote is designed to capture user keystrokes and store them in a text file. The code first imports the 'pynput' library, which is used to detect keystrokes. It then creates a function called 'log_keypress', which stores each keystroke in a text file called 'keylog.txt'. The code also creates a listener to detect key presses and call the 'log_keypress' function.

The code also includes a function to detect the Esc key and automatically send the logs. This is done using a SMTP server, which is configured using the user's email address and password. The code also allows for the user to specify the email address and password to send the logs, as well as the location of the logs folder. Once the logs have been sent, the text file is deleted to protect the user's privacy.
