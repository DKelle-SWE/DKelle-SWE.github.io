---
layout: post
title: Week Five 
---

This week in Software Engineering, my partner Maurya and I submitted our Netflix project. Early in the week, we finished up writing our prediction algorithm and fixing pylint and stylistic issues. We ran into an (almost) big problem when finishing up our prediction algorithm. We have our caches set up to be read as a byte stream through a series of web requests, which means we don't need to have local copies of any of the caches, they're simply read straight from the /u/fares/.../ directory. One morning, our request code started giving us errors that we hadn't seen before. I turned out that the cache our algorithm most heavily depended upon was deleted. This was a problem because there was basically no way for us to recover that specific cache. Luckily enough, I still had all the local copies I had made before we started reading the caches remotely. Without that cache, we would have largely had to come up with a different algorithm that did not depend on the missing cache. Side stepping this potential disaster, we simply had to re-upload the missing cache.

Along with finishing up Netflix, we also had a guest lecturer from Bloomberg talk to us about his contributions and project at Bloomberg, as well as tell us about his company. Amongst other things, the lecturer worked on a search engines of sorts at the California site of Bloomberg. One of the main challenges of this search engine is that there is a very large dataset that must be searched through in order to find the results of a query. Not only does this make indexing the data difficult, but the data is also distributed across multiple machines, which now makes creating an index even much more difficult than before. I didn't quite fully understand how Bloomberg goes about successfully querying against a distributed index, but the general idea was minimizing amount of data that needs to be shared between different nodes in the distributed system (Shards was the word they used to describe different partitions of data on the different nodes, I believe).

My tip of the week is this interesting article on Distributed Search Engines. This article isn't talking about the difficulties in their implementation, but instead analyzes their importance from a security point of view.
https://www.techdirt.com/articles/20140701/03143327738/distributed-search-engines-why-we-need-them-post-snowden-world.shtml


