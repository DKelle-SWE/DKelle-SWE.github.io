---
layout: post
title: Week Two 
---

This week in Software Engineering, I continued my progress on the Collatz project. The collatz conjecture is itself very simple. If a given number is even, divide it by two. If it is Odd, multiply it by 3, and add 1. Repeat these caclulations until we reach the number one. It is believed that any starting number will eventually yeild a 1, although that is not proven.
I believe the purpose of this project is to teach us about industry development pipeline, because the conjecture itself is very easy to implement. The difficult part of this assignment is integrating with Travis CI, git, unit tests, and acceptance tests. In my opinion, the CI is the most important component to this project. The purpose of Travis CI is to ensure that the master branch (or in the case of industry, the customer facing branch) is always in a stable state.
The CI does this by automatically running all unit tests upon pushing a development branch. After the developer verifies all unit tests have passed, the development branch may then be merged with master.

Throughout the week, I finished up some final touches on my cache, and wrote a script that auto-generated a couple hundred extra unit tests. My code passes all of my tests, so I am ready to submit my project to the online tool Sphere Online Judge. Sphere tells me my code has a run time error, and I'm not quite sure why. Sometime early next week, I'll be spending more time looking into this Sphere error. I believe that after I have completed that, I will be ready to create acceptance tests, and submit my assignment.

In industry, you must take extra precautions to make sure that there are no bugs in your code. Another important aspect of industry is making sure that your code is safe. By that, I mean you should always be careful that you are not writing code with vulnerabilities. Here is an interesting article I found this week about 'Buffer Overflow' attacks (which is just one of many ways seemingly safe code can be exploited). Here is an interesting article about buffer overflow attacks that was presented to me by my Network Security professor:
https://www.cs.utexas.edu/~ojensen/courses/cs361s/library/stack.txt
