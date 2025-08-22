# Seven-Segment-Display-Using-Arduino
# To design and implement a system to display the digit “2” on a 7-segment display using an Arduino microcontroller.
# COMPONENTS REQUIRED
Arduino UNO
proteus
# PROCEDURE

Step 1: Connect all the components as per the circuit diagram. </br>
Step 2: Open the Arduino IDE. </br>
Step 3: Go to File → New File to create a new sketch. </br>
Step 4: Type the program. </br>
Step 5: Save the program. </br>
Step 6: Go to Sketch → Verify to compile the program. </br>
Step 7: If no errors, connect the Arduino UNO to your computer using a USB cable. </br>
Step 8: Select the correct board and port in the Arduino IDE. </br>
Step 9: Upload the program into Arduino UNO. </br>
Step 10: Run the simulation in Proteus or observe the hardware output. </br>

# THEORY
# Introduction

A 7-Segment Display is an electronic display device used to display decimal numerals. It consists of 7 LEDs (labeled a–g) arranged in a figure-eight pattern. By lighting specific segments, numbers from 0–9 can be displayed.

In this project, the Arduino controls each segment individually by providing a HIGH (ON) or LOW (OFF) signal to the pins connected to the display. The number “2” is formed by turning ON segments a, b, d, e, g.

 # CIRCUIT DIAGRAM
 <img width="1012" height="629" alt="Screenshot 2025-08-22 213625" src="https://github.com/user-attachments/assets/4a3bcc1a-0aa7-443d-97e0-d9ebdf5acbde" />
## PROGRAM:

```
int a = 2;
int b = 3;
int c = 4;
int d = 5;
int e = 6;
int f = 7;
int g = 8;

void setup() {
  pinMode(a, OUTPUT);
  pinMode(b, OUTPUT);
  pinMode(c, OUTPUT);
  pinMode(d, OUTPUT);
  pinMode(e, OUTPUT);
  pinMode(f, OUTPUT);
  pinMode(g, OUTPUT);
}

void loop() {
  
  digitalWrite(a, HIGH);
  digitalWrite(b, HIGH);
  digitalWrite(c, LOW);
  digitalWrite(d, HIGH);
  digitalWrite(e, HIGH);
  digitalWrite(f, LOW);
  digitalWrite(g, HIGH);
}

```
# OUTPUT:
<img width="948" height="490" alt="Screenshot 2025-08-22 115150" src="https://github.com/user-attachments/assets/8bc8ded7-8c53-454f-8c43-0502a448626e" />

<img width="1105" height="590" alt="Screenshot 2025-08-22 115135" src="https://github.com/user-attachments/assets/11878fe0-75ae-4336-a303-b4ef06734fa3" />
