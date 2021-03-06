# Dwarf Match

[Dwarf Match](https://andy-osborne.github.io/Dwarf-Match/) is an interactive card matching game with a fantasy theme.

I have created this game to engage users of all ages, especially those who enjoy a medieval fantasy theme within their games. It has been designed so that it is easy to play, offers various difficulty levels to the user, flows easily from one section to the next and is fully responsive to the users chosen device.

The use of animations and music has been implemented to stimulate the users senses and aid in the users immersion as they play the game.

I have used HTML, CSS, [Bootstrap Framework](https://getbootstrap.com/) and JavaScript to build this and the game which will form part of my ongoing portfolio of work.

![Preview of Dwarf Match](https://res.cloudinary.com/andy-osborne/image/upload/v1587668012/Dwarf%20Match/Images/ResponsiveDesign_zhwquu.png)

## Demo

A live demo of the website can be found [here](https://andy-osborne.github.io/Dwarf-Match/).

## Table of Contents

1. [**UX**](#ux)
    - [**User Stories**](#user-stories)
    - [**Design choices**](#design-choices)
    - [**Wireframes**](#wireframes)
        - [Variation Between Wireframes and Final Product](#variation-between-wireframes-and-final-product)

2. [**Technologies Used**](#technologies-used)

3. [**Features**](#features)
    - [**Existing Features**](#existing-features)
    - [**Features To Be Implemented**](#features-to-be-implemented)

4. [**Testing**](#testing)
    - [**Code Validation**](#code-validation)
    - [**Manual Testing**](#manual-testing)

5. [**Deployment**](#deployment)
    - [**To Run Locally**](#to-run-locally)

6. [**Credits**](#credits)
    - [**Music and Sound Effects**](#music-and-sound-effects)
    - [**Images**](#images)
    - [**Code Credits**](#code-credits)
    - [**Learning Resources**](#learning-resources)
    - [**Acknowledgements**](#acknowledgements)

7. [**Disclaimer**](#disclaimer)

## __UX__

### User stories

As a user:

- I want the landing page to be visually appealing as this sets the standard for the rest of the website and will aid in the decision of whether I want to try the game or not.

- I want to be able to navigate myself around the site with ease and with as little guidance as necessary.

- I want to easily access the game, tutorial information if needed, and control the sounds coming from the website.

- I want to be able to choose the difficulty level of the game before I play and have an idea of what will change with each difficulty level.

- I want to be able to restart the game if necessary without having to go back to the home screen to do it.

- I want to be able to keep track of the amount of flips it has taken me to complete the game & the time taken to do so as this can give me a personal challenge to beat it on any further play-throughs.

- I want the card layout to be randomised so the front faces of the cards are not in the same position as previous games.

## Design Choices

### Colours

- **Navbar, Footer and Buttons** - I decided to use ``#422020``(Seal Brown) as this stood out well against the various background images used throughout the site. The colour had an earthy feel to me and suited the fantasy theme I was aiming for as this theme tends to use deeper and less vibrant colours.

- **Modals** - I decided to use ``#674134``(Metallic Copper) which is a lighter brown colour for the modals so it aids in it standing out and this colour doesn't get lost when displaying over the background images and it compliments the main colour used for the site.

- **Font Colour** - I decided to use ``#f5f5f5``(White Smoke) for the text as it compliments the brown colours used throughout the site.

- **Card** - I decided to use ``#d0cbcb``(Very Light Grey) for the background colour of the card faces as this stood out well against the game background images whilst still complimenting the overall design style of the game.

### Fonts

- [**Spicy Rice**](https://fonts.google.com/specimen/Spicy+Rice?query=spicy+rice) - I used this font for the site headers and menu buttons. I felt that it cursive feel to it that suited a fantasy theme that I was creating.

- [**Indie Flower**](https://fonts.google.com/specimen/Indie+Flower?query=indie) - I used this font for the text within modals as it had a great quirky feel to it that complimented Spicy Rice.

### Wireframes

- The wireframes for the initial layout of the website were created using [whimsical](https://whimsical.com/) and you can view the wireframes for Dwarf Match [here](https://github.com/Andy-Osborne/Dwarf-Match/tree/master/wireframes).

- The wireframes include a design layout for Desktop, Tablet - portrait and landscape, and Mobile - portrait and landscape.

- The colour scheme I had in mind when designing the mockups was not available on the site.

#### Variation Between Wireframes and Final Product

During the styling phase of the website I stuck to the original wireframe design however; after viewing it live I felt that it brought down the overall design level of the website. It is with this in mind, I did not use the following:

##### Landing Page

- I did not include the duplicate display of the site title as this was an error in the wireframe mockup.

#### Level Select Modal

- I did not include the images as displayed in the wireframe against each difficulty level as I felt it took away from the professionalism of the site and was not necessary to have.

#### Audio Control Modal

- I did not include a master sound control as after testing, I felt it was better to have the individual volume levels for music and sound effects that are controlled independently.

- I included two additions which was a ON/OFF button for the two different audios so the user can easily mute them without the need of fiddling with the slider.

## Technologies Used

1. [HTML](https://en.wikipedia.org/wiki/HTML) - This was used for the overall structure of the website.

2. [CSS](https://en.wikipedia.org/wiki/Cascading_Style_Sheets) - This was used for the overall and bespoke styling of elements on the website.

3. [JavaScript](https://en.wikipedia.org/wiki/JavaScript) - This was used to create overall logic of the game as well as controlling the modals, audio and buttons.

4. [Bootstrap Framework](https://getbootstrap.com/) - This was used to create the overall responsiveness of the website through the use of their flexible grid layout.

5. [Google Fonts](https://fonts.google.com/) - I used Google Fonts to obtain the fonts used on the website which are "Indie Flower" and "Spicy Rice".

6. [GitHub](https://github.com/) - I used to store my repository for the project and record all my commits.

7. [GitHub Pages](https://pages.github.com/) - I used to deploy my website.

8. [Gimp](https://www.gimp.org/) - I used this to edit the images from CraftPix and create images where required.

9. [Autoprefixer](https://autoprefixer.github.io/) - I used this project to make sure all CSS prefixes were used where required to ensure cross-browser compatibility.

10. [Visual Studio Code](https://code.visualstudio.com/) - I used this to write the code for my site.

11. [Cloudinary](https://cloudinary.com/) - I used this to host the background images and game music used as these files are larger in size than the card faces which are between 4KB - 6KB.

## Features

### Existing Features

Landing Page

- The landing page features an animated background of a forest that scrolls across the screen with the site title in the Navbar section and three buttons for the user to interact with.

- The simple approach was designed to not overload the user with various buttons and widgets when they visit the site and they can immediately fulfill their reasons for coming to the site - to play the game or find out how to play it.

- When the user clicks on a button, there is a sound effect which aids in their immersion on the site. They can easily turn the audio off through the use of the third button on the landing page as I felt that it was necessary to provide the user with easy access to audio controls as having sound effects and music is not to everyone's taste.

Navigation Bar

- The navigation bar on the page load contains the site title although once the user enters a game the site title disappears and is instead replaced by three buttons.

- The buttons displayed during a game are Tutorial, Sound Controls and Exit. This gives the user instant access to the three main actions they would want to do, other than playing the game.

- I decided on using images for the buttons to easily convoy their meaning without taking up too much head room within the navbar.

Sound Modal

- The sound modal allows the user to adjust the volume level for the music that is played during the game or the sound effects which are used throughout their journey on the site. The user can do this by using the slider.

- The user can completely disable sound and music by click on the ON/OFF button within the modal.

- These options work through the use of event listeners which then update the code accordingly.

Level Selection Modal

- The level selection modal offers the user three difficulty choices - Easy, Normal, or Hard. Underneath each option, there is a small text blurb that states how many cards and pairs are in each of those levels.

Victory Modal

- The victory modal launches after the user completes the level they were playing and plays a victory sound effect.

- This tells the user how many flips it took them to complete the game as well as how long it took them which a player can then use as their personal best then try to beat it.

- The other options within the modal is for the user to restart the level at the same difficulty, try the next difficulty level - this option does not appear if the user is currently playing at the hardest difficulty setting, or to exit the game and return to the landing page.

Game Area

- The game area has a responsive design which will adapt to the device the user is playing on and the orientation of the device.

- In the top right corner of the game area, there is a restart button that the user can click on to restart their game and reset the timer and counter.

- Upon game start/restart, the cards are all placed facedown and shuffled.

Game cards

- The game cards consist of up to 16 unique images that I obtained through my subscription to CraftPix. These images were resized so they all had a consistent size and would be contained correctly within the cards across all media devices.

- When a user clicks on a card that is facedown, the card face is revealed and a sound effect is played.

- Upon the user selecting two cards, if both cards match a matching sound is played, otherwise the facedown class is re-applied to the card.

Game Counter and Timer

- When a user plays a game, there is an active timer that starts the moment the user starts the game and continues until they complete it.

- Each flip of a card the user does is recorded within the flip counter and is displayed to the user.

### Features To Be Implemented

- I want to implement a 3D perspective to the game cards so that when a user clicks on them, the card visually rotates from the back face to the front face of the card.

- I want to implement the use of cacheStorage so that if a user disables the sound or music during their initial visit to the site, these settings will be retained and applied on their next visit to the site.

## Testing

### Code Validation

All code written has been thoroughly validated and passed through the following online validators:

- HTML - All code was run through the [W3C HTML Validator](https://validator.w3.org/) to ensure it was valid code and no errors were made.

- CSS - All styling was run through the [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) to ensure it was valid and no errors were made.

- JavaScript - All my script was run through the [JSHint](https://jshint.com/) validator and no errors were found.

### Manual Testing

You can view the testing done in the [test.md](https://github.com/Andy-Osborne/Dwarf-Match/blob/master/testing.md) where I have written in-depth on the various tests I have performed.

## Deployment

I developed this project using [Visual Studio Code](https://code.visualstudio.com/). Version control was done using git and hosting the repository was done through GitHub.

The live version of this site is hosted using GitHub Pages and is deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch. In order for the site to deploy correctly on GitHub pages, the landing page must be named `index.html`.

To deploy Dwarf Match from its [repository in GitHub](https://github.com/Andy-Osborne/Dwarf-Match), I completed the following steps:

1. Log into GitHub
2. From the list of repositories, select Andy-Osborne/Dwarf-Match.
3. Click on the settings button located just below the Fork option.
4. Scroll down the new page to GitHub Pages.
5. Select Master Branch from the dropdown menu.
6. After selecting Master Branch, the page will refresh and Dwarf Match is deployed.
7. If you scroll back down to the GitHub Pages section after the page refreshes, you can grab your live link to your deployed site.

### To Run Locally

If you wanted to run this project locally and not use GitHub Pages, you can follow these steps:

1. Go to the repository for [**Dwarf Match**](https://github.com/Andy-Osborne/Dwarf-Match).
2. Below the repository name, you will see a green button with the text **Clone or Download**.
3. Click on this button and a box will appear called **Clone with HTTPS**.
4. Copy this clone URL for the Dwarf Match repository.
5. In your local IDE, open **Git Bash**. Please check that **Git** has been installed in your IDE.
6. Change the **current** working directory to the location where you want the cloned directory to be made.
7. Type ``git clone`` and then paste in the URL you took from the **Clone with HTTPS** button.
    - An example of what the command would look like is below:

        ```git clone https://github.com/Andy-Osborne/Dwarf-Match.git```

8. You can cut ties with the original GitHub repository by typing in:

    - ``git remote rm origin``

## Credits

### Music and Sound Effects

1. The Royalty Free Music used for the game is titled "Adventure" by Alexander Nakarada. You can view his website [here](https://www.serpentsoundstudios.com). This work is licensed under a Creative Commons Attribution 4.0 International License.

2. All sound effects were obtained by [freesound](https://freesound.org/).
    - The sounds used for [clicking](https://freesound.org/people/LittleRobotSoundFactory/sounds/270393/) and the [victory sound](https://freesound.org/people/LittleRobotSoundFactory/sounds/270402) were created by user [LittleRobotSoundFactory](https://freesound.org/people/LittleRobotSoundFactory/). This work is licensed under a  Attribution 3.0 Unported (CC BY 3.0) Licence.

    - The sound used for the [card flip](https://freesound.org/people/Splashdust/sounds/84322/) was created by user [Splashdust](https://freesound.org/people/Splashdust/). I edited the sound to reduce the length of it as mentioned in the testing.md. This work is licensed under the Creative Commons 0 License.

    - The sound used for [card matching](https://freesound.org/people/deleted_user_3277771/sounds/176741/). I edited the sound to reduce the length of it as mentioned in the testing.md. I am unable to link it to the creator as they have deleted their account however; this work is licensed under the Creative Commons 0 License.

### Images

1. The images used in the game are from [CraftPix](https://craftpix.net/) which I hold a annual membership to. This allows me to:

    - Use, copy, adapt, modify, prepare derivative works based upon all purchased assets;

    - Use the game assets as many times as I like;

    - Sell and distribute games with their assets. **Which is not relevant to this as this was created for educational uses only**

2. The image used at the beginning of the README.md showing the responsive layouts was created using [Am I Responsive?](http://ami.responsivedesign.is/#).

### Code Credits

1. The shuffle method was obtained from [stackoverflow](https://stackoverflow.com/questions/2450954/how-to-randomize-shuffle-a-javascript-array).

2. The idea on how get the flowing CSS background animation was provided by the YouTuber Divinector's [video](https://www.youtube.com/watch?v=KWxclDkBJ00).

### Acknowledgements

A special thanks to:

- My Code Institute Mentor, [Precious Ijege](https://github.com/precious-ijege) for his support during the project.
- Code Institute Alumni, [Paul Friel](https://github.com/Spagettileg) for taking the time to review my code and providing feedback.

### Learning Resources

- Throughout my journey of creating this site, I was continuously learning and improving my knowledge and I used the following resources to achieve this:

- [Code Institute](https://codeinstitute.net/).

- [Codecademy](https://www.codecademy.com/).

- [Plurasight](https://www.pluralsight.com/).

- [w3schools](https://www.w3schools.com/).

## Disclaimer

This site has been created entirely for **educational purposes** only and is not intended to be used in any other capacity.
