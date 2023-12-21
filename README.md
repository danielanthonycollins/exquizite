# **Exquizite**

[View the live project here](https://danielanthonycollins.github.io/exquizite/)

![Website shown on multiple devices](documentation/docimg/exquizitedevicepreview.png)

## **Site Overview**

Exquizite is an online quiz game featuring multiple choice questions in the users topic and difficulty of choice. The target audience is quiz enthusiasts, quiz teams looking to practice before an event or anyone looking to pass the time with a fun game.

## **Table of contents**

- [**Exquizite**](#exquizite)
  - [**Site Overview**](#site-overview)
  - [**Table of contents**](#table-of-contents)
  - [**Planning stage**](#planning-stage)
    - [**Target Audiences**](#target-audiences)
    - [**User Stories**](#user-stories)
    - [**Site Aims**](#site-aims)
    - [**Wireframes**](#wireframes)
    - [**Color Scheme**](#color-scheme)
  - [**Typography**](#typography)
  - [**Features**](#features)
    - [Home Page:](#home-page)
    - [Highscores:](#highscores)
    - [Choosing the topic and difficulty](#choosing-the-topic-and-difficulty)
    - [Quiz area](#quiz-area)
    - [End page](#end-page)
  - [**Future Enhancements**](#future-enhancements)
  - [**Testing Phase**](#testing-phase)
    - [**Responsiveness**](#responsiveness)
    - [**Functionality**](#functionality)
    - [**Validators**](#validators)
    - [**Lighthouse**](#lighthouse)
    - [**Testing user stories**](#testing-user-stories)
  - [**Bugs**](#bugs)
  - [**Deployment**](#deployment)
  - [**Tech**](#tech)
  - [**Credits**](#credits)
    - [**Honourable mentions**](#honourable-mentions)
    - [**Content**](#content)
    - [**Media**](#media)

## **Planning stage**

### **Target Audiences**

- Casual users looking for a quiz game to pass the time.
- Quiz enthusiasts and/or teams looking to test their knowledge before a competition.
- Casual users looking for a fun game to entertain guests at a party or gathering.

### **User Stories**

- As a user, I want the site to be easy to use.
- As a user, I want to the site to be responsive.
- As a user, I want to choose the topic for the quiz questions
- As a user, I want to answer different questions each time I take the quiz, even if I choose the same topic.

### **Site Aims**

- To offer a simple, yet interesting quiz game that can be played multiple times without repetition of questions to keep the users engaged.
- To offer multiple topics, creating the largest possible target audience.
- To keep the user informed on their progress as they advance through the quiz.
- To display a leaderboard so users can compare their results with others, hopefully encouraging them to keep playing or come back and try again at a later time.

### **Wireframes**

Home Page (Desktop, Tablet & Mobile)

![Home Page Wireframe](documentation/wireframes/homedesktopwireframe.png)

Game Page - Select Topic (Desktop, Tablet & Mobile

![Game Page - Topic Wireframe](documentation/wireframes/topicdesktopwireframe.png)

Game Page - Questions (Desktop view shown, on tablet and mobile layout is to be the same although everything should wrap to the next line where required)

![Game Page - Questions Wireframe](documentation/wireframes/questiondesktopwireframe.png)

End Page with Final Score (Desktop, Tablet & Mobile)

![End Page with final score wireframe](documentation/wireframes/finalscoredesktopwireframe.png)

High Scores Page (Desktop, Tablet & Mobile)

![High scores page wireframe](documentation/wireframes/highscoresdesktopwireframe.png)

### **Color Scheme**

I decided to use a navy background with white text against the navy to jump out off the page, along with some brown features to match the icon in the logo. I think navy is a very modern, inviting color and a lot of apps and websites seem to be moving towards a darker theme with bright wording and features, rather than the other way around.

## **Typography**

I decided to use the Arial font as it's a simple and clear to read font which worked well with all of the features and also works with the font of the logo.

## **Features**

### Home Page:

![Home page preview](documentation/docimg/exquizitehomepreview.png)

- The user is greeted with a simple starting page which provides two clear options, to play the quiz or view the high scores.

### Highscores:

![Highscores preview - no scores showing](documentation/docimg/hsnoscores.png)

![Highscores preview - with scores showing](documentation/docimg/hswithscores.png)

- The highscores page features a list of the highest scores recorded to date along with the relevant users name, sorted from the highest at the top to the lowest at the bottom.
- If no highscores have been recorded, the message stating that no hire scores are present is shown.

### Choosing the topic and difficulty

![Topic and difficulty select](documentation/docimg/categorydifficulty.png)

- Once the user starts a new quiz, they are presented with two dropdown menus to choose the quiz topic and difficulty. Once they click the submit button, the quiz begins showing them the first of six questions based on what they have chosen.

### Quiz area

![Quiz area start](documentation/docimg/quizareastart.png)

![Quiz area with correct choice](documentation/docimg/quizareacorrect2.png)

![Quiz area with incorrect choice](documentation/docimg/quizareaincorrect2.png)

- The quiz area itself has a few features, including:
  - A progress bar which automatically fills up proportionately based on the question number the user is currently on. This keeps the user informed as to how far into the quiz they currently are, plus when it will end.
  - A score feature, which shows the users current score based on the number of questions they have got right so far.
  - The question itself, which is different for each question asked by the quiz.
  - Four multiple choice answers for the user to choose from. If they select the correct answer, the box highlights green to indicate it is correct. If they select one of the three incorrect answers, the box highlights red to indicate an incorrect choice. Once the user chooses an answer and they receive their feedback, the quiz automatically moves onto the next question until they reach the end, at which point they are directed to the end page.

### End page

![End page](documentation/docimg/endpage.png)

- The end page has a few features:
  - Firstly, the users final score is shown at the top to let them know how they did.
  - They are then given the opportunity to enter their name and save their score, which enters their result along with their name into the highscores. The save score button is disabled until they enter their name, the user cannot submit with an empty name.
  - There is a play again button which restarts the quiz if they wish to play again.
  - There is also a go home button which takes the user back to the home page.

## **Future Enhancements**

- The high scores leaderboard could be improved in the future to store scores on a server rather than on local storage, which will open the quiz up to more competition in future.
- An additional dropdown menu could be added to the game page allowing the user to choose the number of questions they want to answer, allowing them to customise the quiz further.
- Functionality could be introduced in future to create levels which the user can progress through. To pass to the next level they would have to reach a certain quiz score, and each level is more difficult than the last.

## **Testing Phase**

### **Responsiveness**

To be completed

### **Functionality**

To be completed

### **Validators**

To be completed

### **Lighthouse**

To be completed

### **Testing user stories**

**User story 1**: As a user, I want the site to be easy to use.

**Achieved?**: Yes. The quiz includes features and instructions which are clear to the user as they progress through the quiz and allows them to start and finish successfully.

**User story 2**: As a user, I want to the site to be responsive.

**Achieved?**: Yes. The quiz has been designed and tested to be responsive on all devices.

**User story 3**: As a user, I want to choose the topic for the quiz questions

**Achieved?**: Yes. The quiz prompts the user to select from a variety of topics before they begin.

**User story 4**: As a user, I want to answer different questions each time I take the quiz, even if I choose the same topic.

**Achieved?**: Yes. The quiz provides different questions for each game, even if the user plays multiple times choosing the same topic as they do so.

## **Bugs**

I found the following bugs during the development process:

- GitHub Pages
  - Problem: When the project was deployed to GitHub Pages and the start quiz button is clicked, a 404 page appeared saying the link was unknown.
  - Cause: After troubleshooting the issue on slack, I found that GitHub pages does not like absolute flle paths, which were included in my code to send the user to the relevant page based on the button clicked or action taken.
  - Solution: All file paths in all documents were changed to relative by removing the first forward slash.

- Easy difficulty issue
  - Problem: 
  - Cause: 
  - Solution: 

---

## **Deployment**

I deployed the page on GitHub pages via the following procedure:

1. From the project's [repository](https://github.com/danielanthonycollins/exquizite), go to the **Settings** tab.
2. From the left-hand menu, select the **Pages** tab.
3. Under the **Source** section, select **Deploy from a branch** and then the **Main** branch from the drop-down menu and click **Save**.
4. A message will be displayed to indicate a successful deployment to GitHub pages and provide the live link.

You can find the live site [here](https://danielanthonycollins.github.io/exquizite/)

---

## **Tech**

- HTML5
- CSS3
- JavaScript

## **Credits**

The following people, websites and learning materials aided me with the creation of this project.

### **Honourable mentions**

Special thanks to my mentor Richard Wells for his excellent advice and support throughout this project.

### **Content**

I used the [James Q Quick](https://youtu.be/rFWbAj40JrQ?si=lEENGptMdV2F396F) Youtube tutorial to create the base for my quiz.

I used the following [w3schools](https://www.w3schools.com/howto/howto_css_loader.asp) page to include the loading spinner in my project.

### **Media**

The Exquizite logo was created and designed thanks to [logo.com](https://logo.com/), the free logo generator.