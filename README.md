# Pair Programming Project 1

* A program generates a random number between 1 and 100 and stores it.
* Ask the user to guess for a number between 1 and 100.
* If the number is correct, the user is congratulated!
* If the number is not correct, the user is told that their guess was too high or too low. 
* The program keeps asking until the correct guess is entered and then outputs “Well done!” and the number of guesses it took. 

This line of code will produce a random number between 1 & 100. To do this it generates a random number between  0 and 1, times it by 100, adds 1 and rounds (floors) it down. 

```js
let randNum = Math.floor(Math.random()*100+1);
```

## Even Better If (EBI)

* Can your solution be refactored?
* Is it clean? Is it readable? Is it maintainable?
* Could you add the functionality where only three guesses are allowed?
* Anything else? Be creative!