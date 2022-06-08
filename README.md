# sudoku-solver
Building out a Sudoku Solver grid using JavaScript and allow users to enter the digits that they see on their own Sudoku puzzles that they want to solve.

Initially I used an API to solve the game. Later on, I noticed that we can use backtracking algorithm to solve for a sudoku board.
The algorithm is in backtracking.py 

There is up and down arrow to adjust the number in the board. Once finish, click solve to see the result!
<img width="461" alt="Screen Shot 2022-06-07 at 10 14 02 PM" src="https://user-images.githubusercontent.com/90353674/172516574-418781c3-de71-4bb8-a550-79363d0e735f.png">

For instance, this input is a solvable sudoku

<img width="467" alt="Screen Shot 2022-06-07 at 10 16 03 PM" src="https://user-images.githubusercontent.com/90353674/172516956-3e89dc7a-b7d9-4e0d-a0c4-e9e496864129.png">

After clicking solve, this is the result.

<img width="467" alt="Screen Shot 2022-06-07 at 10 16 15 PM" src="https://user-images.githubusercontent.com/90353674/172516997-2f9071ed-c00b-4b12-8def-7a0ec8ba2a29.png">

This application can also notices unsolvable sudoku

<img width="462" alt="Screen Shot 2022-06-07 at 10 16 33 PM" src="https://user-images.githubusercontent.com/90353674/172517090-a3dd1fc6-8c7a-4141-b728-a39be17e7f52.png">

# Build
```npm install```

# Run
```nodemon server.js```


Run the app live on your computer to start. Enjoy!
