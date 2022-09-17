![Cover image for Modern Systems Programming with Scala Native](https://imgdetail.ebookreading.net/cover/cover/20200920/EB9781680507485.jpg)

[Modern Systems Programming with Scala Native](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_1.html "Modern Systems Programming with Scala Native")
====================================================================================================================

Author : [Richard Whaling](https://ebookreading.net/search/author/Richard+Whaling)

Release Date : 2020/01/01

Book Description
-----------------


    
    Access the power of bare-metal systems programming with Scala Native, an ahead-of-time Scala compiler. Without the baggage of legacy frameworks and virtual machines, Scala Native lets you re-imagine how your programs interact with your operating system. Compile Scala code down to native machine instructions; seamlessly invoke operating system APIs for low-level networking and IO; control pointers, arrays, and other memory management techniques for extreme performance; and enjoy instant start-up times. Skip the JVM and improve your code performance by getting close to the metal.
Developers generally build systems on top of the work of those who came before, accumulating layer upon layer of abstraction. Scala Native provides a rare opportunity to remove layers. Without the JVM, Scala Native uses POSIX and ANSI C APIs to build concise, expressive programs that run unusually close to bare metal. Scala Native compiles Scala code down to native machine instructions instead of JVM bytecode. It starts up fast, without the sluggish warm-up phase that's common for just-in-time compilers. Scala Native programs can seamlessly invoke operating system APIs for low-level networking and IO. And Scala Native lets you control pointers, arrays, and other memory layout types for extreme performance.
Write practical, bare-metal code with Scala Native, step by step. Understand the foundations of systems programming, including pointers, arrays, strings, and memory management. Use the UNIX socket API to write network client and server programs without the sort of frameworks higher-level languages rely on. Put all the pieces together to design and implement a modern, asynchronous microservice-style HTTP framework from scratch.
Take advantage of Scala Native's clean, modern syntax to write lean, high-performance code without the JVM.
What You Need:
A modern Windows, Mac OS, or Linux system capable of running Docker. All code examples in the book are designed to run on a portable Docker-based build environment that runs anywhere. If you don't have Docker yet, see the Appendix for instructions on how to get it.

  

Table of Contents
-----------------

1. [&amp;#160;Acknowledgments](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_6.html#d24e109)
1. [&amp;#160;Foreword](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_7.html#d24e142)
1. [&amp;#160;Preface](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_8.html#chp.Preface)
    1. [Who This Book Is For](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_9.html#d24e166)
    1. [What’s In This Book](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_10.html#d24e283)
    1. [Working with the Code](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_11.html#d24e317)
    1. [Online Resources](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_12.html#d24e524)
1. [&amp;#160;Systems Programming in&amp;#160;the&amp;#160;Twenty-First&amp;#160;CenturySystems Programming in&nbsp;the&nbsp;Twenty-First&nbsp;Century](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_13.html#chp.Introduction)
    1. [What Is Systems Programming?](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_14.html#d24e597)
    1. [Moving Toward Modern Systems Programming](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_15.html#d24e682)
    1. [Why Scala Native?](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_16.html#d24e729)
    1. [What Makes Scala Native Different](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_17.html#d24e923)
1. [Part I. Foundations of Systems Programming](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_18.html#d24e1100)
    1. [1. The Basics: Input and Output](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_19.html#chp.inputoutput)
        1. [Working with Output](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_20.html#d24e1145)
        1. [Working with Input](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_21.html#d24e2240)
        1. [Case Study: Google NGrams](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_22.html#section.MaxNGrams)
        1. [What’s Next](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_23.html#d24e4689)
    1. [2. Arrays, Structs, and the Heap](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_24.html#chp.MemoryManagemen)
        1. [The Stack and the Heap](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_25.html#d24e4720)
        1. [Structs, Arrays, and Sorting](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_26.html#d24e5407)
        1. [Sorting an Array](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_27.html#d24e6301)
        1. [Aggregation at Scale](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_28.html#d24e7035)
        1. [What’s Next](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_29.html#d24e7981)
    1. [3. Writing a Simple HTTP Client](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_30.html#chp.HTTPClient)
        1. [Defining Terms](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_31.html#d24e8006)
        1. [Working with TCP](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_32.html#d24e8274)
        1. [Making a TCP Connection](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_33.html#d24e9382)
        1. [Testing Network Code with Netcat](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_34.html#d24e10250)
        1. [Introducing HTTP](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_35.html#d24e10405)
        1. [Implementing HTTP](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_36.html#d24e10706)
        1. [Testing Our Code](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_37.html#d24e11648)
        1. [What’s Next](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_38.html#d24e11917)
    1. [4. Managing Processes: A Deconstructed Shell](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_39.html#chp.ForkWaitShell)
        1. [Running a Program](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_40.html#d24e11983)
        1. [Introducing exec](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_41.html#d24e12039)
        1. [What Went Wrong?](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_42.html#d24e12600)
        1. [Introducing Concurrency with fork() and wait()](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_43.html#d24e12666)
        1. [Supervising Multiple Processes](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_44.html#d24e13361)
        1. [Working with Pipes](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_45.html#d24e13695)
        1. [What’s Next](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_46.html#d24e14648)
    1. [5. Writing a Server the Old-Fashioned Way](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_47.html#chp.HTTPServer)
        1. [Understanding How a Server Works](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_48.html#d24e14671)
        1. [Building Our Server](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_49.html#d24e15420)
        1. [Creating a Minimum Viable Server](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_50.html#d24e15921)
        1. [Handling HTTP](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_51.html#d24e16254)
        1. [Performance Testing with Gatling](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_52.html#chp.Gatling)
        1. [What’s Next](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_53.html#d24e17125)
1. [Part II. Modern Systems Programming](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_55.html#d24e17155)
    1. [6. Doing I/O Right, with Event Loops](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_56.html#chp.libuvServer)
        1. [Blocking and Polling](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_57.html#d24e17167)
        1. [Introducing libuv](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_58.html#d24e17322)
        1. [Working with Asynchronous TCP Sockets](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_59.html#d24e18556)
        1. [Building an Asynchronous HTTP Server](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_60.html#d24e21042)
        1. [What’s Next](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_61.html#d24e22380)
    1. [7. Functions and Futures: Patterns for&amp;#160;Distributed ServicesFunctions and Futures: Patterns for&nbsp;Distributed Services](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_62.html#chp.libuvFutures)
        1. [Designing an Asynchronous API](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_63.html#d24e22430)
        1. [Introducing Futures](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_64.html#d24e22564)
        1. [Implementing Futures](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_65.html#d24e22841)
        1. [Implementing an ExecutionContext](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_66.html#d24e23139)
        1. [Futures and Promises](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_67.html#d24e23723)
        1. [Introducing libcurl](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_68.html#d24e24138)
        1. [Asynchronous curl](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_69.html#d24e25441)
        1. [What’s Next](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_70.html#d24e27579)
    1. [8. Streaming with Pipes and Files](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_71.html#chp.libuvPipes)
        1. [Looking at Streams, Files, and Descriptors](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_72.html#d24e27609)
        1. [Streaming Pipe Input in libuv](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_73.html#d24e27749)
        1. [Streaming File Input in libuv](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_74.html#d24e28692)
        1. [Streaming File Output in libuv](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_75.html#d24e29752)
        1. [Stream Processors](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_76.html#d24e30539)
        1. [What’s Next](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_77.html#d24e31929)
    1. [9. Durability: An Embedded Key-Value Database with LMDB](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_78.html#chp.lmdb)
        1. [Introducing Embedded Storage](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_79.html#d24e32014)
        1. [Defining LMDB Concepts](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_80.html#d24e32095)
        1. [Working with the LMDB API](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_81.html#d24e32199)
        1. [Serialization and Deserialization with JSON](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_82.html#chp.lmdb.json)
        1. [Putting LMDB on the Web](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_83.html#d24e33603)
        1. [What’s Next](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_84.html#d24e34199)
    1. [10. Services: Encapsulation and Abstraction for Modern Designs](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_85.html#chp.conclusions)
        1. [Services and Distributed Systems](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_86.html#d24e34255)
        1. [Parsing, Revisited](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_87.html#d24e34554)
        1. [Moving from Server to Service](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_88.html#d24e36111)
        1. [Implementing an Idiomatic Service DSL](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_89.html#d24e37584)
        1. [Integrations and Ecosystems](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_90.html#d24e38396)
        1. [The Way Forward](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_91.html#d24e38781)
1. [A1. Setting Up the Environment](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_93.html#chp.EnvironmentSetu)
    1. [Running Scala Native on Mac OS](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_94.html#d24e38916)
    1. [Why Use Containers?](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_95.html#d24e39076)
    1. [Installing and Configuring Docker](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_96.html#d24e39123)
    1. [Running Scala Native in Docker](https://ebookreading.net/view/book/Modern+Systems+Programming+with+Scala+Native-EB9781680507485_97.html#d24e39271)
