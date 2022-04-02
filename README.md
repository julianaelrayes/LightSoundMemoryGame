# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Juliana El Rayes**

Time spent: **3** hours spent in total

Link to project: https://glitch.com/edit/#!/innovative-neat-bottom

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [x] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [x]  User has a limited amount of time (5 minutes) to finish the game
- [x]  User can see a countdown timer on the screen when the game starts

## Video Walkthrough (GIF)

![](https://i.imgur.com/C20IduA.gif)

![](https://i.imgur.com/mWIvrYY.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
    - To help me create a random number multiple times in JS: https://stackoverflow.com/questions/68627930/create-a-random-number-multiple-times-in-js]
    - To help me hide images: https://stackoverflow.com/questions/1999071/show-hide-image-on-click

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

- I encountered some challenges when trying to upload the images inside the buttons. After finding the images I wanted to use and uploading them to the assets folder, I did not know how to implement them inside my buttons. I first tried adding the images tags inside the body but that just added the images outside the buttons. To solve this issue I first started analyzing the code I already had and then I thought about putting these tags inside each button tag. This almost worked for me. By now I had a box with a blue question mark inside each button. After, I started researching on the internet to see how other people implemented images in their code. I realized that instead of calling the folder of assets I could use each of the links for the images. This worked well. Finally, my last issue was the size of the images. I solved this problem by playing with the width and height until I got the desired look for my game.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

- After completing this submission, I started thinking about how could I upload future projects that I am planning to work on. I wonder how would I be able to upload this without needing another platform. After doing some research to complete my code, I came to read about HTTP and how it connects us and our website request to the remote server that houses all website data. I would love to know more about these rules and how does the framework work. I would like to get deep into the subject to better understand web development. Also, I would like to learn more about what CMS is and how it is different from a site builder. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

- If I had had more time to work on this project, I could have used it to complete more additional features. I would have made my game buttons sound like one of the Among Us songs so my game would be more harmonical. Also, I would have made the images of the characters appear only when the buttons are clicked instead of just changing the colors. After, I would have made the timer last about 15 seconds on each turn instead of 5 minutes. This would automatically reset after the user guess correctly. Finally, I would have tried to make my game somehow different from others. I would have tried to think outside the box and implement new ideas into the game.



## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright Juliana El Rayes

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

