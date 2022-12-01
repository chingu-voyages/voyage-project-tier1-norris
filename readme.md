# Chingu Solo Project - Tier 1 - Chingu Trivia - for Product Owners

## Overview

As a Product Owner this project is a great opportunity to demonstrate your 
organization skills to help a team who will develop this clean and modern 
webpage. 

You are currently on the **Tier 1 repo** and this Solo Project is only for 
Product Owners **not** Developers. You'll be responsible for creating User 
Stories from the requirements listed below (see [Instructions](#instructions)). 

As you increase your Product Owner skills and experience you'll be able to 
come back to this project and enhance it for the Tier 2 and 3 versions of 
it. Ultimately you'll have a great portfolio piece to share with interviewers.
## About Chingu

If you aren’t yet a member of Chingu we invite you to join us. We help our 
members transform what they’ve learned in courses & tutorials into the 
practical experience employers need and want.

Our remote team projects let you refine your technical skills and put them 
into practice while gaining new “soft” skills like communication, 
collaboration, and Agile project management. The types of skills that 
help real-world teams get things done!

You can learn more and join us at [chingu.io](https://chingu.io).

## Instructions

General instructions for all Pre-Work Projects can also be found in the 
Chingu Voyage Handbook (URL posted in the `#read-me-first` channel on Discord). 
You can also find more information about the User Stories 
[here](https://www.notion.so/Agile-Methodology-101-1894ac9115304fe7a9586c6c7d594470)

### What You Need to Do

Your task for this Solo Project is to **_create Users Stories and/or tasks_** 
for requirements in the [Structure](#structure) and 
[Functionality](#functionality) sections below. Feel free to add questions or 
additional comments in the User Stories that you think would be helpful to 
team members working on it.

> Remember your task for this Solo Project is to create User Stories from 
the [Requirements](#requirements), **_not_** to create a working version of 
the app!

You may create your User Stories and tasks as text file or in the tool of your 
choice (like ZenHub, Notion, Trello, etc.). Remember that you don't neet to 
worry about technical details. What's important is to demonstrate your ability 
to create a set of tasks a team could follow to build the app.

#### Requirements

*Structure*

- [ ] Header item that includes the name for the app, and tabs (if using)
- [ ] Card that displays a trivia question and four multiple choice answers
- [ ] Place element that displays which question number the user is on and the total number of questions (ex. 'Question 1 / 10')
- [ ] Display buttons for advancing to the next question once the current question has been answered
- [ ] Display a message to the user that informs them if their answer was right or wrong
- [ ] Display a clear message to the user when the trivia session is done, and include the user's score

*Styling:*

- [ ] Styles should be reminiscent of the demo versions. Feel free to use artistic licencse as long as the functionality doesn't suffer 

*Functionality*

- [ ] The quiz should span at least 10 questions. Feel free to add more if you would like.
- [ ] The page should not reload! Hardcode all of your questions/choices in your JS file and use DOM manipulation to insert text as you go
- [ ] An array of questions/choices can be found in the `assets` folder of this repo *(filename is 'quizQuestions.js')*; feel free to copy/paste the array in your JS file

*Upon Load:*

- [ ] Load the first question and display the user's place as *Question 1 / 10*
- [ ] Make sure the button used to advance questions is either not visible or not clickable until an answer is submitted

*Considerations:*

- [ ] Try and style your app so that it doesn't overflow the viewport (require scrolling) on any device
- [ ] Make sure your User Experience design is intuitive (buttons are clearly disabled when not available, messages are clear, etc)
- [ ] In the name of responsiveness: please try and have your answer buttons (or divs, or whatever you use) collapse into a column in small sizes (iPhone5, etc)

*Other:*

- [ ] Your repo needs to have a robust README.md
- [ ] Make sure that there are no errors in the developer console before submitting

**Extras (Not Required)**

- [ ] Make your design fully responsive *(small/large/portrait/landscape, etc.)*
- [ ] Offer the user the ability to navigate to previous questions
- [ ] Play with formats for user interaction: drag 'n drop vs. click, etc.

## Example

![](./assets/chingu_trivia.gif)