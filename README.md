LCD_Library
===========

This contains the necessary functions to get the LCD to initialize and send scrolling messages to the LCD screen

Functions:

void initSPI()- Initializes the subsystem

void lcdInitialize()- Initializes the LCD on the geekbox

void lcdClear()- Clears the LCD screen

void displayScreen(char * message) - Displays a message to the screen

void writeCommandByte(char * byteToSend) - sends a command byte to the LCD

void buttonInitialize() - Initializes the buttons on the geek box

void buttonSelect() - Checks to see if a button is selected

void scrollDisplay(char * topMessage, char * bottomMessage) - scrolls a message on both the top and bottom lines on the
LCD screen
