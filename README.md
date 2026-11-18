This project is a display simulator that scrolls user-defined information from right to left across the screen.

The circuit was designed and simulated in **Proteus**, using the **ATmega32** microcontroller as its processor. The display consists of a **16×2 LCD** (16 columns and 2 rows) for presenting the information.

The program was written in **C** and compiled using **CodeVisionAVR (CVAVR)**.

The scrolling text is controlled by the program running on the ATmega32 microcontroller. The microcontroller continuously updates the LCD display by shifting the displayed characters from right to left, creating a scrolling text effect.

The scrolling speed is determined by the delay between consecutive display updates. By modifying this delay in the C program, you can adjust how fast the text moves across the 16×2 LCD.
