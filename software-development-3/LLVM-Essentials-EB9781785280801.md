![Cover image for LLVM Essentials](https://imgdetail.ebookreading.net/cover/cover/software_development/EB9781785280801.jpg)

[LLVM Essentials](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_1.html "LLVM Essentials")
====================================================================================================================

Author : [Mayur Pandey](https://ebookreading.net/search/author/Mayur+Pandey),[ Suyog Sarda](https://ebookreading.net/search/author/+Suyog+Sarda)

Release Date : 2015/12/01

ISBN : 9781785280801

Topic : [Software Development](https://ebookreading.net/search/category/software-development)

Book Description
-----------------

 Become familiar with the LLVM infrastructure and start using LLVM libraries to design a compiler
About This Book
Learn to use the LLVM libraries to emit intermediate representation (IR) from high-level languageBuild your own optimization pass for better code generationUnderstand AST generation and use it in a meaningful wayWho This Book Is For
This book is intended for those who already know some of the concepts of compilers and want to quickly get familiar with the LLVM infrastructure and the rich set of libraries that it provides.
What You Will Learn
Get an introduction to LLVM modular design and LLVM toolsConvert frontend code to LLVM IRImplement advanced LLVM IR paradigmsUnderstand the LLVM IR Optimization Pass Manager infrastructure and write an optimization passAbsorb LLVM IR transformationsUnderstand the steps involved in converting LLVM IR to Selection DAGImplement a custom target using the LLVM infrastructureGet a grasp of C's frontend clang, an AST dump, and static analysisIn Detail
LLVM is currently the point of interest for many firms, and has a very active open source community. It provides us with a compiler infrastructure that can be used to write a compiler for a language. It provides us with a set of reusable libraries that can be used to optimize code, and a target-independent code generator to generate code for different backends. It also provides us with a lot of other utility tools that can be easily integrated into compiler projects.
This book details how you can use the LLVM compiler infrastructure libraries effectively, and will enable you to design your own custom compiler with LLVM in a snap.
We start with the basics, where you'll get to know all about LLVM. We then cover how you can use LLVM library calls to emit intermediate representation (IR) of simple and complex high-level language paradigms. Moving on, we show you how to implement optimizations at different levels, write an optimization pass, generate code that is independent of a target, and then map the code generated to a backend. The book also walks you through CLANG, IR to IR transformations, advanced IR block transformations, and target machines.
By the end of this book, you'll be able to easily utilize the LLVM libraries in your own projects.
Style and approach
This book deals with topics sequentially, increasing the difficulty level in a step-by-step approach. Each topic is explained with a detailed example, and screenshots are included to help you understand the examples.
        Show and hide more                
Table of Contents
-----------------

1. [LLVM Essentials](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_3.html)
    1. [Table of Contents](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_2.html)
    1. [LLVM Essentials](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_4.html)
    1. [Credits](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_5.html)
    1. [About the Authors](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_6.html)
    1. [About the Reviewer](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_7.html)
    1. [www.PacktPub.com](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_8.html)
        1. [Support files, eBooks, discount offers, and more](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_8.html#ch00lvl1sec01)
            1. [Why subscribe?](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_8.html#ch00lvl2sec01)
            1. [Free access for Packt account holders](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_8.html#ch00lvl2sec02)
    1. [Preface](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_9.html)
        1. [What this book covers](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_9.html#ch00lvl1sec02)
        1. [What you need for this book](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_10.html)
        1. [Who this book is for](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_11.html)
        1. [Conventions](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_12.html)
        1. [Reader feedback](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_13.html)
        1. [Customer support](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_14.html)
            1. [Downloading the example code](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_14.html#ch00lvl2sec03)
            1. [Errata](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_14.html#ch00lvl2sec05)
            1. [Piracy](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_14.html#ch00lvl2sec06)
            1. [Questions](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_14.html#ch00lvl2sec07)
    1. [1. Playing with LLVM](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_15.html)
        1. [Modular design and collection of libraries](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_15.html#ch01lvl1sec08)
        1. [Getting familiar with LLVM IR](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_16.html)
        1. [LLVM tools and using them in the command line](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_17.html)
        1. [Summary](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_18.html)
    1. [2. Building LLVM IR](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_19.html)
        1. [Creating an LLVM module](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_19.html#ch02lvl1sec12)
        1. [Emitting a function in a module](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_20.html)
        1. [Adding a block to a function](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_21.html)
        1. [Emitting a global variable](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_22.html)
        1. [Emitting a return statement](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_23.html)
        1. [Emitting function arguments](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_24.html)
        1. [Emitting a simple arithmetic statement in a basic block](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_25.html)
        1. [Emitting if-else condition IR](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_26.html)
        1. [Emitting LLVM IR for loop](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_27.html)
        1. [Summary](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_28.html)
    1. [3. Advanced LLVM IR](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_29.html)
        1. [Memory access operations](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_29.html#ch03lvl1sec22)
        1. [Getting the address of an element](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_30.html)
        1. [Reading from the memory](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_31.html)
        1. [Writing into a memory location](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_32.html)
        1. [Inserting a scalar into a vector](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_33.html)
        1. [Extracting a scalar from a vector](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_34.html)
        1. [Summary](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_35.html)
    1. [4. Basic IR Transformations](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_36.html)
        1. [Opt Tool](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_36.html#ch04lvl1sec29)
        1. [Pass and Pass Manager](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_37.html)
        1. [Using other Pass info in current Pass](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_38.html)
            1. [AnalysisUsage::addRequired&lt;&gt; method](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_38.html#ch04lvl2sec08)
            1. [AnalysisUsage:addRequiredTransitive&lt;&gt; method](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_38.html#ch04lvl2sec09)
            1. [AnalysisUsage::addPreserved&lt;&gt; method](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_38.html#ch04lvl2sec10)
        1. [Instruction simplification example](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_39.html)
        1. [Instruction Combining](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_40.html)
        1. [Summary](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_41.html)
    1. [5. Advanced IR Block Transformations](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_42.html)
        1. [Loop processing](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_42.html#ch05lvl1sec35)
        1. [Scalar evolution](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_43.html)
        1. [LLVM intrinsics](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_44.html)
        1. [Vectorization](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_45.html)
        1. [Summary](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_46.html)
    1. [6. IR to Selection DAG phase](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_47.html)
        1. [Converting IR to selectionDAG](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_47.html#ch06lvl1sec40)
        1. [Legalizing SelectionDAG](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_48.html)
        1. [Optimizing SelectionDAG](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_49.html)
        1. [Instruction Selection](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_50.html)
        1. [Scheduling and emitting machine instructions](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_51.html)
        1. [Register allocation](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_52.html)
        1. [Code Emission](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_53.html)
        1. [Summary](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_54.html)
    1. [7. Generating Code for Target Architecture](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_55.html)
        1. [Sample backend](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_55.html#ch07lvl1sec48)
            1. [Defining registers and register sets](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_55.html#ch07lvl2sec11)
            1. [Defining the calling convention](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_55.html#ch07lvl2sec12)
            1. [Defining the instruction set](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_55.html#ch07lvl2sec13)
        1. [Implementing frame lowering](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_56.html)
        1. [Lowering instructions](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_57.html)
        1. [Printing an instruction](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_58.html)
        1. [Summary](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_59.html)
    1. [Index](https://ebookreading.net/view/book/LLVM+Essentials-EB9781785280801_60.html)
