# project2
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Tic Tac Toe</title>
  <link rel="stylesheet" href="pro1.css" />
</head>
<body>
  <h1>Tic Tac Toe</h1>
  <div class="board" id="board"></div>
  <p id="status">Player X's turn</p>
  <button onclick="resetGame()">Restart</button>

  <script src="pro.js"></script>
</body>
</html>



css (pro1.css)
body {
  font-family: Arial, sans-serif;
  text-align: center;
  padding: 30px;
  background: yellow;
}

h1 {
  margin-bottom: 20px;
}

.board {
  display: grid;
  grid-template-columns: repeat(3, 100px);
  grid-gap: 5px;
  justify-content: center;
  margin: 0 auto 20px;
}

.cell {
  width: 100px;
  height: 100px;
  background: white;
  border: 2px solid #333;
  font-size: 2rem;
  cursor: pointer;
  display: flex;
  align-items: center;
  justify-content: center;
}

.cell:hover {
  background-color: red;
}

button {
  padding: 10px 20px;
  font-size: 16px;
  cursor: pointer;
}


Javascript (pro.js)

body {
  font-family: Arial, sans-serif;
  text-align: center;
  padding: 30px;
  background: yellow;
}

h1 {
  margin-bottom: 20px;
}

.board {
  display: grid;
  grid-template-columns: repeat(3, 100px);
  grid-gap: 5px;
  justify-content: center;
  margin: 0 auto 20px;
}

.cell {
  width: 100px;
  height: 100px;
  background: white;
  border: 2px solid #333;
  font-size: 2rem;
  cursor: pointer;
  display: flex;
  align-items: center;
  justify-content: center;
}

.cell:hover {
  background-color: red;
}

button {
  padding: 10px 20px;
  font-size: 16px;
  cursor: pointer;
}


