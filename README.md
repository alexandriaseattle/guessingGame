##Guessing game

I decided to write a guessing game based off of a couple toungue twisters. 

I started off by prompting the user to answer how much wood Mr.Woodchuck needs in order to purchase a seashell from Sally, for his friend Cindy. The user then determines an appropriate amount of wood (A number from 1-10) in order to purchase a seashell. 

I used a variable that I named "intro" to prompt the user this question and depending on their answer, would return 1 of 3 responses, or, alerts. I used the "if/else if/else" method to convey the conditions.

I *did* , however, run into a problem when trying to pair the number that the user chose with the appropriate alert. I would get a random number generated with the 'Math.random' command, but I had not correctly assigned the variable. 

After I made a second variable with the name "wood" that held the 'Math.floor(Math.random())' and made it equal to var 'intro ' 's condition , I was able to have the correct alert appear with the given numbers from the user. 

![Celebrate](http://seattlesportsnet.files.wordpress.com/2013/11/stephen-colbert-celebration-gif.gif)