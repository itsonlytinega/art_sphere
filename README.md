# GAMEPLAY

The player controls a sphere at the bottom of the screen and must dodge randomly appearing obstacles falling from the top. The game increases in speed every 10 points, making it progressively harder to avoid obstacles as the score grows. The game ends if the sphere collides with an obstacle.

# CONTROLS

- Left Arrow Key: Move the sphere left. 
- Right Arrow Key: Move the sphere right. 
- R Key: Restart the game after a Game Over.

# GAME FEATURES

- **3D Perspective Grid**: The background is a green grid with a perspective effect to simulate depth.
- **Dynamic Difficulty**: Game speed increases at intervals as the player's score goes up, adding more challenge.
- **Score Display**: The player's score is displayed in the top left corner.
- **Game Over and Restart**: If the player collides with an obstacle, a "Game Over" message is shown. Press 'R' to restart the game.

# SETUP INSTRUCTIONS

To clone and set up the game, use the following Bash script. Save this script as `setup_game.sh` in the root directory of your project and run it to install dependencies and start the game.

```bash
#!/bin/bash

# Display information about the script's purpose
echo "Cloning and setting up the game project..."

# Clone the project repository from GitHub
# Replace 'your-repo-url' with the actual GitHub repository URL
git clone https://github.com/itsonlytinega/art_sphere.git)

# Navigate into the project directory
cd your-repo-name

# Check if Node.js and npm are installed
if ! command -v node &> /dev/null || ! command -v npm &> /dev/null
then
    echo "Node.js or npm not found. Please install them first."
    exit 1
fi

# Install dependencies (assuming it's a Node.js project)
npm install

# Start the game (optional - replace 'start' with the relevant command)
npm start

echo "Game setup complete. Use the Left and Right arrow keys to control the sphere and avoid obstacles!"





   
