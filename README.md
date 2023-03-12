<!DOCTYPE html>
<html>
<head>
</head>
<body>
	<h1 align="center">Rock Paper Scissors Game</h1>

<p>This is a simple game of rock paper scissors implemented in Python. The game allows the user to select their choice of hand (rock, paper, or scissors) and plays against the computer, which also randomly selects a hand. The game then determines the winner based on the rules of rock paper scissors.</p>

<h2>How it works</h2>

<p>The game starts by displaying ASCII art representing the three hand choices (rock, paper, scissors). The game then prompts the user to enter their choice of hand. If the input is not valid, the game returns an "Invalid input!" message and exits. If the input is valid, the game generates a random hand for the computer.</p>

<p>Next, the game displays the user's and the computer's hand choices using ASCII art. Finally, the game determines the winner based on the rules of rock paper scissors and displays the result on the screen.</p>

<h2>Techniques Used</h2>

<ul>
	<li>ASCII art for displaying hand choices</li>
	<li>Dictionary data structure for mapping hand choices to their respective ASCII art</li>
	<li>Random module for generating the computer's hand choice</li>
	<li>Basic conditional statements for determining the winner</li>
</ul>

<h2>Example Output</h2>

<pre><code>
Enter your choice (rock, paper, or scissors): rock
You chose rock:
    _______
---'   ____)
      (_____)
      (_____)
      (____)
---.__(___)

Computer chose paper:
     _______
---'    ____)____
           ______)
          _______)
         _______)
---.__________)

You lost!
</code></pre>


<h2>Contributing</h2>

<p>Contributions are always welcome! If you have any suggestions or improvements, please feel free to open an issue or submit a pull request.</p>

<h2>License</h2>

<p>This program is licensed under the MIT License. See the <a href="LICENSE">LICENSE</a> file for details.</p>

</body>
</html>
