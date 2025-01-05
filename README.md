# Sudoku Puzzle

An interactive Sudoku puzzle application built with **React** and **Vite**. The app offers puzzle generation, puzzle solving, conflict detection, and real-time feedback for correct or incorrect entries. 

## Live At
sudoku-react-app-alpha.vercel.app

## Features

- **Generate Solution**  
  - Input your own Sudoku puzzle and get an instant solution.
  - Detect duplicate numbers in rows, columns, or sub-grids before submission.

- **Solve Puzzle**  
  - Generate random Sudoku puzzles at different difficulties (Easy, Medium, Hard).
  - Pre-filled cells are marked, and user input is checked for correctness in real time.
  - Real-time conflict checking for rows, columns, and 3×3 boxes.
  - A congratulatory message is displayed upon puzzle completion.

- **Modals & Alerts**  
  - Modular, reusable modals for user messages (e.g., errors, success).
  - Displays conflict warnings and alerts for invalid puzzles or wrong entries.

- **Responsive Design**  
  - Works seamlessly on desktops, tablets, and mobile devices.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v14 or above recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Running Locally

1. **Clone the repository**:
   ```
   git clone https://github.com/kskaman/sudoku-react-app.git
   ```

2. **Navigate to repository**:
   ```
   cd sudoku-react-vite
   ```
   
3. **Install dependencies**:
   ```
   npm install
   ```
4. **Start the development server**:
   ```
   npm run dev
   ```
    Vite will start a development server, typically at http://localhost:5173 (or the address shown in your terminal) Go to that address in your browser and enjoy the game.



## Technologies Used
- **React** for building the UI.
- **Vite** as the development server and build tool.
- **PropTypes** for component prop type checking.
- **JavaScript** for Sudoku solving and generation logic.
- **CSS Modules** for component-level styling.
- **HTML5** markup in conjunction with React components.

## Gameplay Instructions

#### Choose a Mode:
- **Generate Solution** : Enter your own Sudoku puzzle and click Submit to see the solution.
  - **Conflict Detection**: The puzzle detects duplicates in rows, columns, or 3×3 grids. You’ll see alerts for invalid entries.
    
- **Solve Puzzle**: Select a difficulty (Easy, Medium, Hard), and a random puzzle will be generated.
  - **Filling Cells**:
    - Click an empty cell and type a digit (1–9).
    - If the digit is correct, it will turn green. If incorrect, it turns red.
  - **Completion**: When all cells are filled correctly, a congratulations message is displayed.

## Contributing
Contributions, issues, and feature requests are welcome. Feel free to check the issues page to see if your idea or issue is already listed. If not, open one!

## License
This project is open-source under the MIT License. You’re free to use, modify, or distribute the code as per the license terms.

## Contact
Created by kskaman. For any questions or suggestions, feel free to reach out via the GitHub repository.
