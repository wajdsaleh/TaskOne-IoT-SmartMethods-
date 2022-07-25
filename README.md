# Speech to text
This is a task assigned by Smart Methods company. 
It's about creating a sample page to convert speech to text in Arabic.
# The idea
I developed a sample contact page that asks about first and last name, phone number, email, and the message that the user wants us to receive.
The message part is the speech recognition part because a lot of people find difficulties writing long messages so speech recognition will make it easier for them.
# How the code works
It's a simple JavaScript code that uses the webkitspeechrecognition function, to receive the speech then if it detects a long silence it will pause and convert the speech to a text. The user can click the microphone icon again to complete their message it will continue typing in where it stops. It will not delete the previous lines it wrote.
# Notes
The microphone image src is from google, if you have any errors just upload the image 'mic.png' and correct the src.
I choose this idea rather than a normal speech to text converter to make any company or individual that has a website and want a ready contact page can take this code and place it in the website.
# Future updates
Now the JavaScript code is using webkitspeechrecognition class which work only on specified browsers like Chrome and Safari, there will be another update soon using another method to let the code work on Internet Explorer and Firefox.
There will be some designing update as well.
