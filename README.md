Serial_String_Parse
===================

This repository demonstrates the use of the strtok_r() function to parse an incoming string. This is so that it can be used to call independent functions and set property values. At the heart of the presented code is a function called ParseSerialData() which utilises strtok_r() to separate the received string each time there is a comma “,” present. 

Then depending upon how many chunks of data have been identified the function calls one of two (but not limited to) switch statements that are used to determine what we want to do with the received data.

For more information, check out the following blog post:

http://www.dyadica.co.uk/journal/simple-serial-string-parsing/
