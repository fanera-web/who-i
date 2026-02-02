# Guess Me
🎮 A mini-game based on the "Akinator" concept, where the system tries to guess a character by asking questions with **Yes / No** answers;

## How it works :
1. The game starts with a basic question: *"Does your character have a tail?"*;
2. If the answer is **Yes** → the option "Cat" is suggested;
3. If the answer is **No** → the system asks you to enter: - The character's name - Their distinguishing trait;
4. The new data is added to the knowledge base, making the game "smarter.";
5. In subsequent rounds, the system uses the accumulated questions and answers, gradually expanding the decision tree;
   
## Technologies :
- **HTML** — page structure;
- **CSS** — styling and responsive design;
- **JavaScript** — game logic, working with the decision tree and "localStorage";
   
## Features :
- Endless learning: each new character adds a branch to the tree;
- Data is saved in "localStorage" so the knowledge base isn’t lost after a reload;
- Simple interface with "Yes" / "No" buttons and a form to add characters;
