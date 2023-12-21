## **Exquizite**

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

Home Page

![Home page preview](documentation/docimg/exquizitehomepreview.png)

- The user is greeted with a simple starting page which provides two clear options, to play the quiz or view the high scores.

Highscores

![Highscores preview - no scores showing](documentation/docimg/hsnoscores.png)

![Highscores preview - with scores showing](documentation/docimg/hswithscores.png)

- The highscores page features a list of the top five highest scores recorded to date along with the relevant users name, sorted from the highest at the top to the lowest at the bottom.
- If no highscores have been recorded, the message stating that no hire scores are present is shown.

Choosing the topic and difficulty

![Topic and difficulty select](documentation/docimg/categorydifficulty.png)

- Once the user starts a new quiz, they are presented with two dropdown menus to choose the quiz topic and difficulty. Once they click the submit button, the quiz begins showing them the first of six questions based on what they have chosen.

Quiz area

![Quiz area start](documentation/docimg/quizareastart.png)

![Quiz area with correct choice](documentation/docimg/quizareacorrect2.png)

![Quiz area with incorrect choice](documentation/docimg/quizareaincorrect2.png)

- The quiz area itself has a few features, including:
  - A progress bar which automatically fills up proportionately based on the question number the user is currently on. This keeps the user informed as to how far into the quiz they currently are, plus when it will end.
  - A score feature, which shows the users current score based on the number of questions they have got right so far.
  - The question itself, which is different for each question asked by the quiz.
  - Four multiple choice answers for the user to choose from. If they select the correct answer, the box highlights green to indicate it is correct. If they select one of the three incorrect answers, the box highlights red to indicate an incorrect choice. Once the user chooses an answer and they receive their feedback, the quiz automatically moves onto the next question until they reach the end, at which point they are directed to the end page.

End page

![End page](documentation/docimg/endpage.png)

- The end page has a few features:
  - Firstly, the users final score is shown at the top to let them know how they did.
  - They are then given the opportunity to enter their name and save their score, which enters their result along with their name into the highscores. The save score button is disabled until they enter their name, the user cannot submit with an empty name.
  - There is a play again button which restarts the quiz if they wish to play again.
  - There is also a go home button which takes the user back to the home page.

404 Error

![404 error message](documentation/docimg/404error.png)

- This page was put in place in case a page cannot be found, to stop the user from seeing the generic 404 page provided by the browser.

## **Future Enhancements**

- The high scores leaderboard could be improved in the future to store scores on a server rather than on local storage, which will open the quiz up to more competition in future.
- An additional dropdown menu could be added to the game page allowing the user to choose the number of questions they want to answer, allowing them to customise the quiz further.
- Functionality could be introduced in future to create levels which the user can progress through. To pass to the next level they would have to reach a certain quiz score, and each level is more difficult than the last.

## **Testing Phase**

### **Responsiveness**

Responsiveness was checked and worked as intended with the following browsers and screen sizes:

- Extra Large (27" Mac Desktop):

  - Chrome (120.0.6099.109 Official Build x86_64)
  - Safari (Version 17.2.1 19617.1.17.11.12)
  - Firefox (Version 121.0 64-bit)

- Large (15" MacBook Pro Laptop):

  - Chrome (120.0.6099.109 Official Build x86_64)
  - Firefox (121.0 64-bit)
  - Safari (Version 17.2 17617.1.17.11.11, 17617)

- Medium (10.9" iPad):

  - Chrome
  - Safari
  - Firefox

- Small (6" iPhone 13):

  - Chrome (120.0.6099.119)
  - Safari
  - Firefox (120.4 36613)

DevTools was also used to check the responsiveness at various screen sizes and devices from the list of devices available. All were fully responsive and caused no issues.

### **Functionality**

Home Page: When you enter the website, you're greeted with the logo and two buttons. Clicking the logo should simply refresh the page as it navigates to index.html, clicking start quiz should start the quiz and clicking high scores should navigate to the high scores page. All tests returned the expected results.

Game Page: Once a topic and difficulty is chosen, and the user clicks the submit button, they should be directed to the quiz itself where the first of six questions should be waiting for them, in the topic and difficulty they selected. Once the questions have loaded, the question counter should display Question 1/6 and the score should be 0. Once a user selects an answer, if it's correct it should highlight green, the score should be increased by 10 and the question counter should move to 2/6. If the answer choice is incorrect, the box should highlight red, the score should not change but the question counter should move to 2/6. Once the user has answered six questions, they should be directed to the end page. DevTools and console logs were used to confirm that the chosen topic and difficulty were being fetched correctly from the API. All tests returned the expected results.

End Page: The final score shown should match the score shown after answering the last question, just before the end page appears. If the user has not yet entered their name, they should not be able to save their score. If they have, they should be able to save their score, which then directs them back to the home page. If the user saves their score, this should be recorded in local storage and therefore appear on the high scores page. Clicking play again should start a new game, the go home button should take the user back to the index page. All tests returned the expected results.

High Scores: This should show all of the high scores recorded in local storage. If no high scores are recorded, the message telling the user that no high scores are present should appear instead. If multiple high scores are present, the website should sort all of them in order, with the highest score showing first. Only the top 5 scores should be shown. All tests returned the expected results.

404 Error: If any attempt is made to navigate to a page on the website which doesn't exist, the 404.html page should be shown automatically. After entering a page name at the end of the websites URL which doesn't exist, the 404 page appeared so this test returned the expected result.

Spam Clicks: Every page was tested with spam clicks, by clicking as many buttons, links and features as possible in a very short period, in an effort to try and break the website, but this returned no bugs or errors.

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
  - Problem: When trying to start the quiz straight away without changing the default dropdown options for topic and difficulty choice, the quiz does not start, instead it jumps straight to the end page.
  - Cause: The difficulty select was causing the issue, as the browser couldn't determine the actual value until it was physically selected by the user.
  - Solution: The game.js file was updated to allow the browser to class 'easy' as a difficulty even if it wasn't physcially clicked/selected by the user. So if they try to start the quiz with the default options, the quiz still starts.

- Loading spinner
  - Problem: The loading spinner is showing at the bottom left corner of the game screen along with the topic and difficulty select boxes, when it should appear in the middle of the screen instead of the difficulty and topic select boxes until the API has fetched the relevant data.
  - Cause: The hide class was not included in the game.html file for the categorySelect ID element.
  - Solution: The hide class was added, plus the relevant code in game.js to remove the hide class once the categories are fetched correctly. This was done using the categoryContainer variable which is linked to the categorySelect ID element.

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

The Exquizite logo was created and designed thanks to [logo.com](https://logo.com/), the free logo generator.# **Exquizite**
