This is the first Javascript program I made for a class assignment. I was quite proud of it at the time. The project can be viewed here:
https://jonathandiep.github.io/simon-says/

###Minimum Game Requirements
Use the HTML/CSS from assignment #2. The page should be fully responsive and render correctly in at least one browser (Firefox or Chrome).
Addon functionality (using JavaScript)
1. Click the start button (center button)
2. Capture time
3. Generate random interval in milliseconds
4. Select random container (top, right, bottom, left)
5. At random interval, change background color of random container to grey
6. When the container changes color, the player should click the button associated with that container
    a. If the correct button is selected:
        i. Capture the time
        ii. Calculate the difference between start and stop
        iii. Using alert(), show the player their reaction time
    b. If an incorrect button is selected:
        i. Using alert(), tell the player that their selection is incorrect and to play again.

###Bonus Tier One (+20% points)
Add to the minimum functionality:
1. Randomly select a sequence of container changes (up, down, right...or left, bottom, up for example)
2. Change associated containers in that sequence (not all at once!)
3. Track player button selection (players should click the associated buttons in the correct sequence)
    a. If the correct sequence is selected, use alert() to tell the player.
    b. If an incorrect sequence is selected, use alert() to tell the player.

###Bonus Tier Two (+40% points)
Add to the bonus tier one:
1. The sequence of random container changes should progressive get more difficult.
2. Round one should have one container change to grey while round ten should have a 10 color change sequence.
3. That means you need to:
    a. keep track of round numbers
    b. keep track of container & button sequences
    c. manage color state per container (to get a 5 container sequence you need to flip one container from its original color, to gray, back to original.
4. Use alert() again to communicate correct || incorrect plays.
