# LED Chase Sequence using Arduino

A simple LED chase (Knight Rider–style) pattern using four LEDs — Red, Green, Blue, and Yellow — lighting up in a forward-and-back sequence.

## Components
- Arduino Uno
- 4x LEDs (Red, Green, Blue, Yellow)
- 4x 220Ω resistors
- Breadboard & jumper wires

## Pin Connections
| LED    | Pin |
|--------|-----|
| Red    | 13  |
| Green  | 8   |
| Blue   | 4   |
| Yellow | 2   |

## How It Works
LEDs light up in sequence: Red → Green → Blue → Yellow → Blue → Green → Red, each staying on for 200ms before turning off, creating a bouncing chase effect. Loops continuously.
 
## Simulation
Built and tested on [Wokwi](https://wokwi.com).

## Usage
1. Open `sketch.ino` in Arduino IDE or Wokwi
2. Wire LEDs as shown above
3. Upload and run

## Author
Nagur425
