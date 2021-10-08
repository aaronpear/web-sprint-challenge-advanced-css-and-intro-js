# Sprint Challenge: Advanced CSS and Intro to JavaScript - Influential Artists

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a concrete project. This Sprint explored advanced CSS and introductory JavaScript concepts. During this Sprint, you studied responsive web design, variable declaration, conditionals, loops, functions, arrays, and objects. In your challenge this week, you will demonstrate proficiency by creating a website of influential artists with data from an object.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. Your work reflects your proficiency in Responsive Design, and JavaScript Basics.


## Introduction

In this challenge, you will use a data set of artists to build an "influential artists" webpage. This data comes from a set of "50 influential artists" on [Kaggle](https://www.kaggle.com/ikarus777/best-artworks-of-all-time). We have reduced the data to just 20 artists to make it slightly easier to work with.

### Commits

Commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question.)

Please answer the following questions below, you may edit the readme file to include your answers below the question.

1. How would you describe accessibility on the web to someone new to programming?

    Creating something accessible on the web in large means creating something that can be accessed and neatly presented through
    many different devices: desktops, laptops, phones, tablets, etc., as well as accommodating those who may speak different languages
    or have various disabilities, though that is for the most part not within the scope of this project. This in turn means that us
    as developers need to determine when, where, and how to implement varying levels of responsive design in our work depending on the
    needs of the client.

2. Talk about 3 different things you can do to ensure your website is accessible. 

    It is best practice to use responsive rather than fixed units as much as possible when coding in CSS in order to account for
    varying screen sizes and viewports, or more specifically for key breakpoints for devices that are the most popularly used.
    You should also always keep in mind to keep your HTML as semantic as possible while retaining a structure and flow of the site
    that makes sense, which includes using classes and ids meaningfully and efficiently. This is not only for other developers to more easily read your code, but also for screen readers to more easily read your code to further support those with disabilities.
    After considering all of the basis of your code and building a foundation that you and others can easily work upon, you can then focus on some smaller aspects of your project to further increase accessibility such as consistently utilizing meaningful alt text for images can help for when images do not load or for those who are visually impaired, or using appropriately contrasting colors of
    font in comparison to its background to ensure legibility or maybe to support those with something like color-blindedness.


3. How would you explain the concept of a variable to someone new to programming?

    Variables are a crucial part of programming; you could not reasonably build anything without them if at all. That said, variables in the context of programming act as placeholders for values that we would want to use later in our code. For example, if I worked at a restaurant and wanted to print out the check for a table of 10 people, we would have presumably saved all their items that they've ordered into our system in some form of variable which we can then print out with one button rather than us having to manually remember and calculate the cost of each individual item. This same idea works exactly the same when one part of our code might want to refer back to other variables that we've created before; the data is saved for when we need to use it. Variables can also take different shapes and forms to further organize the process. They might just be a simple number, maybe a string of words, or they might take more complicated forms that can hold, organize, and manipulate data like arrays or objects.

4. What is the purpose of using functions in code?

    Generally, we use functions in code to carry out processes that we need to be repeated in our code to reduce redundancy and make the coding process exponentially more efficient. Instead of writing out a block of code that iterates through an array of objects to retrieve a specific key-value pair every single time we want that piece of data, we would create a function that executes the code needed to grab that point of data whenever we would need to do so.

5. How do you access a key inside of an object inside of an array?

    array[index].key -- or array[index]['key'] if the key holds any spaces or special characters

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Project Set-Up

Follow these steps to set up your project:

1. Fork the repo
2. Go into canvas and connect your reop to codegrade
3. Clone your forked version of the repo
4. DO NOT CREATE A BRANCH. You will be pushing your changes to the main/master today
NOTE: tests will run in the JavaScript portion of this challenge only.
5. cd into your repo
6. open the terminal in your vs code and type `npm install`
7. next type `npm run test` in your terminal
8. Complete your work making regular commits to main/ master your codegrade score will update each time you make a push.


### Testing & Debugging

Open a second terminal inside of your project by clicking on the split terminal icon
![alt text](assets/split_terminal.png "Split Terminal")

Inside of your second terminal type `npm start` 
![alt text](assets/npm_start.png "type npm start")

You will be running your tests in one terminal and debugging in the other. As you work on your code you should make use of `console.log` to check your progress and debug.
![alt text](assets/tests_debug_terminal_final.png "your terminal should look like this")

### Task 2a:  Minimum Viable Product - Responsive Design

*Before you jump in, take 10 minutes to review the code that has already been provided for you. Take time to see how the home page was built. During this time, [Review the provided design files](design/). You have been provided all content necessary in the [index.html file](index.html) and basic styling in the [index.css file](css/index.css).*

* [ ] Ensure your website is responsive at 500px such that your styles match the [mobile design file](design/Mobile.png).

### Task 2b: Minimum Viable Product - JavaScript

Navigate to `index.js` and complete the MVP challenges. Note that you need to scroll past data (or collapse data in VScode) to find the challenges below.



## Resources

📚[Best Practices for Responsive Design](https://www.browserstack.com/guide/responsive-design-breakpoints)

🤝[W3 Schools - Responsive Design](https://www.w3schools.com/html/html_responsive.asp)

👀 [Styling with HTML and CSS](https://www.w3schools.com/html/html_css.asp)

🦄 [Sprint Challenge Study Guide](https://www.notion.so/lambdaschool/Unit-1-Sprint-2-Study-Guide-16f656025c8744458addb068e6348101)





