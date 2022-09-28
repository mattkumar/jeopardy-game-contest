# jeopardy-contest
R Studio Table Contest 2022

## About
This is my entry into the [R Studio 2022 Table Contest.](https://www.rstudio.com/blog/rstudio-table-contest-2022/) It uses Quarto, reactable and scss to style a Jeopardy! game board. </br>

You may view it [here.](https://mattkumar.quarto.pub/jeopardy-game-contest/)

## Aims
My aims for this project were three-fold:

1. To think about creative uses of tables! I'm not a particular fan of Jeopardy!, but this stood out when I was trying to think of things that are tabular/rectangle in nature.

2. Learn how to use some of `reactable`'s custom rendering capabilities

3. Continue to investigate and experiment (s)css and Quarto.

## Data
Data for the table are retrieved programmatically using the `whatr` package. See [here](https://github.com/kiernann/whatr) more for details.

## Features
The table is a faithful recreation (i.e. each cell is in the identical position it was when it aired on TV). Upon hovering on a given cell, the content will flip to provide a clue. Optionally, you can view the answer associated with this clue.

## Assets
The fonts `ITC Korinna Std Bold.woff` and `gyparody rg.woff` were downloaded from [here.](https://www.cdnfonts.com/) The image background used in the table header was downloaded from [here.](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRZHjBdKxdfv15GSsl7d6zvEiSJ_79orInqr3HQtwTMCN8CN-SSwaDwfXYzCzRZwx0LnqI&usqp=CAU) All other assets accessed or modified is documented in `custom.scss`.
