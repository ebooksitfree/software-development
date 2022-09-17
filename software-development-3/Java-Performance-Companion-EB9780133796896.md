![Cover image for Java® Performance Companion](https://imgdetail.ebookreading.net/cover/cover/20200215/EB9780133796896.jpg)

[Java® Performance Companion](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_1.html "Java® Performance Companion")
====================================================================================================================

Author : [Monica Beckwith](https://ebookreading.net/search/author/Monica+Beckwith),[ Bengt Rutisson](https://ebookreading.net/search/author/+Bengt+Rutisson),[ Poonam Parhar](https://ebookreading.net/search/author/+Poonam+Parhar),[ Charlie Hunt](https://ebookreading.net/search/author/+Charlie+Hunt)

Release Date : 2016/04/01

ISBN : 9780133796896

Topic : [Software Development](https://ebookreading.net/search/category/software-development)

Book Description
-----------------

 Java® Performance Companion shows how to systematically and proactively improve Java performance with today’s advanced multicore hardware and complex operating system environments.
The authors, who are all leading Java performance and Java HotSpot VM experts, help you improve performance by using modern software engineering practices, avoiding common mistakes, and applying tips and tricks gleaned from years of real-world experience.
Picking up where Charlie Hunt and Binu John’s classic Java Performance left off, this book provides unprecedented detail on two powerful Java platform innovations: the Garbage First (G1) garbage collector and the HotSpot VM Serviceability Agent.
Coverage includes
Leveraging G1 to overcome limitations in parallel, serial, and CMS garbage collection
Understanding each stage of G1 GC collections, both young and old
Getting under the hood with G1 and efficiently fine-tuning it for your application
Identifying potential optimizations, interpreting experimental results, and taking action
Exploring the internals of the HotSpot VM
Using HotSpot VM Serviceability Agent to analyze, triage, and resolve diverse HotSpot VM issues
Troubleshooting out of memory errors, Java level deadlocks, and HotSpot VM crashes
Extending the Serviceability Agent, and using the Plugin for VisualVM
Mastering useful HotSpot VM command line options not covered in Java™ Performance
Java® Performance Companion can help you squeeze maximum performance and value from Java with JDK 8 or 9–for any application, in any environment.
Register your product at informit.com/register for convenient access to downloads, updates, and corrections as they become available. 
        Show and hide more                
Table of Contents
-----------------

1. [About This E-Book](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_2.html#pref00)
1. [Title Page](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_3.html#title)
1. [Copyright Page](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_4.html#copy)
1. [Contents](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_5.html#toc)
1. [Preface](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_6.html#pref01)
    1. [References](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_6.html#pref01lev1sec1)
1. [Acknowledgments](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_7.html#pref02)
    1. [Charlie Hunt](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_7.html#pref02lev1sec1)
    1. [Monica Beckwith](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_7.html#pref02lev1sec2)
    1. [Poonam Parhar](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_7.html#pref02lev1sec3)
    1. [Bengt Rutisson](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_7.html#pref02lev1sec4)
1. [About the Authors](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_8.html#pref03)
1. [1. Garbage First Overview](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_9.html#ch01)
    1. [Terminology](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_9.html#ch01lev1sec1)
    1. [Parallel GC](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_9.html#ch01lev1sec2)
    1. [Serial GC](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_9.html#ch01lev1sec3)
    1. [Concurrent Mark Sweep (CMS) GC](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_9.html#ch01lev1sec4)
        1. [Summary of the Collectors](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_9.html#ch01lev2sec1)
    1. [Garbage First (G1) GC](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_9.html#ch01lev1sec5)
        1. [G1 Design](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_9.html#ch01lev2sec2)
        1. [Humongous Objects](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_9.html#ch01lev2sec3)
        1. [Full Garbage Collections](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_9.html#ch01lev2sec4)
        1. [Concurrent Cycle](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_9.html#ch01lev2sec5)
        1. [Heap Sizing](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_9.html#ch01lev2sec6)
    1. [References](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_9.html#ch01lev1sec6)
1. [2. Garbage First Garbage Collector in Depth](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_10.html#ch02)
    1. [Background](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_10.html#ch02lev1sec1)
    1. [Garbage Collection in G1](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_10.html#ch02lev1sec2)
    1. [The Young Generation](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_10.html#ch02lev1sec3)
    1. [A Young Collection Pause](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_10.html#ch02lev1sec4)
    1. [Object Aging and the Old Generation](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_10.html#ch02lev1sec5)
    1. [Humongous Regions](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_10.html#ch02lev1sec6)
    1. [A Mixed Collection Pause](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_10.html#ch02lev1sec7)
    1. [Collection Sets and Their Importance](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_10.html#ch02lev1sec8)
    1. [Remembered Sets and Their Importance](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_10.html#ch02lev1sec9)
        1. [Concurrent Refinement Threads and Barriers](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_10.html#ch02lev2sec1)
    1. [Concurrent Marking in G1 GC](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_10.html#ch02lev1sec10)
    1. [Stages of Concurrent Marking](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_10.html#ch02lev1sec11)
        1. [Initial Mark](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_10.html#ch02lev2sec2)
        1. [Root Region Scanning](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_10.html#ch02lev2sec3)
        1. [Concurrent Marking](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_10.html#ch02lev2sec4)
        1. [Remark](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_10.html#ch02lev2sec5)
        1. [Cleanup](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_10.html#ch02lev2sec6)
    1. [Evacuation Failures and Full Collection](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_10.html#ch02lev1sec12)
    1. [References](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_10.html#ch02lev1sec13)
1. [3. Garbage First Garbage Collector Performance Tuning](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_11.html#ch03)
    1. [The Stages of a Young Collection](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_11.html#ch03lev1sec1)
        1. [Start of All Parallel Activities](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_11.html#ch03lev2sec1)
        1. [External Root Regions](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_11.html#ch03lev2sec2)
        1. [Remembered Sets and Processed Buffers](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_11.html#ch03lev2sec3)
        1. [Summarizing Remembered Sets](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_11.html#ch03lev2sec4)
        1. [Evacuation and Reclamation](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_11.html#ch03lev2sec5)
        1. [Termination](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_11.html#ch03lev2sec6)
        1. [Parallel Activity Outside of GC](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_11.html#ch03lev2sec7)
        1. [Summarizing All Parallel Activities](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_11.html#ch03lev2sec8)
        1. [Start of All Serial Activities](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_11.html#ch03lev2sec9)
        1. [Other Serial Activities](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_11.html#ch03lev2sec10)
    1. [Young Generation Tunables](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_11.html#ch03lev1sec2)
    1. [Concurrent Marking Phase Tunables](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_11.html#ch03lev1sec3)
    1. [A Refresher on the Mixed Garbage Collection Phase](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_11.html#ch03lev1sec4)
    1. [The Taming of a Mixed Garbage Collection Phase](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_11.html#ch03lev1sec5)
    1. [Avoiding Evacuation Failures](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_11.html#ch03lev1sec6)
    1. [Reference Processing](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_11.html#ch03lev1sec7)
        1. [Observing Reference Processing](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_11.html#ch03lev2sec11)
        1. [Reference Processing Tuning](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_11.html#ch03lev2sec12)
    1. [References](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_11.html#ch03lev1sec8)
1. [4. The Serviceability Agent](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_12.html#ch04)
    1. [What Is the Serviceability Agent?](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_12.html#ch04lev1sec1)
    1. [Why Do We Need the SA?](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_12.html#ch04lev1sec2)
    1. [SA Components](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_12.html#ch04lev1sec3)
    1. [SA Binaries in the JDK](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_12.html#ch04lev1sec4)
    1. [JDK Versions with Complete SA Binaries](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_12.html#ch04lev1sec5)
    1. [How the SA Understands HotSpot VM Data Structures](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_12.html#ch04lev1sec6)
    1. [SA Version Matching](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_12.html#ch04lev1sec7)
    1. [The Serviceability Agent Debugging Tools](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_12.html#ch04lev1sec8)
        1. [HSDB](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_12.html#ch04lev2sec1)
        1. [HSDB Tools](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_12.html#ch04lev2sec2)
        1. [CLHSDB](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_12.html#ch04lev2sec3)
        1. [Some Other Tools](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_12.html#ch04lev2sec4)
    1. [Core Dump or Crash Dump Files](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_12.html#ch04lev1sec9)
    1. [Debugging Transported Core Files](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_12.html#ch04lev1sec10)
        1. [Shared Library Problems with the SA](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_12.html#ch04lev2sec5)
        1. [Eliminate Shared Library Problems](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_12.html#ch04lev2sec6)
    1. [System Properties for the Serviceability Agent](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_12.html#ch04lev1sec11)
    1. [Environment Variables for the Serviceability Agent](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_12.html#ch04lev1sec12)
    1. [JDI Implementation](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_12.html#ch04lev1sec13)
    1. [Extending Serviceability Agent Tools](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_12.html#ch04lev1sec14)
    1. [Serviceability Agent Plugin for VisualVM](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_12.html#ch04lev1sec15)
        1. [How to Install the SA-Plugin in VisualVM](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_12.html#ch04lev2sec7)
        1. [How to Use the SA-Plugin](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_12.html#ch04lev2sec8)
        1. [SA-Plugin Utilities](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_12.html#ch04lev2sec9)
    1. [Troubleshooting Problems Using the SA](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_12.html#ch04lev1sec16)
        1. [Diagnosing OutOfMemoryError](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_12.html#ch04lev2sec10)
        1. [Diagnosing a Java-Level Deadlock](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_12.html#ch04lev2sec11)
        1. [Postmortem Analysis of a HotSpot VM Crash](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_12.html#ch04lev2sec12)
1. [Appendix: Additional HotSpot VM Command-Line Options of Interest](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_13.html#app01)
1. [Index](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_14.html#index)
1. [Code Snippets](https://ebookreading.net/view/book/Java%C2%AE+Performance+Companion-EB9780133796896_16.html#ch02_images)
