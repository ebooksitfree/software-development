![Cover image for Clojure Data Structures and Algorithms Cookbook](https://imgdetail.ebookreading.net/cover/cover/software_development/EB9781785281457.jpg)

[Clojure Data Structures and Algorithms Cookbook](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_1.html "Clojure Data Structures and Algorithms Cookbook")
====================================================================================================================

Author : [Rafik Naccache](https://ebookreading.net/search/author/Rafik+Naccache)

Release Date : 2015/08/01

ISBN : 9781785281457

Topic : [Software Development](https://ebookreading.net/search/category/software-development)

Book Description
-----------------

25 recipes to deeply understand and implement advanced algorithms in Clojure
About This Book
Explore various advanced algorithms and learn how they are used to address many real-world computing challengesConstruct elegant solutions using impressive techniques including zippers, parsing, and pattern matchingSolve complex problems by adopting innovative approaches such as logic or asynchronous programmingIn Detail
Data-structures and algorithms often cross your path when you compress files, compile programs, access databases, or simply use your favourite text editor. Understanding and implementing them can be daunting. Curious learners and industrial developers can find these complex, especially if they focus on the detailed implementation of these data structures.
Clojure is a highly pragmatic and expressive language with efficient and easy data manipulation capabilities. As such, it is great for implementing these algorithms. By abstracting away a great share of the unnecessary complexity resulting from implementation, Clojure and its contrib libraries will help you address various algorithmic challenges, making your data exploration both profitable and enjoyable.
Through 25 recipes, you'll explore advanced algorithms and data-structures, well served by a sound Clojure implementation.
This book opens with an exploration of alternative uses of the array data-structure, covering LZ77 compression, drawing fractals using Pascal's triangles, simulating a multi-threaded program execution, and implementing a call-stack winding and un-winding operations.
The book elaborates on linked lists, showing you how to construct doubly linked ones, speed up search times over the elements of such structures, use a linked-list as the foundation of a shift-reduce parser, and implement an immutable linked-list using skew binary numbers representation.
After that, the tree data-structure is explored, focusing on building self-balancing Splay Trees, designing a B-Tree backing-up an efficient key-value data-store, constructing an undo capable Rope, and showing how Tries can make for an auto-completing facility.
Next, some optimization and machine learning techniques are discussed, namely for building a co-occurrence-based recommendation engine, using branch-and-bound to optimize integral cost and profit problems, using Dijkstra's algorithm to determine optimal paths and summarizing texts using the LexRank algorithm.
Particular attention is given to logic programming, you will learn to use this to discover interesting relations between social website data, by designing a simple type inferencer for a mini Java-like language, and by building a simple checkers game engine.
Asynchronous programming will be addressed and you will design a concurrent web-crawler, an interactive HTML5 game, and an online taxi booking platform.
Finally, you'll explore advanced cases for higher order functions in Clojure while implementing a recursive descent parser using efficient mutual resucrsion, devising a mini resusable firewall simulator thanks to Clojure 1.7 new tansducers feature or building a simple unification engine with the help of Continuation Passing Style.
What You Will Learn
Explore alternative uses of classical data-structures like arrays and linked-listsDiscover advanced types of tree data-structuresExplore advanced machine learning and optimization techniquesUtilise powerful Clojure libraries, such as Instaparse for parsing, core.match for pattern matching, clojure.zip for zippers, and clojure.matrix for matrix operationsLearn logic programming through the usage of the library core.logicMaster asynchronous programming using the core.async librarySee the transducers in action while resolving real-world use-casesWho This Book Is For
If you are an experienced Clojure developer, longing to take your knowledge to the next level by discovering and using advanced algorithms and seeing how they can be applied to real-world problems, then this book is for you.
Style and approach
This book consists of a set of step-by-step recipes, each demonstrating the material covered in action so it is put in context. When necessary, pointers to further resources are provided.
Downloading the example code for this book. You can download the example code files for all Packt books you have purchased from your account at http://www.PacktPub.com. If you purchased this book elsewhere, you can visit http://www.PacktPub.com/support and register to have the code file.
              
Table of Contents
-----------------

1. [Clojure Data Structures and Algorithms Cookbook](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_3.html)
    1. [Table of Contents](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_2.html)
    1. [Clojure Data Structures and Algorithms Cookbook](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_4.html)
    1. [Credits](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_5.html)
    1. [About the Author](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_6.html)
    1. [About the Reviewers](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_7.html)
    1. [www.PacktPub.com](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_8.html)
        1. [Support files, eBooks, discount offers, and more](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_8.html#ch00lvl1sec01)
            1. [Why Subscribe?](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_8.html#ch00lvl2sec01)
            1. [Free Access for Packt account holders](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_8.html#ch00lvl2sec02)
    1. [Preface](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_9.html)
        1. [What this book covers](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_9.html#ch00lvl1sec02)
        1. [What you need for this book](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_10.html)
        1. [Who this book is for](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_11.html)
        1. [Sections](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_12.html)
            1. [Getting ready](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_12.html#ch00lvl2sec03)
            1. [How to do it…](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_12.html#ch00lvl2sec04)
            1. [How it works…](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_12.html#ch00lvl2sec05)
            1. [There&#39;s more…](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_12.html#ch00lvl2sec06)
            1. [See also](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_12.html#ch00lvl2sec07)
        1. [Conventions](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_13.html)
        1. [Reader feedback](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_14.html)
        1. [Customer support](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_15.html)
            1. [Downloading the example code](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_15.html#ch00lvl2sec08)
            1. [Errata](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_15.html#ch00lvl2sec09)
            1. [Piracy](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_15.html#ch00lvl2sec10)
            1. [Questions](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_15.html#ch00lvl2sec11)
    1. [1. Revisiting Arrays](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_16.html)
        1. [Introduction](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_16.html#ch01lvl1sec09)
        1. [Efficiently compressing a byte array](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_17.html)
            1. [How to do it...](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_17.html#ch01lvl2sec12)
        1. [Using Pascal&#39;s triangle to draw fractals](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_18.html)
            1. [How to do it...](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_18.html#ch01lvl2sec13)
        1. [Simulating multithreading using time-sharing](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_19.html)
            1. [How to do it...](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_19.html#ch01lvl2sec14)
        1. [Simulating a call stack using arrays](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_20.html)
            1. [How to do it...](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_20.html#ch01lvl2sec15)
    1. [2. Alternative Linked Lists](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_21.html)
        1. [Building a doubly linked XOR list](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_21.html#ch02lvl1sec14)
            1. [How to do it…](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_21.html#ch02lvl2sec16)
        1. [Speeding up access to linked list elements](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_22.html)
            1. [How to do it…](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_22.html#ch02lvl2sec17)
        1. [Building a simple shift-reduce parser](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_23.html)
            1. [How to do it…](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_23.html#ch02lvl2sec18)
        1. [Implementing a skew binary random access list](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_24.html)
            1. [How to do it…](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_24.html#ch02lvl2sec19)
    1. [3. Walking Down Forests of Data](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_25.html)
        1. [Introduction](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_25.html#ch03lvl1sec18)
        1. [Building self-balancing, search-efficient splay trees](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_26.html)
            1. [How to do it...](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_26.html#ch03lvl2sec20)
        1. [Designing an efficient key-value store using B-trees](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_27.html)
            1. [How to do it...](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_27.html#ch03lvl2sec21)
            1. [How it works…](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_27.html#ch03lvl2sec22)
        1. [Devising an undo-capable data structure using a rope](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_28.html)
            1. [How to do it...](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_28.html#ch03lvl2sec23)
        1. [Designing an autocomplete system using a trie](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_29.html)
            1. [How to do it...](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_29.html#ch03lvl2sec24)
    1. [4. Making Decisions with the Help of Science](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_30.html)
        1. [Introduction](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_30.html#ch04lvl1sec23)
        1. [Designing a live recommendation engine](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_31.html)
            1. [How to do it...](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_31.html#ch04lvl2sec25)
        1. [Resolving cost and profit optimization problems](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_32.html)
            1. [How to do it...](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_32.html#ch04lvl2sec26)
        1. [Finding optimal paths in a graph](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_33.html)
            1. [How to do it...](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_33.html#ch04lvl2sec27)
        1. [Summarizing texts by extracting the most representative sentences](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_34.html)
            1. [How to do it...](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_34.html#ch04lvl2sec28)
    1. [5. Programming with Logic](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_35.html)
        1. [Introduction](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_35.html#ch05lvl1sec28)
        1. [Querying a social website&#39;s data](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_36.html)
            1. [How to do it…](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_36.html#ch05lvl2sec29)
        1. [Designing a type inferencer](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_37.html)
            1. [How to do it…](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_37.html#ch05lvl2sec30)
        1. [Playing a round of checkers](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_38.html)
            1. [How to do it…](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_38.html#ch05lvl2sec31)
    1. [6. Sharing by Communicating](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_39.html)
        1. [Introduction](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_39.html#ch06lvl1sec32)
        1. [Building a tiny web crawler](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_40.html)
            1. [How to do it…](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_40.html#ch06lvl2sec32)
        1. [Designing an HTML5 game](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_41.html)
            1. [How to do it…](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_41.html#ch06lvl2sec33)
        1. [Designing an online taxi-booking engine](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_42.html)
            1. [How to do it…](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_42.html#ch06lvl2sec34)
    1. [7. Transformations as First-class Citizens](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_43.html)
        1. [Introduction](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_43.html#ch07lvl1sec36)
        1. [Building a recursive descent parser using trampoline](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_44.html)
            1. [How to do it…](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_44.html#ch07lvl2sec35)
        1. [Implementing a reusable mini-firewall using transducers](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_45.html)
            1. [How to do it…](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_45.html#ch07lvl2sec36)
        1. [Building a little unification engine with the continuation-passing style](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_46.html)
            1. [How to do it...](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_46.html#ch07lvl2sec37)
    1. [Index](https://ebookreading.net/view/book/Clojure+Data+Structures+and+Algorithms+Cookbook-EB9781785281457_47.html)
