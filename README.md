<h1>Survival Maths</h1>
Survival Maths is a maths game that requires the user to choose whether the second number generated to the screen in higher or lower than the first. The user initially has 3 lives, that can be detracted from by 0.5 increments if an incorrect answer is chosen. The user has a chance to earn back lives in 0.25 increments for every correct answer chosen. The user can also keep track of their high score, which will update and save every time the top score is beaten and the game is reset. 
<br>
The purpose of this game is to test the user's number comprehension, in this case it is the ability to understand the relation between two random numbers. The concept of the lives is included to add an element of urgency and motivation to get the questions right because their in-game health is at risk. It prevents the user from spamming a button to achieve a high score, or make random guesses. 
<br>
The high score is shown to the user to foster a sense of competitiveness, so they would want to play the game again in order to top the existing high score. As a result, the increased gameplay would improve their number comprehension. However, to prevent the game from feeling monotonous, the score limit is capped at 30 and the game will end once the user reaches this score.
<br>
<img src="assets/images/multi_device_mock_up.png" alt="Responsive Mockup">
<h2>Colour Palette</h2>
The colours I used were in the same colour group yet highly contrasting to make sure that the user's attention is not taken away from the game with any other distracting colour choices. I kept the number of different colours used to two so that the page did not look too busy. 
<img src="assets/images/colour_palette.png" alt="Colour palette showing blue and light cyan">
<br>
<h2>Features</h2>
<strong>Heading</strong>
<br>
I added the game's name as a heading with 3 font awesome icons as the game logo, a heart (representing the users lives) trapped between greater and less than signs.
<br>
<img src="assets/images/header.png" alt="The text 'Survival Maths' with a greater than sign, a heart and a less than sign next to each other to form a logo">
<br>
<strong>Description</strong>
<br>
I added a description of the game and its rules so that the user is clear on how the game operates.
<img src="assets/images/description.png" alt="Text explaining how the game works">
<br>
<strong>Game Area</strong>
<br>
In the game area, I added a dotted border to the game area to keep the user's attention focused on this area once the game had begun. It also breaks up the page to give a clear indication of when the game area starts and the description ends. I created buttons, using the same colour scheme as the rest of the page for consistency, to allow the user to make the guesses 'Higher' & 'Lower', as well as a reset button to allow the user to start the game over with a new set of lives and a cleared score. The user is also able to track how many lives they have as this is being reflected at the top of the game area.
<br>
<img src="assets/images/game_area.png" alt="A screenshot of the game area">
<br>
<strong>Results Area</strong>
<br>
I applied the same styling to the result area to keep the game feeling consistent. However, once the user has depleted their lives, the game area is hidden and the result area is finally shown. In the result area, I made sure to include the score that the user achieved in their most recent round, the high score and a button to reset the game so that the user is taken back to the game area.
<br>
<img src="assets/images/results.png" alt="A screenshot of the results area that highlights how the game area is now hidden">
<br>
<h2>Testing</h2>
Testing across different browsers
<br>
<h2>Validator Testing</h2>
<ul>
<li>HTML Validation</li>
No errors were found when I passed my code through the official <a href="https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-maths%2F#textarea">W3C validator</a>.
<br>
<li>CSS Validation</li>
One error was found when I passed my code through the official. <a href="https://jigsaw.w3.org/css-validator/#validate_by_input">Jigsaw validator</a>.
<br>
<img src="assets/images/css_validator.png" alt="A screenshot of the CSS validator flagging an unecessary 'font-family' in the styling code">
<br>
In order to fix this issue, I simply looked at line 41 and took out the duplication of 'font-family:' from the code.
<li>JavaScript Validation</li>
I ran my code through the official <a href="https://jshint.com/">JSHint validator</a>:
<ul>
<li>There are 7 functions in this file.</li>
<li>Function with the largest signature take 2 arguments, while the median is 1.</li>
<li>Largest function has 18 statements in it, while the median is 1.</li>
<li>The most complex function has a cyclomatic complexity value of 5 while the median is 1.</li>
<li>I had 15 warnings that I felt were not an issue that affected the webpage</li>
<li>JSHint flagged one undefine variable 'result', which I left as it was due to the fact that attempting to define the variable with let 'let' caused more issues.</li>
<li>'buttonClicked' abd 'resetScore' were listed as two unused variables, which does not cause issues to the functionality of my code, so I left this as it was.</li>
</ul>
<li>Accessibility</li>

</ul>

<h2>Features for the future</h2>

To add more levels that increase the difficulty. For example, both of the maths formulas could either be multiplication, divison, addition or subtraction. This would mean that the user would have to figure out the sum of for both of the quesitons in the limited time before they disappear from the screen.

<h2>Deployment</h2>
I deployed the site to GitHub by accessing the repository I had created for the project, going into settings and choosing the main branch to deploy from in the Pages section. Any edits I made since the deployment had been committed to the repository.

<h2>Resources and Credits</h2>
<ul>
<li>Spencer Barriball - How to use async functions and time-outs, as well as the initial idea for the user's lives.</li> 
<li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random">Mozilla.org</a> - How to implement the max random number code.</li>
<li>Fontawesome - for the use of icons in the heading and the lives title.</li>
</ul>
