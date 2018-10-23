# cs50w-project2 "Flack"
This is my implementation of the third project in the CS50W course. The program I wrote is a (very basic) chat application. Users can join existing channels and create new ones after adding a username.

List of files:
- application.py: the file containing the server-side elements of the application (Python, Flask, Flask-Socketio).
- scripts.js: the file containing the client-side elements of the application (ES6).
- styles.css: the file containing the (very crude) visual styling of the program.
- layout.html: the file containing the HTML "blueprint" used by Jinja.
- index.html: the file containing the HTML used for the main/single page of the application (extends layout.html).
- requirements.txt: the file containing the required Python libraries for the program.

Quirks and issues of the application
- the program does not allow private messaging (tried to implement it, but failed)
- it does not use any databases (the project description stated we should not need one)
- You can only send messages by pressing the "Send" button. Pressing your Return key does not work. Also, you can send empty messages.
- A number of HTML elements are hidden until the user completes certain steps (adding their username and entering a channel). These elements often can be briefly visible when the page loads up.

