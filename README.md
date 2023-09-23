# Rock, Paper, Scissors

[Live webpage](https://pp3-rps-ad0039afcece.herokuapp.com/)

![Mockup image](/assets/testing/readme-images/am-i-responsive.png)

## Project Overview

Rock, Paper, Scissors is a classic game  that challenges users against the computer in winning through their selections. 

They are asked to enter their username and followed by their first choice. The game will continue to ask the player their choices until the either the player or the computer reaches 3 wins. At which point, the program will ask the user if they want to play again.


### User Experience

#### Design

- #### ***Font Colour***

- The content is made up of three colours:
  - Green #28a745
  - Purple #6b006b
  - White #FFFFFF

  - The Green #28a745 was chosen as it is associated with football.
  - The Purple #6b006b was chosen as being similar to the the color scheme used by the Premier League website itself. I had chosen a slightly lighter purple in comparison as I felt the darker purple did not contrast well with the shade of Green I chose.
  - Both colors together with the white contrasts really well helping user experience.

- #### ***Typography***

  - The font syles of Lisu Bosa for the main body text and "Barriecito" for the headings works well together and represents the intention of the quiz. 
  - The "Barriecito" in particular works well as it gives off a "quizicle" style.


## Flowchart

Using Lucidchart I was able to design my game before building it. It allowed me to draw up an basic layout and flow that I wanted to include.

![Mockup image](/assets/images/flowchard.png)


## Features

- Username entry.
- "One-page" website.
- Prompt to choose first selection
- Prompts to continue choosing selections until first player to score three wins
- Once the score has reached three, message will appear advising the winner
- User will be asked if they want to play again.

#### Welcome 

![Mockup image](/assets/images/welcome.png)

#### First Selection

![Mockup image](/assets/images/first.selection.png)

#### Result Page

![Mockup image](/assets)

## Technologies Used

### Languages

- HTML

- CSS3

- JavaScript

- Python

### Frameworks, Libraries & Other Resources

1. [Google Fonts:](https://fonts.google.com/)
    - Google Fonts was used to import fonts into the style.css file.

1. [Font Awesome:](https://fontawesome.com/)
    - Font Awesome provideds small graphics to complement the logo and various headers.

1. [Git:](https://git-scm.com/)
    - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.

1. [GitHub:](https://github.com/)
    - GitHub used to store the code whoch was pushed from Git.

1. [Balsamiq:](https://balsamiq.com/)
    - Lucidchart was used to design the wireframes



## Validator Testing

[W3C Markup Validator](https://validator.w3.org/) was used to HTML code.

    - [HTML](/assets/testing/validation-pdf/html-validation.pdf)


[W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) was used to validate CSS code.

    - [CSS](/assets/testing/validation-pdf/css-validation.pdf)


[WAVE Testing](https://chrome.google.com/webstore/detail/wave-evaluation-tool/jbbplnpkjmmeebjpijfedlgcdilocofh) was used to test accessibility of website. No errors were found other than empty form label - this is intended as I am using placeholder text for instruction and visually more attractive without a label.


[JS Hint](https://jshint.com/) was used to validate JavaScript code.

    - [JavaScript](assets/testing/validation-pdf/js-hint-validation-result.pdf)


## User Testing

- Feedback from user testing was postive.
- Reviews suggested that:
    - the website was easy to navigate
    - the colors worked well together
    - the layout and structure of the questions made the intention clear
    - would benefit from a scorecard saving previous user scores
    - more questions

- The webiste worked efficently and without issue across laptop, tablet and mobile phone devices.


## Performance

Using Google Lighthouse within Google Chrome Developer Tools I was able to test the performance, accessibility, best practice and SEO. Overall performance could be improved which I will look at in future updates.

The results shown below:

![Mockup image](/assets/testing/readme-images/performance.png)

## Bugs

- The alert for when no username has been entered and the "Kick-Off" button is pressed does not appear. I have tested this on several browsers and re-written the code but at this time, no fix is in place. I have tested this while ensuring pop-up blockers are disabled but this has not resolved the issue.
  
- The question container resizes depending on length of question being asked. Code would need to be we-written to maintain constant size and for the question text to wrap within the container.

## Future Implementations

- Scoreboard where previous users and their scores are saved which would add further competitivness to the quiz.
  
- Investigate the usage of an API to generate a larger bucket of questions and randomise the questions on each turn
  
- Add animation for when user logs in and also when their final result is revealed, for example, a football being kicked.

## Deployment

### Github pages

The project was deployed to GitHub Pages using the following steps:

1. Log in to GitHub and locate [Premier League Quizzers](https://github.com/raccodes09/ci-pp2-project).
1. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
1. Scroll down the Settings page until you locate the "GitHub Pages" Section.
1. Under "Source", click the dropdown called "None" and select "Main".
1. The page will automatically refresh.
1. Scroll back down through the page to locate the now published site link in the "GitHub Pages" section.

### Forking the GitHub Repository

By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps:

1. Log in to GitHub and locate [Premier League Quizzers](https://github.com/raccodes09/ci-pp2-project).
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone

1. Log in to GitHub and locate [Premier League Quizzers](https://github.com/raccodes09/ci-pp2-project).
2. Under the repository name, click "Clone or download".
3. To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type git clone, and then paste the URL you copied in Step 3.
7. Press Enter. Your local clone will be created.

The live link can be found here - [Live webpage](https://raccodes09.github.io/ci-pp2-project/)

## Credits

### Content

- Code from social media links was taken from CI Love Running project.

- [CSS Tricks](https://css-tricks.com/) Information and code from articles in CSS Tricks regarding media queries and a fixed header.

- [W3Schools](https://www.w3schools.com/) Information on having the questions dynamically appear.

- [Stack Overflow](https://stackoverflow.com/) Assisted with concatenating the questions/options.

- Deployment section of README.md provided by a combination of CI's template and generic template on slack.

- Information for the questions based on the PRemier League history came from various sources, mainly the official Premier League website.

### Media

Tab icon provided by [favicon.cc](https://www.favicon.cc/?action=search&keywords=football/)

## Acknowledgements

The Slack community for asking questions that I didn't know I needed to ask and providing valuable help throughout.

Tutors and Student support from Code Institute - very helpful and understanding throughout the course.
