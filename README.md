## Flask Application Design for Plant vs. Zombies Game

### HTML Files

**1. index.html (Main Game Page)**
    - Contains the Canvas element for displaying the game
    - Includes buttons for controlling the game (start/pause, plant selection, etc.)
    - Displays the game score and other relevant information

**2. plant_selection.html (Plant Selection Menu)**
    - Displays a list of available plants
    - Allows the user to select and purchase plants
    - Includes a description of each plant and its cost

### Routes

**1. /start_game**
    - Starts a new game
    - Initializes the game state and creates the game board

**2. /place_plant**
    - Handles user input for placing plants
    - Checks if the plant can be placed at the specified location
    - Deducts the cost of the plant from the user's balance

**3. /remove_plant**
    - Handles user input for removing plants
    - Removes the plant from the game board and refunds its cost

**4. /move_plant**
    - Handles user input for moving plants
    - Checks if the move is valid and updates the plant's position

**5. /attack_zombie**
    - Handles user input for attacking zombies
    - Calculates the damage dealt to the zombie and updates its health

**6. /end_game**
    - Ends the current game
    - Calculates the user's score and displays it on the game over screen