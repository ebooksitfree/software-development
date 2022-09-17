![Cover image for High Performance Python, 2nd Edition](https://imgdetail.ebookreading.net/cover/cover/20200215/EB9781492055013.jpg)

[High Performance Python, 2nd Edition](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_1.html "High Performance Python, 2nd Edition")
====================================================================================================================

Author : [Ian Ozsvald](https://ebookreading.net/search/author/Ian+Ozsvald),[ Micha Gorelick](https://ebookreading.net/search/author/+Micha+Gorelick)

Release Date : 2020/08/01

ISBN : 9781492055013

Topic : [Software Development](https://ebookreading.net/search/category/software-development)

Book Description
-----------------

 Your Python code may run correctly, but you need it to run faster. By exploring the fundamental theory behind design choices, the updated edition of this practical guide, expanded and enhanced for Python 3, helps you gain a deeper understanding of Python’s implementation. You’ll learn how to locate performance bottlenecks and significantly speed up your code in high-data-volume programs.
How can you take advantage of multicore architectures or clusters? Or build a system that can scale up and down without losing reliability? Experienced Python programmers and students alike will learn concrete solutions to these and other issues, along with war stories from companies that use high-performance Python for social media analytics, productionized machine learning, and other situations.
Get a better grasp of NumPy, Cython, and profilersLearn how Python abstracts the underlying computer architectureUnderstand performant pandasUse profiling to find bottlenecks in CPU time and memory usageWrite efficient programs by choosing appropriate data structuresSpeed up matrix, vector, and even tensor computationsUse tools to compile Python down to machine code, on CPUs and GPUsManage multiple I/O and computational operations concurrentlyConvert multiprocessing code to run on a local or remote clusterDeploy code faster using tools like DockerSolve large problems while using less RAMGet real-life stories and lessons from Python programmers        Show and hide more                
Table of Contents
-----------------

1. [Preface](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_4.html#idm45045635610216)
    1. [Who This Book Is For](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_4.html#idm45045635129288)
    1. [Who This Book Is Not For](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_4.html#idm45045635592392)
    1. [What You’ll Learn](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_4.html#idm45045635824664)
    1. [Python 3](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_4.html#idm45045635646856)
    1. [Changes from Python 2.7](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_4.html#idm45045635705400)
    1. [License](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_4.html#idm45045635686840)
    1. [How to Make an Attribution](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_4.html#idm45045635599640)
    1. [Errata and Feedback](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_4.html#idm45045635597288)
    1. [Conventions Used in This Book](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_4.html#idm45045634268936)
    1. [Using Code Examples](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_4.html#idm45045635466888)
    1. [O’Reilly Online Learning](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_4.html#idm45045635354632)
    1. [How to Contact Us](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_4.html#idm45045635348456)
    1. [Acknowledgments](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_4.html#idm45045635347896)
1. [1. Understanding Performant Python](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_5.html#understanding_perfo)
    1. [The Fundamental Computer System](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_5.html#idm45045635440856)
        1. [Computing Units](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_5.html#idm45045635163000)
        1. [Memory Units](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_5.html#idm45045635162376)
        1. [Communications Layers](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_5.html#understanding_pp_co)
    1. [Putting the Fundamental Elements Together](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_5.html#idm45045635440584)
        1. [Idealized Computing Versus the Python Virtual Machine](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_5.html#understanding-perfo)
    1. [So Why Use Python?](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_5.html#idm45045635090392)
    1. [How to be a Highly Performant Programmer](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_5.html#idm45045635089800)
        1. [Good working practices](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_5.html#idm45045635005032)
        1. [Some Thoughts on Good Notebook Practice](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_5.html#idm45045635004408)
        1. [Getting the joy back into your work](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_5.html#idm45045634972280)
1. [2. Profiling to Find Bottlenecks](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_6.html#chapter-profiling)
    1. [Profiling Efficiently](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_6.html#idm45045634948728)
    1. [Introducing the Julia Set](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_6.html#idm45045634948104)
    1. [Calculating the Full Julia Set](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_6.html#idm45045634914056)
    1. [Simple Approaches to Timing—print and a Decorator](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_6.html#idm45045634731336)
    1. [Simple Timing Using the Unix time Command](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_6.html#idm45045631987176)
    1. [Using the cProfile Module](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_6.html#profiling-cprofile)
    1. [Visualizing cProfile Output with SnakeViz](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_6.html#idm45045631688632)
    1. [Using line_profiler for Line-by-Line Measurements](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_6.html#profiling-line-prof)
    1. [Using memory_profiler to Diagnose Memory Usage](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_6.html#memory_profiler)
    1. [Introspecting an Existing Process with PySpy](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_6.html#profiling-pyspy)
    1. [Using the dis Module to Examine CPython Bytecode](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_6.html#profiling-dis)
        1. [Different Approaches, Different Complexity](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_6.html#idm45045629179784)
    1. [Unit Testing During Optimization to Maintain Correctness](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_6.html#profiling-unit-test)
        1. [No-op @profile Decorator](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_6.html#no_op_profile_decor)
    1. [Strategies to Profile Your Code Successfully](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_6.html#profiling-strategie)
    1. [Wrap-Up](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_6.html#idm45045628525928)
1. [3. Lists and Tuples](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_7.html#chapter-lists-tuple)
    1. [A More Efficient Search](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_7.html#idm45045624672072)
    1. [Lists Versus Tuples](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_7.html#idm45045624671448)
        1. [Lists as Dynamic Arrays](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_7.html#list_as_dynamic_arr)
        1. [Tuples as Static Arrays](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_7.html#tuples_as_static_ar)
    1. [Wrap-Up](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_7.html#idm45045624036936)
1. [4. Dictionaries and Sets](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_8.html#section-dictionary-)
    1. [How Do Dictionaries and Sets Work?](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_8.html#dict_set_how_work)
        1. [Inserting and Retrieving](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_8.html#idm45045623239880)
        1. [Deletion](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_8.html#idm45045623239256)
        1. [Resizing](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_8.html#SEC-dict-resize)
        1. [Hash Functions and Entropy](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_8.html#SEC-dict-set-hash-a)
    1. [Dictionaries and Namespaces](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_8.html#dict_namespace)
    1. [Wrap-Up](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_8.html#idm45045622351208)
1. [5. Iterators and Generators](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_9.html#section-iterators-g)
    1. [Iterators for Infinite Series](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_9.html#iterators_inf)
    1. [Lazy Generator Evaluation](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_9.html#idm45045621288216)
    1. [Wrap-Up](https://ebookreading.net/view/book/High+Performance+Python%2C+2nd+Edition-EB9781492055013_9.html#idm45045620718792)
