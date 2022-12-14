![Cover image for Roslyn Cookbook](https://imgdetail.ebookreading.net/cover/cover/software_development/EB9781787286832.jpg)

[Roslyn Cookbook](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_1.html "Roslyn Cookbook")
====================================================================================================================

Author : [Manish Vasani](https://ebookreading.net/search/author/Manish+Vasani)

Release Date : 2017/07/01

ISBN : 9781787286832

Topic : [Software Development](https://ebookreading.net/search/category/software-development)

Book Description
-----------------

 Use Roslyn as a service to write powerful extensions and tools and use them in Visual Studio to improve code quality and maintain your source code more effectively.
About This Book
Use Roslyn extensions and tools in Visual Studio to enforce "house rules" on code and fix security and performance vulnerabilities in your code.Write Roslyn extensions using the Roslyn service API to help developers enforce conventions and design idioms.Improve developer productivity by using Roslyn-based agile development features in Visual Studio, such as live unit testing, C# interactive and scripting.Contribute to the C# language and compiler tool chain to analyze and edit code.Who This Book Is For
.NET Developers and architects, who are interested in taking full advantage of the Roslyn based extensions and tools to improve the development processes, will find this book useful. Roslyn contributors, i.e. the producers and C# community developers, will also find this book useful
What You Will Learn
Write extensions to analyze source code and report warnings and errors.Edit C# source code to fix compiler/analyzer diagnostics or refactor source code.Improve code maintenance and readability by using analyzers and code fixes.Catch security and performance issues by using PUMA scan analyzers and FxCop analyzers.Perform Live Unit tests in Visual Studio.Use C# interactive and scripting in Visual Studio.Design a new C# language feature and implement various compiler phases for a new language feature.Write command line tools to analyze and edit C# code.In Detail
Open-sourcing the C# and Visual Basic compilers is one of the most appreciated things by the .NET community, especially as it exposes rich code analysis APIs to analyze and edit code. If you want to use Roslyn API to write powerful extensions and contribute to the C# developer tool chain, then this book is for you. Additionally, if you are just a .NET developer and want to use this rich Roslyn-based functionality in Visual Studio to improve the code quality and maintenance of your code base, then this book is also for you.
This book is divided into the following broad modules:
Writing and consuming analyzers/fixers (Chapters 1 - 5): You will learn to write different categories of Roslyn analyzers and harness and configure analyzers in your C# projects to catch quality, security and performance issues. Moving ahead, you will learn how to improve code maintenance and readability by using code fixes and refactorings and also learn how to write them.Using Roslyn-based agile development features (Chapters 6 and 7): You will learn how to improve developer productivity in Visual Studio by using features such as live unit testing, C# interactive and scripting.Contributing to the C# language and compiler tool chain (Chapters 8 - 10): You will see the power of open-sourcing the Roslyn compiler via the simple steps this book provides; thus, you will contribute a completely new C# language feature and implement it in the Roslyn compiler codebase. Finally, you will write simple command line tools based on the Roslyn service API to analyze and edit C# code.Style and approach
This book takes a recipe-based approach, teaching you how to perform various hacks with the Compiler API in your hands.
        Show and hide more                
Table of Contents
-----------------

1. [Preface](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_14.html)
    1. [What this book covers](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_15.html)
    1. [What you need for this book](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_16.html)
    1. [Who this book is for](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_17.html)
    1. [Conventions](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_18.html)
    1. [Reader feedback](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_19.html)
    1. [Customer support](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_20.html)
        1. [Downloading the example code](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_21.html)
        1. [Downloading the color images of this book](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_22.html)
        1. [Errata](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_23.html)
        1. [Piracy](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_24.html)
        1. [Questions](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_25.html)
1. [Writing Diagnostic Analyzers](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_26.html)
    1. [Introduction](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_27.html)
    1. [Creating, debugging, and executing an analyzer project in Visual Studio](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_28.html)
        1. [Getting ready](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_29.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_30.html)
        1. [How it works...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_31.html)
    1. [Creating a symbol analyzer to report issues about symbol declarations](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_32.html)
        1. [Getting ready](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_33.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_34.html)
        1. [How it works...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_35.html)
        1. [There s more...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_36.html)
        1. [See also](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_37.html)
    1. [Creating a syntax node analyzer to report issues about language syntax](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_38.html)
        1. [Getting ready](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_39.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_40.html)
        1. [How it works...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_41.html)
    1. [Creating a syntax tree analyzer to analyze the source file and report syntax issues](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_42.html)
        1. [Getting ready](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_43.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_44.html)
        1. [How it works...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_45.html)
    1. [Creating a method body analyzer to analyze whole method and report issues](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_46.html)
        1. [Getting ready](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_47.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_48.html)
        1. [How it works...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_49.html)
    1. [Creating a compilation analyzer to analyze whole compilation and report issues](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_50.html)
        1. [Getting ready](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_51.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_52.html)
        1. [How it works...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_53.html)
    1. [Writing unit tests for an analyzer project](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_54.html)
        1. [Getting ready](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_55.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_56.html)
        1. [How it works...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_57.html)
        1. [See also](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_58.html)
    1. [Publishing NuGet package and VSIX for an analyzer project](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_59.html)
        1. [Getting ready](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_60.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_61.html)
1. [Consuming Diagnostic Analyzers in .NET Projects](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_62.html)
    1. [Introduction](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_63.html)
    1. [Searching and installing analyzers through the NuGet package manager](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_64.html)
        1. [Getting ready](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_65.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_66.html)
    1. [Searching and installing VSIX analyzers through the VS extension gallery](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_67.html)
        1. [Getting ready](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_68.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_69.html)
    1. [Viewing and configuring analyzers in solution explorer in Visual Studio](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_70.html)
        1. [Getting ready](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_71.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_72.html)
        1. [How it works...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_73.html)
    1. [Using the ruleset file and Rule Set editor to configure analyzers](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_74.html)
        1. [Getting ready](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_75.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_76.html)
        1. [How it works...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_77.html)
        1. [There&#39;s more...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_78.html)
1. [Writing IDE Code Fixes, Refactorings, and Intellisense Completion Providers](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_79.html)
    1. [Introduction](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_80.html)
    1. [Creating, debugging, and executing a CodeFixProvider to fix a compiler warning](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_81.html)
        1. [Getting ready](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_82.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_83.html)
        1. [How it works...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_84.html)
    1. [Applying batch code fixes (FixAll) across different scopes: document, project, and solution](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_85.html)
        1. [Getting ready](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_86.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_87.html)
    1. [Creating a custom FixAllProvider to fix all occurrences of an issue across a scope](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_88.html)
        1. [Getting ready](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_89.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_90.html)
        1. [How it works...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_91.html)
    1. [Creating a CodeRefactoringProvider to refactor source code to recommend using C# 7.0 tuples](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_92.html)
        1. [Getting ready](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_93.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_94.html)
        1. [How it works...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_95.html)
        1. [There s more...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_96.html)
    1. [Creating a CompletionProvider to provide additional intellisense items while editing code.](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_97.html)
        1. [Getting ready](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_98.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_99.html)
        1. [How it works...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_100.html)
    1. [Writing unit tests for a CodeFixProvider](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_101.html)
        1. [Getting ready](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_102.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_103.html)
        1. [How it works...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_104.html)
1. [Improving Code Maintenance of C# Code Base](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_105.html)
    1. [Introduction](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_106.html)
    1. [Configuring C# code style rules built into Visual Studio 2017](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_107.html)
        1. [Getting ready](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_108.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_109.html)
        1. [How it works...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_110.html)
        1. [There is more...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_111.html)
    1. [Using the .editorconfig file for configuration of code style rules](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_112.html)
        1. [Getting ready](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_113.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_114.html)
        1. [How it works...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_115.html)
    1. [Using the public API analyzer for API surface maintenance](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_116.html)
        1. [Getting ready](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_117.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_118.html)
        1. [How it works...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_119.html)
        1. [There&#39;s more...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_120.html)
    1. [Using third-party StyleCop analyzers for code style rules](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_121.html)
        1. [Getting ready](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_122.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_123.html)
        1. [How it works...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_124.html)
1. [Catch Security Vulnerabilities and Performance Issues in C# Code](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_125.html)
    1. [Introduction](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_126.html)
    1. [Identifying configuration-related security vulnerabilities in web applications](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_127.html)
        1. [Getting ready](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_128.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_129.html)
        1. [How it works...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_130.html)
    1. [Identifying cross-site scripting vulnerabilities in view markup files (.cshtml, .aspx files) in web applications](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_131.html)
        1. [Getting ready](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_132.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_133.html)
        1. [How it works...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_134.html)
    1. [Identifying insecure method calls that can lead to SQL and LDAP injection attacks](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_135.html)
        1. [Getting ready](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_136.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_137.html)
        1. [How it works...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_138.html)
    1. [Identifying weak password protection and management in web applications](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_139.html)
        1. [Getting ready](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_140.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_141.html)
    1. [Identifying weak validation of data from external components to prevent attacks such as cross-site request forgery and path tampering](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_142.html)
        1. [Getting ready](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_143.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_144.html)
    1. [Identifying performance improvements to source code using FxCop analyzers](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_145.html)
        1. [Getting ready](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_146.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_147.html)
        1. [How it works...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_148.html)
1. [Live Unit Testing in Visual Studio Enterprise](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_149.html)
    1. [Introduction](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_150.html)
    1. [Running live unit tests in Visual Studio for unit test projects based on NUnit, XUnit, and MSTest frameworks](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_151.html)
        1. [Getting started](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_152.html)
        1. [How to do it](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_153.html)
    1. [Viewing and navigating live unit test results](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_154.html)
        1. [Getting started](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_155.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_156.html)
    1. [Understanding incremental live unit test execution with code changes](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_157.html)
        1. [Getting started](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_158.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_159.html)
        1. [How it works](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_160.html)
    1. [Understanding Start/Stop/Pause/Continue/Restart functionality for fine grain control of LUT](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_161.html)
        1. [Getting started](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_162.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_163.html)
    1. [Including and excluding subset of tests for live execution](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_164.html)
        1. [Getting started](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_165.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_166.html)
    1. [Configuring different options for live unit testing using the Tools Options dialog](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_167.html)
        1. [Getting started](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_168.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_169.html)
1. [C# Interactive and Scripting](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_170.html)
    1. [Introduction](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_171.html)
    1. [Writing a simple C# script and evaluating it within the Visual Studio interactive window](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_172.html)
        1. [Getting started](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_173.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_174.html)
        1. [How it works...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_175.html)
    1. [Using script directives and REPL commands in the C# interactive window](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_176.html)
        1. [Getting started](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_177.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_178.html)
    1. [Using keyboard shortcuts for evaluating and navigating through script sessions in the C# interactive window](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_179.html)
        1. [Getting started](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_180.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_181.html)
    1. [Initializing the C# interactive session from the existing C# project](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_182.html)
        1. [Getting started](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_183.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_184.html)
    1. [Executing the C# script on a Visual Studio developer command prompt using csi.exe](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_185.html)
        1. [Getting started](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_186.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_187.html)
    1. [Using the Roslyn scripting API to execute C# code snippets](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_188.html)
        1. [Getting started](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_189.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_190.html)
        1. [How it works...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_191.html)
1. [Contribute Simple Functionality to Roslyn C# Compiler Open Source Code](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_192.html)
    1. [Introduction](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_193.html)
    1. [Setting up Roslyn enlistment](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_194.html)
        1. [Getting Started](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_195.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_196.html)
    1. [Implementing a new syntax error in the C# compiler code base](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_197.html)
        1. [Getting Started](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_198.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_199.html)
        1. [How it works...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_200.html)
    1. [Implementing a new semantic error in the C# compiler code base](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_201.html)
        1. [Getting Started](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_202.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_203.html)
        1. [How it works...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_204.html)
    1. [Writing unit tests for a new error in the C# compiler code base](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_205.html)
        1. [Getting Started](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_206.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_207.html)
    1. [Using Roslyn Syntax Visualizer to view Roslyn syntax tokens and nodes for a source file](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_208.html)
        1. [Getting Started](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_209.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_210.html)
    1. [Sending a Roslyn pull request to contribute to next version of C# compiler and VS IDE](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_211.html)
        1. [Getting Started](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_212.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_213.html)
1. [Design and Implement a New C# Language Feature](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_214.html)
    1. [Introduction](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_215.html)
        1. [New language feature: Switch Operator (?::)](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_216.html)
    1. [Designing syntax and grammar for a new C# language feature](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_217.html)
        1. [Getting Started](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_218.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_219.html)
        1. [How it works...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_220.html)
    1. [Implementing parser support for a new C# language feature](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_221.html)
        1. [Getting Started](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_222.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_223.html)
        1. [How it works...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_224.html)
    1. [Implementing binding/semantic analysis support for a new C# language feature](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_225.html)
        1. [Getting Started](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_226.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_227.html)
        1. [How it works...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_228.html)
        1. [There&#39;s more...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_229.html)
    1. [Implementing lowering/code generation support for a new C# language feature](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_230.html)
        1. [Getting Started](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_231.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_232.html)
        1. [How it works...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_233.html)
    1. [Writing unit tests for C# parsing, binding, and codegen phases](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_234.html)
        1. [Getting Started](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_235.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_236.html)
1. [Command-Line Tools Based on Roslyn API](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_237.html)
    1. [Introduction](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_238.html)
    1. [Writing an application based on the Compiler Syntax API to parse and transform source files](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_239.html)
        1. [Getting started](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_240.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_241.html)
        1. [How it works...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_242.html)
    1. [Writing an application based on the Compiler Semantic API to display diagnostics and overload resolution results](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_243.html)
        1. [Getting started](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_244.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_245.html)
        1. [How it works...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_246.html)
    1. [Writing an application based on the Compiler Analyzer API to execute diagnostic analyzers and display analyzer diagnostics](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_247.html)
        1. [Getting started](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_248.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_249.html)
        1. [How it works...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_250.html)
    1. [Writing an application based on the Workspaces API to format and simplify all source files in the solution](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_251.html)
        1. [Getting started](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_252.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_253.html)
        1. [How it works...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_254.html)
    1. [Writing an application based on the Workspaces API to edit projects in a solution and display project properties](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_255.html)
        1. [Getting started](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_256.html)
        1. [How to do it...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_257.html)
        1. [How it works...](https://ebookreading.net/view/book/Roslyn+Cookbook-EB9781787286832_258.html)
