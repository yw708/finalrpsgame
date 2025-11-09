# Rock Paper Scissors Game

<p>This program is a simple interactive game written in HTML, CSS, and JavaScript. 
It allows the user to play Rock Paper Scissors against the computer while demonstrating 
key programming concepts such as user input, randomization, conditionals, and functions with parameters.</p>

<br>

<p>**Purpose**</p>
<p>The purpose of this program is to show how JavaScript can be used to make a webpage interactive. 
It also demonstrates how to connect user actions, such as button clicks and key presses, to game logic and multimedia elements like sounds and images.</p>

<br>

<p>**Inputs**</p>
<p>- User enters their name through a prompt.</p>
<p>- User selects rock, paper, or scissors through a prompt.</p>
<p>- User clicks buttons to start the game or change their name.</p>
<p>- User can press specific keys to trigger sound effects.</p>

<br>

<p>**Outputs**</p>
<p>- The result of the game (win, lose, or draw) is displayed as text on the page.</p>
<p>- An image is shown to represent the outcome (cake, coal, or glass bead).</p>
<p>- Sounds are played when buttons are clicked or certain keys are pressed.</p>

<br>

<p>**Function with Parameters Example**</p>
<p>The program includes a function that takes in parameters and returns a calculated result.</p>

<pre>
function calculateScore(wins, losses, draws) {
  return (wins * 3) + (draws * 1) - (losses * 2);
}

calculateScore(2, 1, 1); // returns 5
</pre>

<p><b>Parameters:</b></p>
<p>- wins: number of times the player wins</p>
<p>- losses: number of times the player loses</p>
<p>- draws: number of times the game ends in a draw</p>

<p>This example demonstrates how parameters can be passed into a function and used to perform a calculation. 
It does not affect the Rock Paper Scissors gameplay but serves as a clear example of parameter usage.</p>

<br>

<p>**How to Use**</p>
<p>1. Open the HTML file in a browser.</p>
<p>2. Enter your name when prompted.</p>
<p>3. Click “Play Game” to start a round.</p>
<p>4. Enter rock, paper, or scissors in the prompt window.</p>
<p>5. View the result and image that appear on the screen.</p>
<p>6. Use “Change Name” to rename the player at any time.</p>

<br>

<p>**Documentation Types**</p>
<p>- <b>Comments</b>: Explain sections of the code for easier understanding.</p>
<p>- <b>Read Me</b>: Describes how the program works, how it is used, and the purpose of its design.</p>
