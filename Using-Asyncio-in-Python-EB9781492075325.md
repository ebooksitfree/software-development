![Cover image for Using Asyncio in Python](https://imgdetail.ebookreading.net/cover/cover/20200215/EB9781492075325.jpg)

[Using Asyncio in Python](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_1.html "Using Asyncio in Python")
====================================================================================================================

Author : [Caleb Hattingh](https://ebookreading.net/search/author/Caleb+Hattingh)

Release Date : 2020/02/01

ISBN : 9781492075325

Topic : [Software Development](https://ebookreading.net/search/category/software-development)

Book Description
-----------------

 If you’re among the Python developers put off by asyncio’s complexity, it’s time to take another look. Asyncio is complicated because it aims to solve problems in concurrent network programming for both framework and end-user developers. The features you need to consider are a small subset of the whole asyncio API, but picking out the right features is the tricky part. That’s where this practical book comes in.
Veteran Python developer Caleb Hattingh helps you gain a basic understanding of asyncio’s building blocks—enough to get started writing simple event-based programs. You’ll learn why asyncio offers a safer alternative to preemptive multitasking (threading) and how this API provides a simpleway to support thousands of simultaneous socket connections.
Get a critical comparison of asyncio and threading for concurrent network programmingTake an asyncio walk-through, including a quickstart guidefor hitting the ground looping with event-based programmingLearn the difference between asyncio features for end-user developers and those for framework developersUnderstand asyncio’s new async/await language syntax, including coroutines and task and future APIsGet detailed case studies (with code) of some popular asyncio-compatible third-party libraries        Show and hide more                
Table of Contents
-----------------

1. [Preface](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_5.html#idm46363041469800)
    1. [Conventions Used in This Book](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_5.html#idm46363037630456)
    1. [O’Reilly Online Learning](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_5.html#idm46363041713368)
    1. [How to Contact Us](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_5.html#idm46363041707304)
    1. [Acknowledgments](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_5.html#idm46363041432776)
1. [1. Introducing Asyncio](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_6.html#intro)
    1. [The Restaurant of ThreadBots](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_6.html#idm46363041299848)
    1. [Epilogue](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_6.html#idm46363040920120)
    1. [What Problem Is Asyncio Trying to Solve?](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_6.html#idm46363041383992)
1. [2. The Truth About Threads](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_7.html#idm46363041383400)
    1. [Benefits of Threading](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_7.html#idm46363041327176)
    1. [Drawbacks of Threading](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_7.html#idm46363041326584)
    1. [Case Study: Robots and Cutlery](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_7.html#robotcut)
1. [3. Asyncio Walk-Through](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_8.html#walkthrough)
    1. [Quickstart](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_8.html#quickstart-section)
    1. [The Tower of Asyncio](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_8.html#idm46363038712280)
    1. [Coroutines](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_8.html#idm46363038108680)
        1. [The New async def Keywords](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_8.html#idm46363037973208)
        1. [The New await Keyword](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_8.html#idm46363037972584)
    1. [Event Loop](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_8.html#idm46363033411304)
    1. [Tasks and Futures](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_8.html#idm46363032574840)
        1. [Create a Task? Ensure a Future? Make Up Your Mind!](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_8.html#idm46363032018024)
    1. [Async Context Managers: async with](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_8.html#idm46363032535208)
        1. [The contextlib Way](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_8.html#idm46363031302696)
    1. [Async Iterators: async for](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_8.html#asynciter)
    1. [Simpler Code with Async Generators](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_8.html#idm46363030891800)
    1. [Async Comprehensions](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_8.html#idm46363030155608)
    1. [Starting Up and Shutting Down (Gracefully!)](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_8.html#shutdown)
        1. [What Is the return_exceptions=True for in gather()?](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_8.html#retexcept)
        1. [Signals](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_8.html#signals)
        1. [Waiting for the Executor During Shutdown](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_8.html#waitforexe)
1. [4. 20 Asyncio Libraries You Aren’t Using (But…Oh, Never Mind)](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_9.html#idm46363027999656)
    1. [Streams (Standard Library)](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_9.html#idm46363027306152)
        1. [Case Study: A Message Queue](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_9.html#idm46363027300408)
        1. [Case Study: Improving the Message Queue](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_9.html#idm46363027299464)
    1. [Twisted](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_9.html#idm46363025091144)
    1. [The Janus Queue](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_9.html#idm46363025090616)
    1. [aiohttp](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_9.html#idm46363024062120)
        1. [Case Study: Hello World](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_9.html#idm46363024057304)
        1. [Case Study: Scraping the News](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_9.html#scrapingthenews)
    1. [ØMQ (ZeroMQ)](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_9.html#idm46363023394296)
        1. [Case Study: Multiple Sockets](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_9.html#idm46363023436328)
        1. [Case Study: Application Performance Monitoring](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_9.html#appmon)
    1. [asyncpg and Sanic](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_9.html#idm46363022486824)
        1. [Case Study: Cache Invalidation](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_9.html#asyncpg_cs)
    1. [Other Libraries and Resources](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_9.html#idm46363021187144)
1. [5. Concluding Thoughts](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_10.html#idm46363038764104)
1. [A. A Short History of Async Support in Python](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_11.html#idm46363041117176)
    1. [In the Beginning, There Was asyncore](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_11.html#idm46363039344728)
    1. [The Path to Native Coroutines](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_11.html#idm46363039344184)
1. [B. Supplementary Material](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_12.html#appendixb)
    1. [Cutlery Example Using Asyncio](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_12.html#idm46363039268520)
    1. [Supplementary Material for News Website Scraper](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_12.html#supnews)
    1. [Supplementary Material for the ZeroMQ Case Study](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_12.html#supappmon)
    1. [Database Trigger Handling for the asyncpg Case Study](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_12.html#appendix_trigger)
    1. [Supplementary Material for the Sanic Example: aelapsed and aprofiler](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_12.html#appendix_perf)
1. [Index](https://ebookreading.net/view/book/Using+Asyncio+in+Python-EB9781492075325_13.html#idm46363016614488)
