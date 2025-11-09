# Rock Paper Scissors Game

<p>This program is a simple interactive game written in HTML, CSS, and JavaScript. 
It allows the user to play Rock Paper Scissors against the computer while demonstrating 
key programming concepts such as user input, randomization, conditionals, list, selection, and functions with parameters.</p>

<br>

<p>**Purpose**</p>
<p>The purpose of this program is to show how JavaScript can be used to make a webpage interactive. 
It also demonstrates how to connect user actions, such as button clicks and key presses, to game logic and multimedia elements like sounds and images. It also shows how to personalize user experience through greetings that depend on the current time and user input.</p>

<br>

<p>**Inputs**</p>
<p>- User enters their name through a prompt when the page loads.</p> 
<p>- User can click the <b>“Change Name”</b> button to enter a new name at any time.</p>
<p>- The program automatically checks the current time of day (morning, afternoon, or evening) using the computer’s system clock.</p> 
<p>- User clicks the <b>“Play Game”</b> button or presses the <b>“S”</b> key to start a round of Rock Paper Scissors.</p> 
<p>- User enters “rock,” “paper,” or “scissors” in a prompt to make a move.</p> <p>- Keyboard inputs and mouse clicks also trigger different sound effects.</p>

<br>

<p>**Outputs**</p>
<p>-A personalized greeting is displayed on the page, such as <i>“Good afternoon, Alex! Welcome to the Rock Paper Scissors game!”</i></p> 
<p>- The current player name is shown and updated dynamically whenever the name changes.</p> 
<p>- The result of each game (win, lose, or draw) is displayed as text below the game area.</p> 
<p>- An image representing the result appears: a <b>cake</b> for a win, <b>coal</b> for a loss, and a <b>glass bead</b> for a draw.</p> 
<p>- Background sounds and key-press effects play to enhance interactivity.</p> <br>

<br>

<p>**Function with Parameters Example**</p>
<p>The program includes a parameterized function that updates the personalized greeting depending on both the user’s name and the time of day:</p> 
<pre> function greet(username, time) { const greetingtext = `Good ${time}, ${username}! Welcome to the Rock Paper Scissors game!`; document.getElementById('greeting').textContent = greetingtext; } </pre> 
<p><b>Parameters:</b></p> 
<p>- <b>username</b>: The current player’s name, entered by the user.</p> 
<p>- <b>time</b>: The time of day (“morning,” “afternoon,” or “evening”) calculated from the system clock.</p> <p>This function demonstrates how parameters can dynamically change webpage content based on real-time data and user input.</p> 

<br>

<p>**Additional JavaScript Concepts Demonstrated**</p>
<p>- <b>Event Listeners:</b> Used to detect button clicks and key presses (for playing sounds, starting the game, or renaming the player).</p> 
<p>- <b>DOM Manipulation:</b> Elements such as text, images, and results are updated dynamically through <code>document.getElementById()</code>.</p> 
<p>- <b>Conditional Statements:</b> Used to determine the time of day and the winner of each round.</p> 
<p>- <b>Randomization:</b> The computer’s choice is selected randomly from rock, paper, or scissors.</p> 
<p>- <b>Multimedia Integration:</b> Audio effects play on key events to enhance user experience.</p> 

<br>


<p>**How to Use**</p>
<p>1. Open the HTML file in a browser.</p> 
<p>2. Enter your name when prompted. The page will greet you based on the current time (e.g., morning or evening).</p> 
<p>3. Click <b>“Play Game”</b> or press <b>“S”</b> to begin.</p> 
<p>4. Enter <i>rock</i>, <i>paper</i>, or <i>scissors</i> in the prompt window.</p> 
<p>5. View the game result and image that appear below.</p> 
<p>6. Use <b>“Change Name”</b> at any time to update your player name and greeting instantly.</p>
