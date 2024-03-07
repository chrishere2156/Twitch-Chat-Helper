
- Gui with a open vertical space for text to appear, with a scroll bar on the side and a text box at the bottom which the user types start and stop to the program. At the top is 2 tabs one says overview the other when clicked on asks for a username and then shows all the messages from that one person. And on the right side at the top and exit button. On the left is settings icon button that when pressed shows a opace red box where the program is looking for text.
- when the user types start in the text box the main program starts:
- create multithreading pool with a quarter of all available threads for better efficiency. The pool allows the program to pick the current least used thread.
- take a picture of the specified area on screen
- convert the image to greyscale for better accuracy
- look for the first word or words before a colon sign and set that as the user. This text will never be white.
- if the user matches one preset inside the program or set inside the Gui copy the users name and the text next to it. Note the text sent by the user can span multiple lines and is shown as white text. Make sure it gets all of it
- copy the current time in hour and minute eh 14:35, username, text and paste it to the overview tab and if the second tab matches the username paste it there too.
- repeat untill the user types stop in the Gui text box.




Chat GPT Steps it gave me to follow:

To start with your project, it's best to break down the tasks into smaller, manageable steps. Here's a suggested roadmap:

GUI Design and Implementation:

Start by designing the GUI layout based on your description.
Implement the GUI using a library like Tkinter for Python or any other GUI framework you're comfortable with.
Add functionality for the start and stop buttons, tabs, settings, and exit button.
Multithreading Setup:

Implement the multithreading setup with a thread pool.
Test the thread pool to ensure it's working correctly and efficiently.
Screen Capture and OCR Integration:

Implement the logic to capture screenshots of the specified area on the screen.
Integrate OCR functionality using a library like Tesseract (pytesseract) to extract text from the captured screenshots.
Test the screen capture and OCR process to ensure accurate text extraction.
Text Processing and User Identification:

Develop logic to process the extracted text, identify the user based on predefined criteria (e.g., text before a colon), and extract the username and message.
Handle cases where the username or message spans multiple lines or contains special characters.
Timestamping and Message Logging:

Implement timestamping functionality to record the time when each message is captured.
Set up message logging to store the username, message, and timestamp in memory or a data structure.
GUI Integration:

Integrate the functionality to display messages in the GUI, both in the overview tab and the user-specific tab.
Ensure that messages are displayed accurately and updated in real-time.
User Interaction and Control:

Implement functionality to start and stop the message capture process based on user input in the GUI text box.
Test user interaction to ensure smooth control of the program.
Settings and Configuration:

Implement functionality to specify the area where the program looks for text and other settings.
Allow users to customize settings through the GUI.
Error Handling and Testing:

Implement error handling mechanisms to handle unexpected scenarios gracefully.
Test the program extensively, including edge cases and error scenarios, to ensure robustness and reliability.
Optimization and Refinement:

Optimize the program for performance, memory usage, and efficiency.
Refine the user interface and user experience based on feedback and usability testing.
Documentation and Deployment:

Document your code, including comments, to make it understandable and maintainable.
Prepare the program for deployment, including packaging, distribution, and installation instructions if applicable.