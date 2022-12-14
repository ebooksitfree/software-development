![Cover image for Code Quality](https://imgdetail.ebookreading.net/cover/cover/software_development/EB0321166078.jpg)

[Code Quality](https://ebookreading.net/view/book/Code+Quality-EB0321166078_1.html "Code Quality")
====================================================================================================================

Author : [Diomidis Spinellis](https://ebookreading.net/search/author/Diomidis+Spinellis)

Release Date : 2006/04/01

ISBN : 0321166078

Topic : [Software Development](https://ebookreading.net/search/category/software-development)

Book Description
-----------------

Diomidis Spinellis' first book, Code Reading, showed programmers how to understand and modify key functional properties of software. Code Quality focuses on non-functional properties, demonstrating how to meet such critical requirements as reliability, security, portability, and maintainability, as well as efficiency in time and space.
Spinellis draws on hundreds of examples from open source projects--such as the Apache web and application servers, the BSD Unix systems, and the HSQLDB Java database--to illustrate concepts and techniques that every professional software developer will be able to appreciate and apply immediately.
Complete files for the open source code illustrated in this book are available online at: http://www.spinellis.gr/codequality/

              
Table of Contents
-----------------

1. [Copyright](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html)
    1. [Dedication](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ded01)
1. [Effective Software Development Series: Scott Meyers, Consulting Editor](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html)
    1. [Titles in the Series](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#pref01lev1sec1)
1. [List of Tables](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html)
1. [List of Figures](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html)
1. [Foreword](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html)
1. [Preface](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html)
    1. [Content and Supplementary Material](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#pref05lev1sec1)
    1. [Acknowledgments](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#pref05lev1sec2)
1. [1. Introduction](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html)
    1. [1.1. Software Quality](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch01lev1sec1)
        1. [1.1.1. Quality Through the Eyes of the User, the Builder, and the Manager](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch01lev2sec1)
        1. [1.1.2. Quality Attributes](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch01lev2sec2)
        1. [1.1.3. A World of Tensions](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch01lev2sec3)
    1. [1.2. How to Read This Book](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch01lev1sec2)
        1. [1.2.1. Typographical Conventions](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch01lev2sec4)
        1. [1.2.2. Diagrams](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch01lev2sec5)
        1. [1.2.3. Charts](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch01lev2sec6)
        1. [1.2.4. Assembly Code](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch01lev2sec7)
        1. [1.2.5. Exercises](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch01lev2sec8)
        1. [1.2.6. Supplementary Material](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch01lev2sec9)
        1. [1.2.7. Tools](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch01lev2sec10)
    1. [Further Reading](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch01lev1sec3)
1. [2. Reliability](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html)
    1. [2.1. Input Problems](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev1sec1)
    1. [2.2. Output Problems](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev1sec2)
        1. [2.2.1. Incomplete or Missing Output](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev2sec1)
        1. [2.2.2. Correct Results at the Wrong Time](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev2sec2)
        1. [2.2.3. Wrong Format](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev2sec3)
    1. [2.3. Logic Problems](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev1sec3)
        1. [2.3.1. Off-by-One Errors and Loop Iterations](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev2sec4)
        1. [2.3.2. Neglected Extreme Conditions](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev2sec5)
        1. [2.3.3. Forgotten Cases, Condition Tests, or Steps](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev2sec6)
        1. [2.3.4. Missing Methods](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev2sec7)
        1. [2.3.5. Unnecessary Functionality](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev2sec8)
        1. [2.3.6. Misinterpretation](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev2sec9)
    1. [2.4. Computation Problems](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev1sec4)
        1. [2.4.1. Incorrect Algorithm or Computation](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev2sec10)
        1. [2.4.2. Incorrect Operand in an Expression](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev2sec11)
            1. [Uninitialized Variables](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev3sec1)
            1. [Dereferencing NULL](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev3sec2)
            1. [Using Concrete Types](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev3sec3)
            1. [Abusing the Type System](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev3sec4)
        1. [2.4.3. Incorrect Operator in an Expression](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev2sec12)
        1. [2.4.4. Operator Precedence Problems](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev2sec13)
        1. [2.4.5. Overflow, Underflow, and Sign Conversion-Errors](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev2sec14)
    1. [2.5. Concurrency and Timing Problems](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev1sec5)
    1. [2.6. Interface Problems](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev1sec6)
        1. [2.6.1. Incorrect Routine or Arguments](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev2sec15)
        1. [2.6.2. Failure to Test a Return Value](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev2sec16)
        1. [2.6.3. Missing Error Detection or Recovery](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev2sec17)
        1. [2.6.4. Resource Leaks](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev2sec18)
        1. [2.6.5. Misuse of Object-Oriented Facilities](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev2sec19)
    1. [2.7. Data-Handling Problems](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev1sec7)
        1. [2.7.1. Incorrect Data Initialization](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev2sec20)
        1. [2.7.2. Referencing the Wrong Data Variable](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev2sec21)
        1. [2.7.3. Out-of-Bounds References](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev2sec22)
        1. [2.7.4. Incorrect Subscripting](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev2sec23)
        1. [2.7.5. Incorrect Scaling or Data Units](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev2sec24)
        1. [2.7.6. Incorrect Data Packing or Unpacking](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev2sec25)
        1. [2.7.7. Inconsistent Data](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev2sec26)
    1. [2.8. Fault Tolerance](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev1sec8)
        1. [2.8.1. Management Strategy](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev2sec27)
        1. [2.8.2. Redundancy in Space](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev2sec28)
        1. [2.8.3. Redundancy in Time](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev2sec29)
        1. [2.8.4. Recoverability](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev2sec30)
    1. [Advice to Take Home](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev1sec9)
    1. [Further Reading](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch02lev1sec10)
1. [3. Security](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html)
    1. [3.1. Vulnerable Code](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch03lev1sec1)
    1. [3.2. The Buffer Overflow](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch03lev1sec2)
    1. [3.3. Race Conditions](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch03lev1sec3)
    1. [3.4. Problematic APIs](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch03lev1sec4)
        1. [3.4.1. Functions Susceptible to Buffer Overflows](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch03lev2sec1)
        1. [3.4.2. Format String Vulnerabilities](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch03lev2sec2)
        1. [3.4.3. Path and Shell Metacharacter Vulnerabilities](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch03lev2sec3)
        1. [3.4.4. Temporary Files](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch03lev2sec4)
        1. [3.4.5. Functions Unsuitable for Cryptographic Use](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch03lev2sec5)
        1. [3.4.6. Forgeable Data](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch03lev2sec6)
    1. [3.5. Untrusted Input](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch03lev1sec5)
    1. [3.6. Result Verification](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch03lev1sec6)
    1. [3.7. Data and Privilege Leakage](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch03lev1sec7)
        1. [3.7.1. Data Leakage](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch03lev2sec7)
        1. [3.7.2. Privilege Leakage](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch03lev2sec8)
        1. [3.7.3. The Java Approach](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch03lev2sec9)
        1. [3.7.4. Isolating Privileged Code](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch03lev2sec10)
    1. [3.8. Trojan Horse](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch03lev1sec8)
    1. [3.9. Tools](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch03lev1sec9)
    1. [Advice to Take Home](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch03lev1sec10)
    1. [Further Reading](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch03lev1sec11)
1. [4. Time Performance](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html)
    1. [4.1. Measurement Techniques](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch04lev1sec1)
        1. [4.1.1. Workload Characterization](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch04lev2sec1)
        1. [4.1.2. I/O-Bound Tasks](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch04lev2sec2)
        1. [4.1.3. Kernel-Bound Tasks](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch04lev2sec3)
        1. [4.1.4. CPU-Bound Tasks and Profiling Tools](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch04lev2sec4)
    1. [4.2. Algorithm Complexity](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch04lev1sec2)
    1. [4.3. Stand-Alone Code](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch04lev1sec3)
    1. [4.4. Interacting with the Operating System](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch04lev1sec4)
    1. [4.5. Interacting with Peripherals](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch04lev1sec5)
    1. [4.6. Involuntary Interactions](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch04lev1sec6)
    1. [4.7. Caching](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch04lev1sec7)
        1. [4.7.1. A Simple System Call Cache](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch04lev2sec5)
        1. [4.7.2. Replacement Strategies](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch04lev2sec6)
        1. [4.7.3. Precomputing Results](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch04lev2sec7)
    1. [Advice to Take Home](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch04lev1sec8)
    1. [Further Reading](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch04lev1sec9)
1. [5. Space Performance](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html)
    1. [5.1. Data](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch05lev1sec1)
        1. [5.1.1. Basic Data Types](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch05lev2sec1)
        1. [5.1.2. Aggregate Data Types](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch05lev2sec2)
            1. [Arrays](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch05lev3sec1)
            1. [Structures](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch05lev3sec2)
        1. [5.1.3. Alignment](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch05lev2sec3)
        1. [5.1.4. Objects](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch05lev2sec4)
    1. [5.2. Memory Organization](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch05lev1sec2)
    1. [5.3. Memory Hierarchies](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch05lev1sec3)
        1. [5.3.1. Main Memory and Its Caches](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch05lev2sec5)
        1. [5.3.2. Disk Cache and Banked Memory](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch05lev2sec6)
        1. [5.3.3. Swap Area and File-Based Disk Storage](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch05lev2sec7)
    1. [5.4. The Process/Operating System Interface](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch05lev1sec4)
        1. [5.4.1. Memory Allocation](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch05lev2sec8)
        1. [5.4.2. Memory Mapping](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch05lev2sec9)
        1. [5.4.3. Data Mapping](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch05lev2sec10)
        1. [5.4.4. Code Mapping](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch05lev2sec11)
        1. [5.4.5. Accessing Hardware Resources](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch05lev2sec12)
        1. [5.4.6. Interprocess Communication](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch05lev2sec13)
    1. [5.5. Heap Memory Management](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch05lev1sec5)
        1. [5.5.1. Heap Fragmentation](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch05lev2sec14)
        1. [5.5.2. Heap Profiling](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch05lev2sec15)
        1. [5.5.3. Memory Leaks](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch05lev2sec16)
        1. [5.5.4. Garbage Collection](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch05lev2sec17)
    1. [5.6. Stack Memory Management](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch05lev1sec6)
        1. [5.6.1. The Stack Frame](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch05lev2sec18)
        1. [5.6.2. Stack Space](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch05lev2sec19)
    1. [5.7. Code](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch05lev1sec7)
        1. [5.7.1. Design Time](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch05lev2sec20)
        1. [5.7.2. Coding Time](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch05lev2sec21)
        1. [5.7.3. Build Time](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch05lev2sec22)
    1. [Advice to Take Home](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch05lev1sec8)
    1. [Further Reading](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch05lev1sec9)
1. [6. Portability](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html)
    1. [6.1. Operating Systems](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch06lev1sec1)
    1. [6.2. Hardware and Processor Architectures](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch06lev1sec2)
        1. [6.2.1. Data Type Properties](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch06lev2sec1)
        1. [6.2.2. Data Storage](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch06lev2sec2)
        1. [6.2.3. Machine-Specific Code](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch06lev2sec3)
    1. [6.3. Compilers and Language Extensions](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch06lev1sec3)
        1. [6.3.1. Compiler Bugs](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch06lev2sec4)
            1. [Nonstandard Extensions](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch06lev3sec1)
            1. [New Language Features](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch06lev3sec2)
            1. [Binary Compatibility](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch06lev3sec3)
    1. [6.4. Graphical User Interfaces](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch06lev1sec4)
    1. [6.5. Internationalization and Localization](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch06lev1sec5)
        1. [6.5.1. Character Sets](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch06lev2sec5)
        1. [6.5.2. Locale](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch06lev2sec6)
        1. [6.5.3. Messages](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch06lev2sec7)
    1. [Advice to Take Home](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch06lev1sec6)
    1. [Further Reading](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch06lev1sec7)
1. [7. Maintainability](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html)
    1. [7.1. Measuring Maintainability](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev1sec1)
        1. [7.1.1. The Maintainability Index](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev2sec1)
            1. [Applying Maintainability Metrics in Practice](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev3sec1)
        1. [7.1.2. Metrics for Object-Oriented Programs](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev2sec2)
            1. [Weighted Methods per Class](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev3sec2)
            1. [Depth of Inheritance Tree](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev3sec3)
            1. [Number of Children](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev3sec4)
            1. [Coupling Between Object Classes](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev3sec5)
            1. [Response for a Class](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev3sec6)
            1. [Lack of Cohesion in Methods](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev3sec7)
            1. [Applying Object-Oriented Metrics in Practice](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev3sec8)
        1. [7.1.3. Dependency Metrics on Packages](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev2sec3)
    1. [7.2. Analyzability](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev1sec2)
        1. [7.2.1. Consistency](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev2sec4)
        1. [7.2.2. Expression Formatting](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev2sec5)
        1. [7.2.3. Statement Formatting](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev2sec6)
        1. [7.2.4. Naming Conventions](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev2sec7)
        1. [7.2.5. Statement-Level Comments](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev2sec8)
        1. [7.2.6. Versioning Comments](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev2sec9)
        1. [7.2.7. Visual Structure: Blocks and Indentation](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev2sec10)
        1. [7.2.8. Length of Expressions, Functions, and Methods](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev2sec11)
        1. [7.2.9. Control Structures](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev2sec12)
        1. [7.2.10. Boolean Expressions](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev2sec13)
        1. [7.2.11. Recognizability and Cohesion](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev2sec14)
        1. [7.2.12. Dependencies and Coupling](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev2sec15)
            1. [Data Coupling](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev3sec9)
            1. [Stamp Coupling](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev3sec10)
            1. [Control Coupling](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev3sec11)
            1. [Temporal Coupling](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev3sec12)
            1. [Common Coupling](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev3sec13)
            1. [External Coupling](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev3sec14)
            1. [Content Coupling](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev3sec15)
        1. [7.2.13. Code Block Comments](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev2sec16)
        1. [7.2.14. Data Declaration Comments](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev2sec17)
        1. [7.2.15. Appropriate Identifier Names](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev2sec18)
        1. [7.2.16. Locality of Dependencies](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev2sec19)
        1. [7.2.17. Ambiguity](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev2sec20)
        1. [7.2.18. Reviewability](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev2sec21)
    1. [7.3. Changeability](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev1sec3)
        1. [7.3.1. Identification](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev2sec22)
            1. [Intuitive Names](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev3sec16)
            1. [The Role of Comments](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev3sec17)
            1. [Polymorphic Abstraction](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev3sec18)
        1. [7.3.2. Separation](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev2sec23)
            1. [When Coupling Interferes with Separability](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev3sec19)
            1. [Increasing Separability Through Design Patterns](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev3sec20)
            1. [Cohesive Design Abstractions](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev3sec21)
            1. [Problems with Needless Repetition](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev3sec22)
            1. [Hard-Coded Constants](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev3sec23)
            1. [Comment Formatting](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev3sec24)
    1. [7.4. Stability](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev1sec4)
        1. [7.4.1. Encapsulation and Data Hiding](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev2sec24)
            1. [Declare Variables within the Innermost Block that Uses Them](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev3sec25)
            1. [Declare Class Members with the Least Visibility Required](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev3sec26)
            1. [Encapsulate Groups of Related Classes Inside Modules](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev3sec27)
            1. [Avoid Global Variables and Functions](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev3sec28)
            1. [Use Components and Separate Processes to Isolate Large, Relatively Independent Subsystems](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev3sec29)
        1. [7.4.2. Data Abstraction](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev2sec25)
        1. [7.4.3. Type Checking](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev2sec26)
        1. [7.4.4. Compile-Time Assertions](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev2sec27)
        1. [7.4.5. Runtime Checks and Inspection-Time Assertions](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev2sec28)
    1. [7.5. Testability](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev1sec5)
        1. [7.5.1. Unit Testing](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev2sec29)
        1. [7.5.2. Integration Testing](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev2sec30)
            1. [Test Harness](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev3sec30)
            1. [Test Stub](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev3sec31)
        1. [7.5.3. System Testing](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev2sec31)
        1. [7.5.4. Test Coverage Analysis](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev2sec32)
        1. [7.5.5. Incidental Testing](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev2sec33)
            1. [Assertions](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev3sec32)
            1. [Defensive Coding](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev3sec33)
            1. [Logging and Debug Messages](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev3sec34)
    1. [7.6. Effects of the Development Environment](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev1sec6)
        1. [7.6.1. Incremental Builds](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev2sec34)
        1. [7.6.2. Tuning Build Performance](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev2sec35)
    1. [Advice to Take Home](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev1sec7)
    1. [Further Reading](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch07lev1sec8)
1. [8. Floating-Point Arithmetic](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html)
    1. [8.1. Floating-Point Representation](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch08lev1sec1)
        1. [8.1.1. Measuring Error](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch08lev2sec1)
        1. [8.1.2. Rounding](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch08lev2sec2)
        1. [8.1.3. Memory Format](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch08lev2sec3)
        1. [8.1.4. Normalization and the Implied 1-Bit](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch08lev2sec4)
        1. [8.1.5. Exponent Biasing](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch08lev2sec5)
        1. [8.1.6. Negative Numbers](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch08lev2sec6)
        1. [8.1.7. Denormal Numbers](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch08lev2sec7)
        1. [8.1.8. Special Values](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch08lev2sec8)
    1. [8.2. Rounding](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch08lev1sec2)
    1. [8.3. Overflow](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch08lev1sec3)
    1. [8.4. Underflow](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch08lev1sec4)
    1. [8.5. Cancellation](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch08lev1sec5)
    1. [8.6. Absorption](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch08lev1sec6)
    1. [8.7. Invalid Operations](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch08lev1sec7)
    1. [Advice to Take Home](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch08lev1sec8)
    1. [Further Reading](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html#ch08lev1sec9)
1. [A. Source Code Credits](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html)
1. [Bibliography](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html)
1. [Epigraph Credits](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html)
1. [Colophon](https://ebookreading.net/view/book/Code+Quality-EB0321166078_0.html)
