# Applied JavaScript Sprint Challenge

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past sprint and apply them in a concrete project. This sprint explored **Applied JavaScript**. During this sprint, you studied **DOM and components**. In your challenge this week, you will demonstrate your mastery of these skills by creating **an online Bloomtech newspaper**.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge.

## Project Set Up

- [x] Fork and clone the repo. Delete your old fork from Github first if you are repeating this Unit.
- [x] Open the assignment in Canvas and click on the "Set up git" option.
- [x] Push your first commit: `git commit --allow-empty -m "first commit" && git push`.
- [x] Check to see that Codegrade has accepted your git submission.

## Project Instructions

### Introduction

You are going to create a Bloomtech Newspaper. Your job is going to be to create the components that make up the newspaper's home page.

In meeting the minimum viable product (MVP) specifications listed below, your project should look similar to the image linked below:

[Bloomtech Times](https://tk-assets.lambdaschool.com/cac4803c-6e8f-4846-be0e-b20d82a34a73_lambda-times.png)

### Instructions

- [x] Navigate to the root of the project with your command line.
- [x] Run `npm install` to download the dependencies listed in the `package.json` file.
- [ ] Run `npm start` to compile the project and serve it.
- [x] Navigate Chrome to `http://localhost:3000`
- [x] In a separate terminal, run `npm test` to run tests.

**Steps Required for MVP:**

- [x] Steps 1 and 2 are explained inside the `src/components/header.js` file.
- [x] Steps 3 and 4 are explained inside the `src/components/tabs.js` file.
- [x] Steps 5 and 6 are explained inside the `src/components/card.js` file.

**Important Notes:**

- Please **do not move or rename existing files** or folders.
- If your development server stops "auto reloading", manually kill it with `CTRL+C` and restart it.
- Do not change the `package.json` file except to install libraries with NPM (Axios is _already_ in the `package.json`).
- In your solution, it is essential that you follow best practices and produce clean and professional results.
- Schedule time to review, refine, and polish your work, including spell-checking and grammar-checking.
- It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Submission format

- [x] Submit via Codegrade by committing and pushing any new changes to the *main* branch.
- [x] Check Codegrade for automated feedback.
- [x] Check Codegrade in the days following the Sprint Challenge for reviewer feedback.
- [x] Any changes pushed after the deadline will not receive any feedback.

## Interview Questions

Demonstrate your understanding of this week's concepts by answering the following questions:

1. What is the DOM?

The DOM is an API that allows javascript to create, read, update or delete html content
1. What is an event?

An event is anything that can be detected by the browser, i.e., click, hover, scroll, etc.

2. What is an event listener?

An event listener is a method that is fired whenever an event occurs on the element that has the event listener. It takes two arguments, an event to listen to and a callback function to be executed when the event occurs.

3. Why would we convert a NodeList into an Array?

Converting a NodeList to an Array allows us to use all the fun Array methods such as map, filter and reduce.

4. What is a component?

A component is a function that returns a container consisting of html elements. Components are especially useful when you have a lot of containers that contain identical html and css classes but differ only in the content contained within these elements. Creating a component allows us to keep our code dry.
