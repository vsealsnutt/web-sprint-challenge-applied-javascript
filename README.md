# Applied JavaScript Sprint Challenge

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past sprint and apply them in a concrete project. This sprint explored **Applied JavaScript**. During this sprint, you studied **DOM and components**. In this challenge you will demonstrate your mastery of these skills by creating **an online Bloomtech newspaper**.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding sprint.

You are not allowed to collaborate during the sprint challenge.

### Project Set Up

- [ ] Create a forked copy of this project
- [ ] Clone your OWN version of the repository (Not BloomTech's by mistake!)
- [ ] Implement the project on the main branch, committing changes regularly
- [ ] Push commits: `git push origin main`

## Project Instructions

### Introduction

You are going to create a Bloomtech Newspaper. Your job is going to be to create the components that make up the newspaper's home page.

In meeting the minimum viable product (MVP) specifications listed below, your project should look similar to the image linked below:

[Bloomtech Times](https://github.com/bloominstituteoftechnology/web-sprint-challenge-applied-javascript/blob/main/Assets/bloomtech-times.png)

### Instructions

- [ ] Navigate to the root of the project with your command line.
- [ ] Run `npm install` to download the dependencies listed in the `package.json` file.
- [ ] Run `npm start` to compile the project and serve it.
- [ ] Navigate Chrome to `http://localhost:3000`
- [ ] In a separate terminal, run `npm test` to run tests.

**Steps Required for MVP:**

- [ ] Steps 1 and 2 are explained inside the `src/components/header.js` file.
- [ ] Steps 3 and 4 are explained inside the `src/components/tabs.js` file.
- [ ] Steps 5 and 6 are explained inside the `src/components/card.js` file.

**Important Notes:**

- Please **do not move or rename existing files** or folders.
- If your development server stops "auto reloading", manually kill it with `CTRL+C` and restart it.
- Do not change the `package.json` file except to install libraries with NPM (Axios is _already_ in the `package.json`).
- In your solution, it is essential that you follow best practices and produce clean and professional results.
- Schedule time to review, refine, and polish your work, including spell-checking and grammar-checking.
- It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Submission format

- [ ] Submit via Codegrade by committing and pushing any new changes to the *main* branch.
- [ ] Check Codegrade for automated feedback.

## Stretch Interview Questions

Demonstrate your understanding of this sprint's concepts by answering the following free-form questions. Edit this document to include your answers after each question.

1. What is the DOM?
    The DOM stands for the Document Object Model. The DOM represents the contents of an HTML document, and Javascriot can access the DOM in order to make a page more interactive.

2. What is an event?
    An event is an action that a user takes on a webpage, such as clicking, scrolling, zooming, using the keyboard, etc.

3. What is an event listener?
    An event listener waits for a certain event to happen on a page, so that an action can be taken in response to the event. For example, an event listener can wait for a user to hover their mouse over a section of text on the page and then trigger a reaction, such as that section being bolded or turning a different color.

4. Why would we convert a NodeList into an Array?
    We would convert a NodeList into an array in order to access more Javascript functionality. For example, the forEach() Javascriot method can be used to iterate over an array while the same can't be done with a NodeList.

5. What is a component?
    A component is a part of an element that is made up of HTML, CSS, and JavaScript. It is a REUSABLE piece of code that can be built and applied to multiple elements that are similar in functionality and styling.