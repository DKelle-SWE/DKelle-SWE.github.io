---
layout: post
title: Week Four
---

This is the week of the Netflix project. The idea of this project is that there exists some data about Netflix users and their ratings of movies. Our goal is to write a script that can accurately predict how a given user will rate a given movie. A large subset of the Netflix user data is used as training data for our predictor to attempt to learn against. Once the predictor has chugged through all the training data, it will be ready to run against the test data. After calculating predictions for all of the test data, we must have some way to measure the accuracy of our predictor. To do so, we are using a Root Mean Square Error (RMSE) algorithm. This past week in class we saw several implementations of the RMSE, and analyzed their respective speeds. The fastest version of RMSE was implemented using the numpy library, which makes sense, because numpy actually runs as C code in the background.

The schedule of my partner and I did not line up so well this first week, so we have not made too much progress. So far, we have set up a github with all of the starter code, provided a temporary fix to make sure all current tests pass, hooked our repo into TravisCI, invited the graders to our private repo, and gain access to the test repository. We have set aside several times next week to start working on our actual predictor. Our goal is to have the predictor work with an RMSE of less than 1, and a runtime of less than one minute.

My tip of the week is this interesting paper detailing the 2009 iteration of the Netflix Prediction algorithm dubbed “BelKor’s Pragmatic Chaos”algorithm. This won the Netflix Challenge grand prize for 2009. Find the paper here: http://www.netflixprize.com/assets/GrandPrize2009_BPC_BellKor.pdf

