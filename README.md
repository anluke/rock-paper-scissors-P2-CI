# ROCK PAPER SCISSORS

Idea came from a game called: **Rock Paper Scissors**. It is a hand game usually played between two people in which each player simultaneously forms one of three shapes with an outstretched hand. These shapes are "rock" (a closed fist), "paper" (a flat hand), and "scissors" (a fist with the index finger and middle finger extended, forming a V).  

This is a 2nd Milestone project for Code Institute. The purpose was to build a simple and effective site with good implementation of **JavaScript**. Very simple but functional.  
It was a perfect little project to use some of the JavaScript content covered so far.  

The live website can be found [here](link to webpage).


![Devices](picture across different devices)

<br />

## User Story

Target Audience for this game would be children aged from **5 - 10** years.  
The game should be played clearly across different devices and respond instantly.  
There is no time limit on the game itself.  

It's a fun way to interact with a computer and see who would win majority of rounds.



## Features

- __Rock Paper Scissors Heading__

    - Featured at the top of the page, the name of the game and heading is easy to see for the user.

![Title](https://github.com/anluke/rock-paper-scissors/blob/main/assets/images/readme_snips/title.png?raw=true)


<br>

- __The Game Area__  

    ![Game Area](https://github.com/anluke/rock-paper-scissors/blob/main/assets/images/readme_snips/game_section.png?raw=true)

    - This section will allow the user play the Rock Paper Scissors game.
  
    - The user will be able to select what hand gesture to go with and immediately find out the result of the game round.

    - Each of the elements are responsive and change color *(more on that below)*.


    <br>

- __Win Event__  

    ![Win](https://github.com/anluke/rock-paper-scissors/blob/main/assets/images/readme_snips/win.png?raw=true)

    - In the chance that the player wins the round, the winning hand will turn **green** and slightly increase in size while losing hand will turn **red** and slightly scale down.

    - This event will only last for 1 second. I thought about making the effect look longer but it would interfere with fast paced game.

    - Win event will also increment user's score by **1** and color change follows in the same manner for both the user and the computer.

    - There is also an announcement section that tells us who won the current round and elements chosen. In this case it was Rock that beat Scissors.

    <br>

- __Lose Event__  

    ![Lose](https://github.com/anluke/rock-paper-scissors/blob/main/assets/images/readme_snips/lose.png?raw=true)

    - In the chance that player loses the round, the hand will turn **red** and slightly decrease in size while computers winning hand will turn **green** and slightly scale up.

    - Lose event will keep our current score intact while only incrementing computer's current score.

    - Color change will follow in the same fashion as above **Win** function.

   

<br />

- __Draw Event__

    ![Draw](https://github.com/anluke/rock-paper-scissors/blob/main/assets/images/readme_snips/draw.png?raw=true)

    - If the even is draw the score will remain intact.

    - The hand will turn blue and announcement area will notify the player that both sides selected the same gesture.

    - Score at the bottom will remain the same.  

<br />

<br />

- __Score Section__

    ![Score](https://github.com/anluke/rock-paper-scissors/blob/main/assets/images/readme_snips/result_section.png?raw=true)

    - Score sections sits at the bottom of the page.

    - It holds two icons right just before the name that perfectly matches the type of player.

    - When the user wins, the score increments by **1** while turning color to green. *(displayed in the images above)*

    - Win event for the computer will follow in the same fashion and increment it's result by **1** while also changing color.

    - Losing the round will not affect the score. It will stay the same until next round is won.

<br />

## Testing

- I tested that this page works in different browsers: Chrome, Firefox, and Safari.

- The page is responsive and contains all the functions across different screen sizes using the dev tools device toolbar.

- I confirmed that header/navbar, hero, main-section, about, sign up and footer are all readable and easy to understand.

- I also confirm that submit form works: requires an entry in every field and also checks if a user has put a correct email address by checking the email address format.


### Bugs

- When I tested my page through **Multi Device Website Mockup Generator** I discovered a slight offset in the hero background image.  
While writing a Media Query for Laptop devices I had moved the background image left by ```-1 cm``` instead of moving it ```left``` to allow for better representation of the Hero background image.

```
  #hero {
    background-position-x: -1cm;
  }
```
 - Removing the ```-1 cm``` and replacing it with ```left``` attribute fixed the issue and got the Hero image to respond how I intended.


 ### Validator Testing

 - HTML
    - No errors were returned when passing through [W3C validator](https://validator.w3.org/nu/#textarea).

- CSS  
    - No errors were found when passing through the official [WRC(JigSaw) validator](https://jigsaw.w3.org/css-validator/validator).

- Validator Testing
    - I confirmed that the color palette and font is easy to read and accessible by running it through **Lighthouse** in devtools.

        ![Validator Test](https://github.com/anluke/candle-realm/blob/main/assets/readme-images/desktop-lighthouse.png?raw=true)

- JavaScript
    - No errors were found when passing the content of **script.js** file to JS Hint website:
    

### Unfixed Bugs

No reports of bugs as of now.

<br />

### Unfixed Bugs

## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows:
  - In the GitHub repository, navigate to Settings tab.
  - From the source section drop-down menu, select the Master Branch.
  - Once the master branch has been selected, the page provided the link to the completed website.

The live link can be found here: [Rock Paper Scissors]()

<br />

## Credits

- Content

    - The icons for the project were taken from [Font Awesome](https://fontawesome.com/).


- Code

    - Before starting the project I watched this video to kind of get the idea of how to implement it all in the best possible way. I ended up not complicating the code as I wanted to stay true to basics. The video was a great help though. It's from freeCodeCamp YouTube Channel [freeCodeCamp.org](https://www.youtube.com/watch?v=jaVNP3nIAv0).

 - Readme

    - For Readme file I used [CI P2 readme template](https://github.com/Code-Institute-Solutions/readme-love-maths/blob/master/README.md) as a general idea and built my project around similar layout.

    - For the intro at the top of the readme file I resorted to [WikiPedia](https://en.wikipedia.org/wiki/Rock_paper_scissors).