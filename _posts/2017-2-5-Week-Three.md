---
layout: post
title: Week Three 
---

This week in Software Engineering, I finally passed the Collatz Sphere Online tests. The speed requirements were much more difficult to satisfy than I was expecting. Initially, I had a lazy cache that would populate itself after computing collatz sequence lengths. This was too slow, even when I switched the cache from being an array to a dictionary (even though the dictionary used too much space to satisfy the memory requirements anyway). After I realized a lazy cache was not going to work, I switched to an eager cache. The eager cache differs from the lazy cache in that, on start up of the program, the eager cache would automatically compute, and store the collatz sequence of the first N digits. Even after testing various N (include 1000 up to 100000), this approach was still too slow. Eventually I landed on using a Meta cache, which was just a cache preloaded with hard coded integers and their corresponding sequence lengths. Finally that was quick enough to satisfy all time requirements.

In the upcoming week, we are being assigned a new project. In this project we will have to come up with an algorithm to approximate TV shows users will like based on their previous ratings of other TV shows. I remember hearing about this project many semesters ago by other students who were enrolled in SWE. This was one of the first projects that I had heard of that really connected computer science to real world applications for me. This algorithm that we design can be compared to the actual Netflix algorithm to determine how successfully we recommend shows to users (and weather or not the user actually does like the show we recommend). I'm excited to see how good my recommendation algorithm is going to be, and if it would actually help real users or not.

My tip of the week is actually about the Netflix project as well. In order to actually be able to test your algorithm, you must have access to real user data, which Netflix released. Netflix, of course, anonymized this data before releasing it. However, Professors Narayanan and Vitaly from The University of Texas were able to reverse this anonymization. Here is a cool article talking about it!
http://www.securityfocus.com/news/11497