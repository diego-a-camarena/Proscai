
<h1 align="left">Hey 👋 What's up?</h1>

###

<h2 align="left">Description</h2>

###

<p align="left">The purpose of this challenge is to find a word such that when entered into a hash function it returns the following value: 15338399087375.</p>

###

<h2 align="left">Resolution</h2>

<p align="left">After analyzing the challenge, I came to the conclusion that the best way to find the word would be to create a function that could decrypt the hash function.</p>

<p align="left">The first step was to analyze the algorithm inside the hash function</p>

<p align="left">So if we want to find a function that decrypts the hashed value in theory we would have to find a function that does the opposite operations to the hash function..</p>

<p align="left">The most complex part of the algorithm is the part where the dictionary index is added, since this is a variable value.</p>

<p align="left">To find the solution we have the advantage that the multiplication is done with a constant number, so we would then have to find the relationship between the number of times this constant number is multiplied and the sum that is done at the end.</p>

<p align="left">So I found that the relationship is that if the module is taken from the initial input using the constant (19) the result is close to 0.5 for each position in which the character is found within the dictionary..</p>

<p align="left">So once we know what logic exists, it is possible to build the decrypt function.</p>

###

<p align="left">Output:<br>descubrir</p>

###

<p align="left">The time it took me to find the logic was approximately 20 minutes and 10 more minutes to do it in code</p>

###

<p align="left">Inside the repository is the code of the function to find the answer to this exercise</p>
