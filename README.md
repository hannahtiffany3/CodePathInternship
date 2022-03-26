# CodePathInternship
Memory Game Code for CodePath Internship

# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Hannah Tiffany**

Time spent: **8** hours spent in total

Link to project: 
Live site: https://coffee-bevel-plaster.glitch.me 
Code: https://glitch.com/edit/#!/coffee-bevel-plaster

## Required Functionality

The following **required** functionality is complete:

* [ ] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [ ] "Start" button toggles between "Start" and "Stop" when clicked. 
* [ ] Game buttons each light up and play a sound when clicked. 
* [ ] Computer plays back sequence of clues including sound and visual cue for each button
* [ ] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [ ] User wins the game after guessing a complete pattern
* [ ] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](https://github.com/hannahtiffany3/CodePathInternship/blob/main/Memory%20Game.gif)
![](gif2-link-here)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
I used Geeks for Geeks to help with uploading to GitHub. I also used W3 schools to learn about the rand() function to make my program produce a random pattern each time.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
The biggest challenge I encountered during this submission was creating random pattern. Although I could get it to work, I realized the would only generate a new pattern each time the game restarted, but not if I pressed the stop button and started again. After reviewing my code, I realized that I was initializing the pattern variable only at the beginning of the program, which meant that if I stopped and started the program, the pattern array would not be erased and updated. To fix this, I moved the code to create the array into the start fuction. Because this code runs each time the start button is pressed, it would recreate the pattern each time. Overcoming this problem required me to look at the code and dissect what it was doing. I have often found that coding requires you to look at each step of a program, one line of code at a time, and discern what that specific line is doing. Although it can take time, doing this is a great way to make sure you understand the code and the logic behind it.
The only other problem I encountered with the submission process was that I am not very familiar with GitHub. However, this problem was easy to overcome by doing research and using my resources. This is a skill that is also very applicable to computer science, as very few bugs in programs are unique. Being able to get help from peers or other resources helps cut down on the time it would have taken if you had tried to fix the code alone.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
I have very limited experience with web development, beyond a little PHP and playing around with JavaScript and HTML on my own. I took a databases class in which our final project required us to create our own database and connect it to a website using PHP. Our teacher gave us a skeleton program, but it had to be heavily modified in order to fit my project. Despite never having encountered PHP before, I was able to dissect the code enough to understand it and modify it to complete my project. I found that I was able to do the same thing with this project. Even though most of the code in this project was new to me, I understand what it does and I do not have any specific questions. However, I am very interested to learn more. I had a lot of fun implementing and teaching myself to understand the code that went into this project and I would like more opportunities to practice web development on my own.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
The biggest thing I would like to do is implement the feature that gives the user a limited amount of time to enter their guess. I am interested in this feature specifically because it would require using the system clock. I have used timers in other projects with C++, but I have limited experience with it and have never experienced it in JavaScript. I would be interested to do research on how to access and use the system clock in Java. I would also like to take the time to explore the different formatting options. Part of the reason why I love web building so much is the design element, and although it may seem secondary to having extra features, people are much more likely to be drawn to a simpler but well-designed website or game. I would like to take time to get familiar with all the different font and color options, as well as playing around with resizing, reshaping, and moving the position of the buttons.



## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright Hannah Tiffany

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
