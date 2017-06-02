# Code Q & A Forum

A code question and answer forum for developers and other tech inclined folk.

## PLANNING
 **1. Config/dependencies:**
   * npm-node package manager
   * bower-front end package manager
   * moment?-time tracker
 
 **2. Specs:**
   * Navigation: each page provides navigation buttons
   * Question: Allows user to add question along with notes, their name. Automatically generates a date.
   * Questions: listed on home page along with author, provide a link to the associated answers
   * Questions: all answers and question editing capability(although this doesn't make any sense as answers will no longer be relevant if the question varies greatly, maybe include a reminder of this) on specific answer page
   * Answers: Allows users to add  answers to questions along with their name and and automatically generated date to keep answers relevant.
   * Answers: link to a specific answer page in order to edit an answer
 
 **3. Integration:**
   * Initial routes: ember new...
   * Template pages:
     * application.hbs ~ over all template including site title and home link
     * index.hbs ~ listing all questions
     * question.hbs ~ listing all answers using question id and updating question
     * answer.hbs ~ updating answer
 
 **4. Models:**
   * questions
     * content
     * author
     * notes
     * date
   * answers
     * content
     * author
     * date
 
 **5. UX/UI**
   * bootstrap, sass
   * customize style(which probably means adding some blue somewhere...)
 
 **6. Polish**
   * Refactor: update component
   * Delete: unnecessary comments
   * README

## Prerequisites
ES6 compatible browser such as Chrome or Safari.

Proper installation of:

* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/) (with NPM)
* [Ember CLI](https://ember-cli.com/)
* [PhantomJS](http://phantomjs.org/)

## Installation

* `git clone https://github.com/sushadore/code-questions.git`
* `cd code-questions`
* `npm install`
* `bower init`

## Run Code Q & A

* `ember serve`
* Visit Code Q & A Forum:  [http://localhost:4200](http://localhost:4200).

### Author
Susha Dore

### License
MIT
Copyright(c) 2017 Susha Dore
