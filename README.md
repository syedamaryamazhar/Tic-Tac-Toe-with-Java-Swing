# Tic-Tac-Toe-with-Java-Swing
A classic Tic Tac Toe game built using Java Swing. This game allows you to play in two modes:

1. Player vs Player
2. Player vs Computer (with basic AI)

The game uses visually appealing buttons, custom icons, and background images for a fun and interactive experience.

🧠 Features
Play against another player or the computer.

-Choose your token (X or O).
-Graphical user interface using JFrame, JPanel, JButton.
-Dynamic background images and button icons.
-Highlights the winning combination with different icons.
-Basic AI for the computer opponent (chooses best available move).
-Full-screen game windows.

🖥️ Technologies Used
-Java (JDK 8+)
-Swing (GUI)
-AWT (Graphics and Event Handling)

📂 Project Structure
├── GUI.java                  # Main game logic and UI
├── X.png                     # Icon for X token
├── O.png                     # Icon for O token
├── gridbg.png                # Background for grid buttons
├── Xwin.png / Owin.png       # Icons for horizontal wins
├── Xwincolm.png / Owincolm.png   # Icons for vertical wins
├── XwinDR.png / OwinDR.png   # Icons for diagonal wins
├── start button.png          # Start button image
├── p2p.png                   # Player vs Player button image
├── p2c.png                   # Player vs Computer button image
├── Play Now.png              # Button to begin the match
├── ticbg.png                 # Start screen background
├── ticbg2.png                # Token selection background
├── ticbg3.png                # Game mode selection background

🚀 How to Run
1. Make sure you have Java installed.
2. Place all .png image assets in the same directory as your .java file.
3.Compile and run:
  -javac GUI.java
  -java GUI
   
🕹️ Controls
-Click "Start" on the main screen.
-Choose between Player vs Player or Player vs Computer.
-Select your token (X or O).
-Click on a grid cell to make your move.
-Game ends with a win or draw message.

📌 Notes
- Ensure all the required image files are correctly named and placed in the project directory.
- The game uses full-screen mode for better visuals.
- Basic error handling included (e.g., clicking on occupied cells).

💡 Future Improvements
1. Add reset/replay button.
2. Improve AI to block opponent's winning moves.
3. Add sound effects for moves and win/loss.

👩‍💻 Author
-Developed by Syeda Maryam Azhar and Uswa Imtiaz (group member)
-Built for learning Java GUI and event handling.
