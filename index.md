
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles/styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Raleway&display=swap" rel="stylesheet">
    <script src="scripts/script.js" defer></script>
    <title>Document</title>
</head>

<body>
    <h1>Kym's Tic Tac Toe Game</h1>
    <div class="board" id="board">
        <div class="cell" data-cell></div>
        <div class="cell" data-cell></div>
        <div class="cell" data-cell></div>
        <div class="cell" data-cell></div>
        <div class="cell" data-cell></div>
        <div class="cell" data-cell></div>
        <div class="cell" data-cell></div>
        <div class="cell" data-cell></div>
        <div class="cell" data-cell></div>
    </div>
    <div class="winning-message" id="winningMessage">
        <div data-winning-message-text></div>
        <button id="restartButton">Restart</button>
    </div>

    <div class="instructions">
        <ol>
            <li>The game is played on a grid that's 3 squares by 3 squares.</li>
            <li>You are X, your friend is O. Players take turns putting their marks in empty squares.</li>
            <li>The first player to get 3 of her marks in a row (up, down, across, or diagonally) is the winner.</li>
            <li>When all 9 squares are full, the game is over.</li>
        </ol>
    </div>
</body>

</html>
