# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Christopher Esquivel**

Time spent: **6** hours spent in total

Link to project: https://glitch.com/edit/#!/nutritious-cliff-cat

## Required Functionality

The following **required** functionality is complete:

* [X] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [X] "Start" button toggles between "Start" and "Stop" when clicked. 
* [X] Game buttons each light up and play a sound when clicked. 
* [X] Computer plays back sequence of clues including sound and visual cue for each button
* [X] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [X] User wins the game after guessing a complete pattern
* [X] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [X] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [X] Buttons use a pitch (frequency) other than the ones in the tutorial
* [X] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [X] Computer picks a different pattern each time the game is played
* [X] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](http://g.recordit.co/TTpTdIRL1q.gif)
![](http://g.recordit.co/P4UySBRyTO.gif)
![](http://g.recordit.co/Ut8p3EqRqV.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
https://stackoverflow.com/questions/40858456/how-to-display-a-javascript-var-in-html-body (To display the variable playerLives to the screen)
https://www.w3schools.com/jsref/jsref_push.asp (some information on arrays in javascript)
https://www.tutorialspoint.com/in-javascript-how-to-empty-an-array (more information on arrays)
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random (information about the Math class used to generate the random pattern)

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
A challenge I encountered was coming up with the logic for the game. This is my first project using HTML, CSS, and Javascript. I had a tough time when working on the guess function. At first, to check if the user clicked the right button, I was checking for btn == pattern[progress]. Based on the pattern from the demo, when I ran the program, the first turn worked fine, second turn as well but then the third did not work. It always failed at the third turn. After debugging it with a few console.log statements, I realized I was using the wrong index. So, I fixed it and now it checks for btn == pattern[guessCount]. It took me about 10 minutes to solve this. What helped me go through this was taking a piece of paper and a pencil and go through the code step by step, keeping track of the variables being used. This is what I do every time I am stuck with a problem. I also like to explain what my code is supposed to do out loud. It helps me catch any logical mistake I have made. Since I have zero experience with HTML, CSS, and Javascript, I depended on the demo and google. For instance, I wanted to display the variable playerLives to the screen. I used "onload=getLives()" and the span tag

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
The questions I have after completing this assignment are: How would an expert implement the same game? How can a web developer memorize all those keywords used in HTML and CSS? How is the work of web development professionals similar to this project? What improvements can be done to my code? What other technologies could have been used to implement this game?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had a few more hours to work on the project, I would have spent them adding more features, such as a timer, personalized buttons and sounds. Keep track of the player's score and add different game modes. One in which two buttons light up at the same time, but one of them is fake. A faster game mode. Another in which after each turn, it changes the color of the buttons. I would probably need more than a few more hours to implement all this. My current understanding of HTML, CSS, and Javascript is not that great. I barely know the basics, but I hope this internship can teach me everything I need to know to work for a company as a web developer. 



## Interview Recording URL Link

[My 5-minute Interview Recording](https://youtu.be/KuqDRm2Hb3Y)


## License

    Copyright [Christopher Esquivel]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
