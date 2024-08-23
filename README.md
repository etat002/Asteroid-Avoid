# Asteroid Avoid
## Introduction:
The project is a single player/multiplayer game where the goal is to avoid incoming asteroids for as long as possible, or in the case of two players until the other player is hit. As the game progresses in time the difficulty increases, and asteroid velocities and frequencies will increase likewise. 
## Complexities:
* Nokia 5110 LCD Screen
* Random Number Generator
* Multiplayer functionality
## User Guide:
The game can be set to one player or two player mode by moving the switch to the left/middle for two players or the right for one player. Make sure to set the preferred player option and then restart the game. To move as player one, use the joystick to the right and the left for player two. There will be a photoresistor that will read in light levels to aid in randomness. The three LEDs all the way in the back will indicate the difficulty level the game is currently on, 1 LED for easy, 2 for medium, and 3 for hard. Upon getting hit, there will be a game over screen. In multiplayer mode, the LED on the winner’s side will light up. When the game is over, or whenever the user feels like restarting the game, press the red button on the arduino board.
## Hardware Components Used:
* 1x Nokia 5110 LCD Screen
* 2x Joysticks
* 6x LEDS
* 1x Potentiometer
* 1x Switch
* 1x PhotoResistor
* 6x Resistors (220 ohms)
* 1x Breadboard
* 1x Elegoo Uno R3
## Software Libraries Used:
* Adafruit_GFX
* Adafruit_PCD8544
* SPI
## Wiring Diagrams:
<details close>
  <summary>Click Me</summary>
  <IMG src="https://github.com/user-attachments/assets/929c18d6-f47b-4878-bd1a-0614cae95f04" alt = "Wiring image1"/>
  <IMG src="https://github.com/user-attachments/assets/39f8a494-5633-4abd-8c48-738a93bc4396" alt = "Wiring image2"/>
</details>

## Task Diagram:
<details close>
  <summary>Click Me</summary>
  <IMG src="https://github.com/user-attachments/assets/093ab8d2-dd7e-4370-8297-4c7d14cd8006" alt = "Task Diagram"/>
</details>

## SynchSM Diagrams:
<details close>
  <summary>Click Me</summary>
  <IMG src="https://github.com/user-attachments/assets/37620f7c-f0c7-413e-baa9-233f23b65b5a" alt = "Spaceship SM"/>
  <IMG src="https://github.com/user-attachments/assets/612d9977-1f17-4f05-964b-c7915f74a5f8" alt = "Asteroids SM"/>
  <IMG src="https://github.com/user-attachments/assets/c65fb278-a61f-4d51-ade6-be10373a2ee5" alt = "Collide SM"/>
  <IMG src="https://github.com/user-attachments/assets/ebb7cd6c-adf2-4dbc-b0ad-890a67c14870" alt = "Difficulty SM"/>
</details>
