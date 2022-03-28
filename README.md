# Pre-work - *LIGHT & SOUND*

**LIGHT & SOUND** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Mythreya Vangapandu**

Time spent: **6.5** hours spent in total

Link to project: https://glitch.com/edit/#!/html-simon

## Required Functionality

The following **required** functionality is complete:

* [✅] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [✅] "Start" button toggles between "Start" and "Stop" when clicked. 
* [✅] Game buttons each light up and play a sound when clicked. 
* [✅] Computer plays back sequence of clues including sound and visual cue for each button
* [✅] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [✅] User wins the game after guessing a complete pattern
* [✅] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [✅] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [✅] Buttons use a pitch (frequency) other than the ones in the tutorial
* [✅] More than 4 functional game buttons
* [✅] Playback speeds up on each turn
* [✅] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [✅] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [✅] Help button (?) created to toggle display of game directions
- [✅] Buttons darken on hover

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](gif1-link-here)
![](gif2-link-here)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions

### 1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

For this project, I primarily relied on my existing knowledge of HTML and CSS. I also referenced HTML documentation from 
[W3schools.com](https://www.w3schools.com/) and utilized [Stack Overflow](https://stackoverflow.com) when I ran into unfamiliar error messages.

### 2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
In the past few months, I have coded almost exclusively with React Native for web development, which utilizes components built with JSX (an extension to JavaScript). Because the syntaxes of
JSX and HTML/CSS are similar, I found myself making syntax errors in my code. For example, React Native styling properties 
use camelCase (e.g. backgroundColor) for style properties while CSS uses dashed case (e.g. background-color). This was initially frustrating because the
differences were so miniscule it would often take me an extra minute to find what the error was. I overcame this challenge by reminding myself to use
a dash betweeen words in property names and double-checking with other existing style components in the file. 

Another obstacle I ran into was centering and margins. For a long time I did not fully understand the difference between 
all of the different "align" and "justify" properties. I would be unsure of when and where to reference each property, and 
would play around with each until it looked right. In order to better understand what I was doing, I had 
[this image](https://pbs.twimg.com/media/ExBNameVgAElLBh.jpg) open in a separate window as reference while I was coding.

At first, I did not fully understand the difference between classes and ids in HTML, as I was using them somewhat interchangebly. This was 
until I realized that id is for identifying specific elements, while classes are for general class of objects in the document.

While all of these challenges initially slowed down my progress on the project, I stuck with the problems I ran into and stayed patient.
In the end, I found that I learned a lot about HTML, CSS, and especially JavaScript. I'm grateful that this has been more than 
a surface level refresher of my knowledge and challenged what I thought I understood.
### 3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
* What kind of visuals and color themes do users respond well to on websites?
* What are some common design choices to avoid that make the user's experience worse?
* Are there any existing packages for web development that would be helpful for creating visually pleasing components?
* What sort of things should a developer keep in mind as the functionality of a website increases?
* What does collaboration on large-scale projects look like in professional settings?
* What sort of creative liberties are permitted to a developer when putting together a website for a corporation?
* How is more complex logic managed with JavaScript?
* How can a young developer get better at working with backend frameworks?


### 4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
* I think a very interesting feature to work on would be the **timer** that sets a limited amount of time every time the clue sequence is 
played. I would need to figure exactly where to put it in the script, but I cannot imagine the styling would be too complicated as I would
place it right next to the directions button.
* Another feature I was considering was a **custom pop-up box** that displays the winning and losing messages instead of the default boxes. I 
would design them to look like the other boxes in the project.
* I would add a **pause button**, which would temporarily stop the game and resume after the user hits play
* I would add three **different game modes**, which would be increasingly difficult. I would make the game go faster each mode and increase 
the number of buttons present on the screen.
* I would add a feature that would allow the user to **choose the symbols on each button** as well as the color. 
* I would make the tones that each button plays is a **chord** instead of an individual note.

## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright Mythreya Vangapanu

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

