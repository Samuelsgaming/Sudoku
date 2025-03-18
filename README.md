<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sudoku Game</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="sudoku-container">
        <h1>Sudoku Game</h1>
        <div class="grid">
            <!-- 81 Sudoku cells (9x9 grid) -->
            <!-- Create 81 cells with an input for user to fill -->
            <div class="cell"><input type="number" min="1" max="9"></div>
            <div class="cell"><input type="number" min="1" max="9"></div>
            <div class="cell"><input type="number" min="1" max="9"></div>
            <!-- Repeat this div 81 times to create a 9x9 grid -->
            <!-- Here, you can continue creating 81 cells -->
        </div>
        <div class="buttons">
            <button id="checkBtn">Check</button>
            <button id="resetBtn">Reset</button>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
