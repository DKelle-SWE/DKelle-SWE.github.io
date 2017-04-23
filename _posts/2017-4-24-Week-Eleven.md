---
layout: post
title: Week Eleven 
---

Last week in Software Engineering, we finalized our 3 installment of the database project. With this iteration of the database project, we had to implement a search bar, write user stories, utilize another group's API, and write self evaluations.
The search bar of the website was somewhat simple to get working. With some minimal javascript code, we were able to add a search bar to the front end of our site. Initially, I was worried that we were going to have to build some sort of crawler
in or order to support the back end of the search bar, but we were able to easily implement the search bar as a series of database querries, which made things much simpler.

Overall, our website (although not pretty) is fully functional, and can provide all sorts of data about Smash brothers. I think this project was a great way to learn about different types of important tools used in a professional software engineering setting.
Prior to this assignment, we have never had experience with setting up our own integration tests. Being able to set up Travis to automatically run all unit tests with each new push is a great way to slowly and safely integrate new changes. I think this is a great experience to have, especially considering most industry jobs will require unit testing and continuous integration.

We also learned a lot about front-end development and Angular. Angular makes it easy to dynamically render content on a web page - for example, populating tables with the results of a dynamic SQL query.

A lot of the requirements on these assignments require a minimum word count. If you are writing in terminal, there is an easy way to get the number of words in a given document.
My tip of the week is the useful Bash command 'wc -w *filename*'. For example, if I want to check the word count of this weeks blog entry, I can type 'wc -w 2017-4-24-Week-Eleven.md'
