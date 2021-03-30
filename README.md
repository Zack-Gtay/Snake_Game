# Snake_Game

1- We create a grid (kind of (simulating it)) -> every time we move we have to move by the amount of 40 pixels
2- the Snake is going to be a list with different positions, each of these positions is block and we're going to update each of the block in a certain direction and then we are drawing the block and that gives us a snake
3- MOVING THE SNAKE: the head is moved to a new block - the block before the head gets the position where the head used to be - Each block is moved to the position of the block that used to be before it (this deletes the last block)
