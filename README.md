# Connect with Four Game AI 🔴🟡


![FourGame](https://github.com/user-attachments/assets/e12d1661-6516-45ca-bcf6-bc8f4aba0663)

Hey there! Welcome to my Connect Four game - a fun twist on the classic board game we all grew up playing. I built this during my learning journey with Python and thought it would be cool to share it with everyone.

What's This All About?

Remember those lazy afternoons playing Connect Four with friends? Well, I recreated that experience but with a computer opponent that's actually challenging! The goal is simple - drop your colored pieces and try to connect four in a row before the AI does.

 Cool Stuff I Added

The Basics:
- Classic Connect Four gameplay (because why mess with perfection?)
- You get the green pieces, AI gets red (seemed fair to me)
- Click to drop pieces - super intuitive
- Win by getting 4 in a row any direction

The Fun Part - AI Levels:
I spent way too much time making the AI actually intelligent. Here's what I came up with:

- **Easy Mode**: Perfect for kids or when you just want to relax
- **Intermediate**: Gets a bit sneaky with its moves  
- **Hard**: Actually thinks about strategy
- **Impossible**: Uses fancy algorithms I learned about
- **Godmode**: Good luck beating this one... seriously

Visual Goodies:
- Smooth animations and hover effects
- Sound effects (because who doesn't love good audio feedback?)
- Clean, modern interface that doesn't hurt your eyes
- Little touches like piece shadows and highlights

Tech Stuff (For Fellow Developers)

I built this using Python because it's awesome and beginner-friendly:

```python
# Main tools I used
pygame    # For all the graphics and game window
numpy     # Makes board calculations super fast
math      # Needed for the AI algorithms
```

The Smart Stuff:
The AI isn't just randomly picking moves. I implemented:
- **Minimax Algorithm**: The AI thinks several moves ahead
- **Alpha-Beta Pruning**: Makes the AI think faster
- **Position Scoring**: AI evaluates how good each move is
- **Strategic Planning**: Blocks your winning moves while planning its own

Want to Try It?

You'll need:
- Python 3.7+ (most people have this already)
- A few minutes to install dependencies

Setup is super easy:
```bash
# Install the required packages
pip install pygame numpy

# Download my code and run it
cd src
python game.py
```

That's it! The game should pop right up.

How I Organized Everything

```
My Project/
├── src/                 # All the Python code
│   ├── game.py         # Main game - start here
│   ├── functions.py    # Basic game functions
│   ├── minmax_ai.py    # The smart AI stuff
│   └── ...
├── assets/             # Sounds and fonts
└── README.md          # You're reading it!
```

Playing the Game

1. **Pick Your Challenge**: Choose how smart you want the AI to be
2. **Your Turn**: Click any column to drop your green piece
3. **AI's Turn**: Watch it think and make its move
4. **Keep Going**: First to connect 4 wins!
5. **Play Again**: Hit restart to try beating the AI again

The game shows you where your piece will land with a dotted preview - pretty neat, right?

Behind the Scenes

How the AI Actually Works:
- It looks at the board and scores every possible move
- Considers both offensive and defensive plays
- The harder difficulties look more moves ahead
- Uses mathematical algorithms to find the best move

Scoring System I Created:
- Connecting 4 pieces = Instant win
- 3 in a row with a space = Really good
- 2 in a row with spaces = Decent start
- Center column = Extra points (strategic advantage)
- Blocking your wins = High priority

The Visual Experience

I wanted this to feel modern, not like those old school games. So I added:
- Smooth piece dropping animations
- Gradient effects on the board
- Reflective highlights on pieces (they look almost 3D!)
- Clean, rounded buttons
- Satisfying sound effects for each move

What's Next?

I have some ideas brewing:
- Player vs Player mode (for when you want to challenge friends)
- Online multiplayer (ambitious, but why not?)
- Statistics tracking (see how you improve over time)
- Custom themes and colors
- Maybe even mobile support

Found a Bug or Have Ideas?

I'm still learning, so if you spot something weird or have cool ideas, let me know! I love getting feedback and suggestions from other developers.

--> A Personal Note
This project taught me so much about game development, AI algorithms, and Python. It started as a simple "let me try making Connect Four" and turned into this whole thing with multiple AI difficulties and fancy graphics. 
The Minimax algorithm was particularly fun to implement - watching the AI actually think strategically instead of making random moves felt like magic the first time it worked.
Hope you enjoy playing it as much as I enjoyed building it! 
