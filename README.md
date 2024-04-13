The objective of this project is to build a password detector using LPC1768 microcontroller along with keyboard,LEDs and LCD display. The system will allow users to input a password using keyboard, which will then be compared to a pre-defined password. If the input matches the correct password, the LCD will display “Access Granted” and LED will light up in a pattern, indicating successful authentication. Otherwise, a red LED will indicate authentication.

Components Required :
-	LPC1768 microprocessor
-	LCD display
-	LED lights
-	Keyboard
-	Switch to clear password (Reset)

Description and Working :

The project utilizes an LPC178 microcontroller to implement a password-based access control system. The system comprises a keyboard, an LCD display, and LEDs. 
 
•	Keyboard Input: Users input the password via the keyboard interface connected to the LPC178 microcontroller.
 
•	Password Detection: The microcontroller compares the entered password with a predefined password stored in its memory.
 
•	 Access Granted/Access Denied Display: 
   - If the entered password matches the predefined password, the LCD display shows “Access Granted”, indicating successful authentication.
   - If the entered password does not match the predefined password, the LCD display shows “Access Denied”, indicating unsuccessful authentication.
 
•	 LED Feedback:
   - Access Granted: Upon successful authentication, the LEDs display a predefined serial pattern or sequence, indicating access granted.
   - Access Denied: Upon unsuccessful authentication, the LEDs blink in a specific pattern, signaling access denied.
