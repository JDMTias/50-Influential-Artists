# Sprint Challenge: Advanced CSS and Intro to JavaScript - Influential Artists

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a concrete project. This Sprint explored Advanced CSS and JavaScript fundamentals. During this Sprint, you studied studied preprocessing, variable declaration, conditionals, loops, functions, arrays, and objects. In your challenge this week, you will demonstrate proficiency by creating a website for artisits with data from a `JSON` object.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your TL if you need direction. Your work reflects your proficiency in Preprocessing, and JavaScript Basics.

> You have **three hours** to complete this challenge. Plan your time accordingly.

## Introduction

In this challenge, you will use a data set of influential artists to build a "influential artists" webpage. This data comes from a set of "50 influential artists" on [kaggle](https://www.kaggle.com/ikarus777/best-artworks-of-all-time). We have reduced the data to just 20 artists to make it slightly easier to work with. You can work with the full dataset as a stretch goal.

### Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons) and your team lead.

## Self-Study Questions

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your project manager

1. How would you describe preprocessing to someone new to CSS?

It allows you to create variables and code that you can re use over and over again without having to maybe write down the specifics. It also allows you to make changes without having to re-write your code, you can just change the variables and it will automatically update the entire code. Preprocessing also makes you code easier to read with nesting, it also makes it a lot smaller, since you won't have to re-write things. 

2. What is your favorite concept in preprocessing? What is the concept that gives you the most trouble?
 My favorite is the ability to nest it makes things so much easier also mixins, what gives me the most trouble is probably accesibility, or media queries. 


3. How would you explain the concept of a variable to someone new to programming?

Variable is just like you learned in math it is something that can be given value to. For example the Pythagorean Theorem a^2+b^2=c^2 we know that each letter is a variable to a side of a triangle and the legth of the triangle is then measured and put into a or b or c therefore giving the variable a value. 


4. What is the purpose of using functions in code?
 Functions allows the developer to repeat sections of code with just a single line, its like a mini program. For example a For loop. instead of me writing console log of something 100 times, I can just write a for loop with a limit of a 100 and with a single line it will repeat itself 100 times. 


5. What is a JSON data?

Json stands for JavaScript Object Notation, it is a lightwheight format of data that is eady to read and write for humans as well as machines. Its what we use to write JavaScript with. 



You may need to look up an answer but, you are expected to be able to answer all these questions. Your responses contribute to your Sprint Challenge grade. Skipping this section *will* prevent you from passing this challenge.

## Instructions

### Task 1: Project and Pre-processer Set Up

Follow these steps to set up your project:

#### Git Set up

- [x ] Create a forked copy of this project.
- [x ] Add your Team Lead as collaborator on Github.
- [ x] Clone your OWN version of the repository (Not Lambda's by mistake!).
- [ x] Create a new branch: git checkout -b `<firstName-lastName>`.

#### Preprocessor Set up

* [x ] Verify that you have LESS installed correctly by running `lessc -v` in your terminal, if you don't get a version message back, reach out to your project manager for help.
* [ x] In your project's root folder, run the following command `less-watch-compiler less css index.less`
* [ x] Verify your compiler is working correctly by changing the `background-color` on the `body` selector to `red` in your `index.less` file.
* [x ] Once you see the red screen, you can delete that style and you're ready to start on the next task

### Task 2a:  Minimum Viable Product - PreProcessing

#### Import LESS Files

* [x ] Navigate to your `index.less` file. Notice the file is blank. You have been asked to use a certain import order. That order is as follows:

```markdown
    1.variables.less
    2.mixins.less
    3.reset.less
    4.general.less
    5.navigation.less
    6.main.less
    7.cta.less
```

_You will know everything is working properly when you see the styles enabled for the provided content._  

#### Home Page - Desktop HTML & LESS

* [x] Take 10 minutes to review the code that has already been provided for you. Take time to see how the home page was built.
* [X] Add a viewport meta tag to the head of your index.html page
* [X] [Review the provided home desktop design file](design/Desktop.png). You are to build the missing navigation system and header image. You have been provided all content necessary in the [index.html file](index.html)
* [X] Navigation Styles: Use the `navigation.less` file for styling.
* [ !] Main Content Styles: Use the `main.less` file for styling
* [X] LESS Mixins: Create and use 2 different mixins to aid your styling. Use the `mixins.less` file for your mixins
* [X ] LESS Parametric Mixin: create a parametric mixin that is used to create the `contact us` button styles.
* [X ] Use at least 2 parameters to create your button
* [ ] Create a hover state that changes the opacity of images to 80%
* [ ] Use good coding practices including adding responsive breakpoints to your code with media queries

### Task 2b: Minimum Viable Product - JavaScript

Navigate to `index.js` and complete the MVP challenges. Note that you need to scroll past data (or collapse data in VScode) to find the challenges.

### Task 3: Stretch Problems

After finishing your required elements, you can push your work further. These goals may or may not be things you have learned in this module but they build on the material you just studied. Time allowing, stretch your limits and see if you can deliver on the following optional goals, also listed in `index.js`, where applicable:

* [ ] Use JavaScript to programmatically create HTML elements in the console and copy them to display all 20 artists on the page
* [ ] Create a function called `randomize` that takes a data array as an argument and returns a the same array in a randomized order.
* [ ] Use advanced array methods (.map, .reduce, .filer) to refactor your MVP code (create an array of all artists born in the 1900s with .filter, for example)
* [ ] Add responsive breakpoints to your code by using media queries
* [ ] Add CSS animations

## Resources

📚[Best Practices for Responsive Design](https://www.browserstack.com/guide/responsive-design-breakpoints)

🤝[W3 Schools - Responsive Design](https://www.w3schools.com/html/html_responsive.asp)

👀 [Styling with HTML and CSS](https://www.w3schools.com/html/html_css.asp)

## Submission format

Follow these steps for completing your project.

- [ ] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's  Repo). **Please don't merge your own pull request**
- [ ] Add your team lead as a reviewer on the pull-request
- [ ] Your team lead will count the project as complete by merging the branch back into master
