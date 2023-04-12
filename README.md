# CodeClause_AlarmClockwith_GUI
Alarm Clock with GUI
This program is an alarm clock with a Graphical User Interface (GUI) built using the Tkinter library in Python. It allows the user to set an alarm by specifying the time and a message to be displayed when the alarm goes off. When the specified time is reached, the program will display a message box with the user-specified message.

Requirements
This program requires Python 3.x and the Tkinter library, which is included with most Python installations. If Tkinter is not installed on your system, you can install it using pip:
python
pip install tkinter 


How to use
Clone the repository or download the code.
Run the alarm_clock_gui.py file.
Set the alarm time using the spinboxes for hours, minutes, and seconds.
Enter a message to be displayed when the alarm goes off.
Click the "Set Alarm" button to set the alarm.
To cancel the alarm before it goes off, click the "Cancel Alarm" button.


Acknowledgments
This program was inspired by this tutorial by "Tech With Tim".


Here is the algorithm for the Alarm Clock with GUI:

Import the necessary libraries - tkinter, datetime, and time.
Create a class called AlarmClock that inherits from the Tk class in the tkinter library.
In the __init__ method of the AlarmClock class, create the GUI with the following widgets:
A Label widget with the text "Set Alarm".
Three Spinbox widgets for the hours, minutes, and seconds.
A Label widget with the text "Message".
A Entry widget for the message to be displayed when the alarm goes off.
Two Button widgets for setting and canceling the alarm.
Define a method called set_alarm that retrieves the user-specified time and message from the GUI, calculates the time until the alarm goes off, and creates a new thread to wait for that amount of time before displaying the message box.
Define a method called cancel_alarm that stops the thread created in set_alarm.
Define a method called display_message that creates a message box with the user-specified message.
Instantiate the AlarmClock class and start the main event loop with the mainloop() method.
