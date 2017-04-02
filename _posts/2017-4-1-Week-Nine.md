---
layout: post
title: Week Nine
---

Last week in Software Engineering, we started talking about regex. Regexs is a way to use a sequence of character to define a pattern. This pattern is then usually used for string search algorithms, or search and replace algorithms.
In my opinion, regex strings can be very complicated to look at, and even more confusing to anyone not well versed in the regular expression language. For example, take a look at the following regular expression:

    [A-Z0-9._%+-]+@[A-Z0-9.-]+\.[A-Z]{2,}

This string looks almost like nonsense, but regex has very careful rules defining what each section of the above string does.

    [A-Z0-9._%+-]+ 

This will match any string containing the letters A-Z, numbers 0-9, dots, underscores, percents, plus and minus.
    
    @

This will match with the literal symbol '@'

    [A-Z0-9.-]+

This will match one or more letter, digit, and hyphens.

    \.[A-Z]{2,}

This will finally match a single dot, and then two letters.


Aside from talking about regex, we started part 2 of our IDb project. In part 1, we finished our 2500 word documentation guide, which we will need to bump up to 3750 words.
In part 2, we will also need to create our actual databases, and hook them into the website. After the databases are filled with data, we can have our 'Tournamnets', 'Characters', etc pages can load real live data.
After we hook in our databases, we need to give our 'About' page a button to automatically run our unit tests. After this, we should have finished up part 2.

My tip of the week is this useful explanation of regex with examples, including the one I detailed above:
http://www.regular-expressions.info/tutorial.html

