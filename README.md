# Rock Paper Scissors Game

<p>This program is a fully functional Rock Paper Scissors game created with HTML, CSS, and JavaScript. It allows the user to compete against a computer opponent, producing accurate win, lose, or draw results. The program also integrates images, sounds, and dynamic text to create an interactive experience that responds to both mouse and keyboard inputs.</p> 

<br>

<p><b>Purpose</b></p>
<p>The purpose of this program is to demonstrate how JavaScript can make webpages interactive through user input, randomization, conditional logic, multimedia elements, and DOM manipulation. It shows how to link user actions, such as button clicks and key presses, to meaningful program responses while reinforcing the understanding of key programming structures and parameterized functions.</p> 

<br>

<p><b>Inputs</b></p>
<p>- User enters their name through a prompt when the webpage loads.</p> 
<p>- User can click the <b>“Change Name”</b> button to rename themselves at any time.</p> 
<p>- The program automatically detects the current time of day and displays a personalized greeting (“Good morning,” “Good afternoon,” or “Good evening”).</p> 
<p>- User starts the game by clicking the <b>“Play Game”</b> button or pressing the <b>“S”</b> key.</p> 
<p>- User selects their move by typing <i>rock</i>, <i>paper</i>, or <i>scissors</i> in a prompt.</p> 
<p>- Keyboard inputs such as the <b>Shift</b> key trigger sound effects.</p> 

<br>

<p><b>Outputs</b></p>
<p>- Personalized greeting text that changes based on both player name and time of day.</p> 
<p>- Game results displayed as text: <b>You win!</b>, <b>You lose!</b>, or <b>It’s a draw!</b></p> 
<p>- Corresponding images are displayed for each result: a <b>cake</b> for a win, <b>coal</b> for a loss, and a <b>glass bead</b> for a draw.</p> 
<p>- Multiple sound effects play during various interactions (button clicks, key presses, and game events).</p> 

<br>

<p><b>Game Logic and Programming Concepts</b></p>
<p>The core of the program is the <code>play_rps()</code> function, which implements the game’s logic using key programming concepts:</p> 
<p>- <b>List (Array):</b> A list of possible computer moves is stored in an array: <code>const computer_choices = ['rock', 'paper', 'scissors'];</code></p> 
<p>- <b>Selection (Conditional Statements):</b> The program uses <code>if</code> and <code>else if</code> statements to determine game outcomes and to detect the correct time of day for greetings.</p> 
<p>- <b>Iteration (Loop):</b> A <code>while</code> loop ensures valid player input by repeatedly prompting until the user enters “rock,” “paper,” or “scissors.”</p> 
<p>- <b>Accurate Win Conditions:</b> The conditional logic correctly determines whether the user wins, loses, or draws against the computer’s randomized move.</p> 

<br>

<p><b>Function with Parameter</b></p>
<p>The game includes a function that uses parameters to personalize greetings based on both the user’s name and the current time of day:</p> 
<pre> function greet(username, time) { const greetingtext = `Good ${time}, ${username}! Welcome to the Rock Paper Scissors game!`; document.getElementById('greeting').textContent = greetingtext; } </pre> 
<p><b>Parameters:</b></p> 
<p>- <b>username</b>: The name entered by the player.</p> 
<p>- <b>time</b>: The time of day (morning, afternoon, or evening) determined from the computer’s system clock.</p> <p>This demonstrates how a function with parameters can modify webpage content dynamically according to both user input and external data.</p>

<br>

<p><b>Multimedia and Interactivity</b></p>
<p>- <b>Images:</b> Each outcome is paired with a specific image (cake, coal, or glass bead) displayed on the screen.</p> 
<p>- <b>Sounds:</b> Three sound files play at different interaction points — when clicking buttons, pressing keys, or starting the game.</p> 
<p>- <b>Text Outputs:</b> Greeting, username, and game results update dynamically through DOM manipulation.</p> <p>- <b>Mouse and Keyboard Inputs:</b> Users can control the game using both the mouse (buttons) and keyboard (keys).</p> 

<br>

<p><b>How to Use</b></p>
<p>1. Open the HTML file in a browser.</p> 
<p>2. Enter your name when prompted; the page will greet you depending on the time of day.</p> 
<p>3. Click <b>“Play Game”</b> or press <b>“S”</b> to start a round.</p> 
<p>4. Enter <i>rock</i>, <i>paper</i>, or <i>scissors</i> when prompted.</p> 
<p>5. View the result, image, and text updates on the screen.</p> 
<p>6. Click <b>“Change Name”</b> to rename yourself and update your greeting instantly.</p> 


