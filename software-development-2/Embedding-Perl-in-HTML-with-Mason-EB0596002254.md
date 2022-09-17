![Cover image for Embedding Perl in HTML with Mason](https://imgdetail.ebookreading.net/cover/cover/software_development/EB0596002254.jpg)

[Embedding Perl in HTML with Mason](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_1.html "Embedding Perl in HTML with Mason")
====================================================================================================================

Author : [Dave Rolsky](https://ebookreading.net/search/author/Dave+Rolsky),[ Ken Williams](https://ebookreading.net/search/author/+Ken+Williams)

Release Date : 2002/10/01

ISBN : 0596002254

Topic : [Software Development](https://ebookreading.net/search/category/software-development)

Book Description
-----------------

Mason doesn't aim to be the one true Perl-based templating system for building web sites, but it's led many programmers to abandon their custom solutions when they've seen how much easier using Mason can be. It's a powerful, open source, Perl-based web site development and delivery engine, with features that make it an ideal backend for high load sites serving dynamic content.  Mason uses a concept called components: a mix of HTML, Perl, and special Mason commands. These components can be entire web pages, or bits of HTML that can be embedded in top-level components.  Shared and reusable, these components greatly simplify site maintenance: when you change a shared component, you instantly change all pages that refer to it.Although using Mason isn't difficult, creating a Mason-based site can be tricky. Embedding Perl in HTML with Mason, written by members of Mason's core development team, shows you how to take advantage of Mason's strengths while avoiding the obstacles that inexperienced users may encounter.  Mason's unique features, when used properly, can streamline the design of a web site or application.  This concise book covers these features from several angles, and includes a study of the authors' sample site where these features are used.Embedding Perl in HTML with Mason shows you how to create large, complex, dynamically driven web sites that look good and are a snap to maintain. You'll learn how to visualize multiple Mason-based solutions to any given problem and select among them. The book covers the latest line of Mason development 1.1x, which has many new features, including line number reporting based on source files, sub-requests, and easier use as a CGI.  The only book to cover this important tool, Embedding Perl in HTML with Mason is essential reading for any Perl programmer who wants to simplify web site design. Learn how to use Mason, and you'll spend more time making things work, and less time reinventing the wheel.
              
Table of Contents
-----------------

1. [Foreword](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_3.html)
1. [Preface](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_4.html)
    1. [Intended Audience](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_4.html#perlhtmlmason-PREF-)
    1. [Requirements](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_4.html#perlhtmlmason-PREF-)
    1. [How to Read This Book](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_4.html#perlhtmlmason-PREF-)
    1. [Overview](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_4.html#perlhtmlmason-PREF-)
    1. [Other Resources](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_4.html#perlhtmlmason-PREF-)
    1. [Typographic Conventions](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_4.html#perlhtmlmason-PREF-)
    1. [We’d Like to Hear from You](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_4.html#perlhtmlmason-PREF-)
    1. [Open Publication License](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_4.html#perlhtmlmason-PREF-)
    1. [Acknowledgments](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_4.html#perlhtmlmason-PREF-)
1. [1. Introduction](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_5.html)
    1. [A First Example](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_5.html#perlhtmlmason-CHP-1)
    1. [The Main Features of Mason](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_5.html#perlhtmlmason-CHP-1)
        1. [Components: Modular Design Elements](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_5.html#perlhtmlmason-CHP-1)
        1. [Object-Style  Component Inheritance](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_5.html#perlhtmlmason-CHP-1)
        1. [Intelligent Caching Mechanisms](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_5.html#perlhtmlmason-CHP-1)
        1. [Integration with Apache and mod_perl](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_5.html#perlhtmlmason-CHP-1)
    1. [Alternatives to Mason](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_5.html#perlhtmlmason-CHP-1)
        1. [Embperl](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_5.html#perlhtmlmason-CHP-1)
        1. [Apache::ASP](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_5.html#perlhtmlmason-CHP-1)
        1. [HTML::Template](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_5.html#perlhtmlmason-CHP-1)
        1. [Text::Template](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_5.html#perlhtmlmason-CHP-1)
        1. [Template Toolkit](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_5.html#perlhtmlmason-CHP-1)
        1. [PHP](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_5.html#perlhtmlmason-CHP-1)
    1. [Philosophy](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_5.html#perlhtmlmason-CHP-1)
    1. [Getting Started with Mason](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_5.html#perlhtmlmason-CHP-1)
        1. [A Standalone Installation](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_5.html#perlhtmlmason-CHP-1)
        1. [A mod_perl Installation](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_5.html#perlhtmlmason-CHP-1)
        1. [Trying It Out](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_5.html#perlhtmlmason-CHP-1)
1. [2. Components](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_6.html)
    1. [Mason from 10,000 Feet](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_6.html#perlhtmlmason-CHP-2)
    1. [Core Concepts](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_6.html#perlhtmlmason-CHP-2)
    1. [Basic Component Syntax](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_6.html#perlhtmlmason-CHP-2)
        1. [Substitution Tags: &lt;% %&gt;](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_6.html#perlhtmlmason-CHP-2)
            1. [Escaping substitutions](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_6.html#perlhtmlmason-CHP-2)
        1. [Embedded Perl: % Lines and  &lt;%perl&gt; Blocks](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_6.html#perlhtmlmason-CHP-2)
        1. [Calling Other Components: &lt;&amp; &amp;&gt; Tags](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_6.html#perlhtmlmason-CHP-2)
            1. [Components called with content](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_6.html#perlhtmlmason-CHP-2)
        1. [Other Named Blocks](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_6.html#perlhtmlmason-CHP-2)
            1. [ &lt;%init&gt; blocks](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_6.html#perlhtmlmason-CHP-2)
            1. [ &lt;%args&gt; blocks](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_6.html#perlhtmlmason-CHP-2)
            1. [ &lt;%filter&gt; blocks](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_6.html#perlhtmlmason-CHP-2)
            1. [ &lt;%once&gt; blocks](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_6.html#perlhtmlmason-CHP-2)
            1. [ &lt;%cleanup&gt; blocks](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_6.html#perlhtmlmason-CHP-2)
            1. [ &lt;%text&gt; blocks](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_6.html#perlhtmlmason-CHP-2)
            1. [ &lt;%doc&gt; blocks](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_6.html#perlhtmlmason-CHP-2)
            1. [&lt;%flags&gt; and    &lt;%attr&gt; blocks](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_6.html#perlhtmlmason-CHP-2)
            1. [   &lt;%def&gt; and &lt;%method&gt; blocks](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_6.html#perlhtmlmason-CHP-2)
            1. [ &lt;%shared&gt; blocks](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_6.html#perlhtmlmason-CHP-2)
        1. [Escaping a  Newline](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_6.html#perlhtmlmason-CHP-2)
    1. [Component Arguments](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_6.html#perlhtmlmason-CHP-2)
        1. [&lt;%args&gt; Block Revisited](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_6.html#perlhtmlmason-CHP-2)
        1. [%ARGS](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_6.html#perlhtmlmason-CHP-2)
        1. [%ARGS Versus @_](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_6.html#perlhtmlmason-CHP-2)
        1. [Argument Examples](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_6.html#perlhtmlmason-CHP-2)
        1. [Arguments via Component Calls](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_6.html#perlhtmlmason-CHP-2)
        1. [Arguments via HTTP Requests](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_6.html#perlhtmlmason-CHP-2)
    1. [Component Return Values](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_6.html#perlhtmlmason-CHP-2)
    1. [Special Globals](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_6.html#perlhtmlmason-CHP-2)
        1. [ $m](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_6.html#perlhtmlmason-CHP-2)
        1. [ $r](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_6.html#perlhtmlmason-CHP-2)
    1. [Sample Component](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_6.html#perlhtmlmason-CHP-2)
1. [3. Special Components: Dhandlers and Autohandlers](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_7.html)
    1. [Dhandlers](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_7.html#perlhtmlmason-CHP-3)
        1. [Finer Control over Dhandlers](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_7.html#perlhtmlmason-CHP-3)
        1. [D   handlers and Apache Configuration](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_7.html#perlhtmlmason-CHP-3)
    1. [Autohandlers](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_7.html#perlhtmlmason-CHP-3)
        1. [Using Autohandlers for Initialization](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_7.html#perlhtmlmason-CHP-3)
        1. [Using Autohandlers as Filters](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_7.html#perlhtmlmason-CHP-3)
        1. [Inspecting the Wrapping Chain](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_7.html#perlhtmlmason-CHP-3)
    1. [Using Autohandlers and Dhandlers Together](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_7.html#perlhtmlmason-CHP-3)
1. [4. APIs](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_8.html)
    1. [Request Class and Object  API](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_8.html#perlhtmlmason-CHP-4)
        1. [Constructor Parameters](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_8.html#perlhtmlmason-CHP-4)
        1. [Calling Other Components](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_8.html#perlhtmlmason-CHP-4)
        1. [Aborting the Flow of Execution](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_8.html#perlhtmlmason-CHP-4)
        1. [The Wrapping Chain](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_8.html#perlhtmlmason-CHP-4)
        1. [Dhandler-Related Methods](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_8.html#perlhtmlmason-CHP-4)
        1. [Miscellaneous Methods](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_8.html#perlhtmlmason-CHP-4)
        1. [Introspection](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_8.html#perlhtmlmason-CHP-4)
        1. [Buffer-Related Methods](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_8.html#perlhtmlmason-CHP-4)
        1. [Caching](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_8.html#perlhtmlmason-CHP-4)
        1. [Subrequests](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_8.html#perlhtmlmason-CHP-4)
        1. [Methods Available Only When Using ApacheHandler](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_8.html#perlhtmlmason-CHP-4)
        1. [Methods Available When Using ApacheHandler or CGIHandler](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_8.html#perlhtmlmason-CHP-4)
        1. [Getting in Close with Buffers](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_8.html#perlhtmlmason-CHP-4)
    1. [Component Object API](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_8.html#perlhtmlmason-CHP-4)
        1. [Methods for File-based   Components](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_8.html#perlhtmlmason-CHP-4)
    1. [Buffers](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_8.html#perlhtmlmason-CHP-4)
1. [5. Advanced Features](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_9.html)
    1. [Subcomponents](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_9.html#perlhtmlmason-CHP-5)
    1. [Creating Components on the Fly](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_9.html#perlhtmlmason-CHP-5)
    1. [Sharing Data Among Component Sections](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_9.html#perlhtmlmason-CHP-5)
    1. [Methods and Attributes](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_9.html#perlhtmlmason-CHP-5)
        1. [Methods](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_9.html#perlhtmlmason-CHP-5)
        1. [Using Methods for Titles and Headers](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_9.html#perlhtmlmason-CHP-5)
        1. [Methods with Dynamic Content](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_9.html#perlhtmlmason-CHP-5)
        1. [Attributes](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_9.html#perlhtmlmason-CHP-5)
        1. [Top-Down Versus Bottom-Up Inheritance](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_9.html#perlhtmlmason-CHP-5)
    1. [Calling Components with Content Blocks](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_9.html#perlhtmlmason-CHP-5)
    1. [Advanced Inheritance](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_9.html#perlhtmlmason-CHP-5)
        1. [ Inheritance and  Multiple Component Roots](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_9.html#perlhtmlmason-CHP-5)
        1. [An Advanced Inheritance Example](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_9.html#perlhtmlmason-CHP-5)
    1. [Subrequests](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_9.html#perlhtmlmason-CHP-5)
        1. [A Caution About Autohandler Inheritance](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_9.html#perlhtmlmason-CHP-5)
1. [6. The Lexer, Compiler, Resolver, and Interpreter  Objects](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_10.html)
    1. [Passing Parameters to Mason Classes](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_10.html#perlhtmlmason-CHP-6)
    1. [The Lexer](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_10.html#perlhtmlmason-CHP-6)
    1. [The Compiler](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_10.html#perlhtmlmason-CHP-6)
        1. [Altering Every Component’s Content](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_10.html#perlhtmlmason-CHP-6)
        1. [Compiler Methods](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_10.html#perlhtmlmason-CHP-6)
    1. [The Resolver](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_10.html#perlhtmlmason-CHP-6)
    1. [The Interpreter](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_10.html#perlhtmlmason-CHP-6)
        1. [Request Parameters Passed to the Interpreter](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_10.html#perlhtmlmason-CHP-6)
1. [7. Using Mason with mod_perl](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_11.html)
    1. [Configuring Mason](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_11.html#perlhtmlmason-CHP-7)
        1. [Configuration via httpd.conf](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_11.html#perlhtmlmason-CHP-7)
        1. [Configuration via Custom Code](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_11.html#perlhtmlmason-CHP-7)
    1. [Document Root Versus the Component Root](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_11.html#perlhtmlmason-CHP-7)
    1. [Not OK](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_11.html#perlhtmlmason-CHP-7)
    1. [$r](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_11.html#perlhtmlmason-CHP-7)
    1. [ApacheHandler Parameters](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_11.html#perlhtmlmason-CHP-7)
    1. [To Autoflush or Not to Autoflush](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_11.html#perlhtmlmason-CHP-7)
    1. [Generating Something Besides HTML](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_11.html#perlhtmlmason-CHP-7)
    1. [Apache::Status and Mason](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_11.html#perlhtmlmason-CHP-7)
1. [8. Building a Mason Site](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_12.html)
    1. [Functionality](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_12.html#perlhtmlmason-CHP-8)
    1. [Directory Layout](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_12.html#perlhtmlmason-CHP-8)
    1. [File Extensions](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_12.html#perlhtmlmason-CHP-8)
    1. [Apache Configuration](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_12.html#perlhtmlmason-CHP-8)
    1. [The Components](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_12.html#perlhtmlmason-CHP-8)
        1. [The Unrestricted Parts](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_12.html#perlhtmlmason-CHP-8)
    1. [Components with Access Controls](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_12.html#perlhtmlmason-CHP-8)
    1. [All Done](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_12.html#perlhtmlmason-CHP-8)
    1. [Further Directions](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_12.html#perlhtmlmason-CHP-8)
1. [9. Mason and CGI](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_13.html)
    1. [CGI-Appropriate Situations](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_13.html#perlhtmlmason-CHP-9)
    1. [CGI-Inappropriate Situations](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_13.html#perlhtmlmason-CHP-9)
    1. [Creating a CGI-Based Site in Mason](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_13.html#perlhtmlmason-CHP-9)
    1. [Using  Mason Templates Inside Regular CGI Scripts](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_13.html#perlhtmlmason-CHP-9)
        1. [Design Considerations](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_13.html#perlhtmlmason-CHP-9)
    1. [Differences Between Mason Under CGI and mod_perl](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_13.html#perlhtmlmason-CHP-9)
1. [10. Scalable Design](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_14.html)
    1. [Modules Versus Components](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_14.html#perlhtmlmason-CHP-1)
        1. [The Other Side](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_14.html#perlhtmlmason-CHP-1)
    1. [Components as Independent Units](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_14.html#perlhtmlmason-CHP-1)
    1. [Component Layout](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_14.html#perlhtmlmason-CHP-1)
    1. [File Naming and Directory Layout](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_14.html#perlhtmlmason-CHP-1)
    1. [Random Advice](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_14.html#perlhtmlmason-CHP-1)
1. [11. Recipes](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_15.html)
    1. [Sessions](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_15.html#perlhtmlmason-CHP-1)
        1. [Without Touching httpd.conf](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_15.html#perlhtmlmason-CHP-1)
        1. [Predeclaring the Global via an httpd.conf File](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_15.html#perlhtmlmason-CHP-1)
        1. [Predeclaring the Global via a handler.pl Script](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_15.html#perlhtmlmason-CHP-1)
        1. [Using Cache::Cache for Sessions](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_15.html#perlhtmlmason-CHP-1)
        1. [Putting the Session ID in the URL](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_15.html#perlhtmlmason-CHP-1)
    1. [Making Use of Autoflush](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_15.html#perlhtmlmason-CHP-1)
    1. [User Authentication and Authorization](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_15.html#perlhtmlmason-CHP-1)
        1. [Using Apache::AuthCookie](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_15.html#perlhtmlmason-CHP-1)
        1. [Authentication Without Cookies](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_15.html#perlhtmlmason-CHP-1)
        1. [Access Controls with Attributes](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_15.html#perlhtmlmason-CHP-1)
    1. [Co-Branding Color Schemes](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_15.html#perlhtmlmason-CHP-1)
        1. [With Stylesheets](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_15.html#perlhtmlmason-CHP-1)
        1. [With Code](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_15.html#perlhtmlmason-CHP-1)
    1. [Developer Environments](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_15.html#perlhtmlmason-CHP-1)
        1. [Multiple Component Roots](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_15.html#perlhtmlmason-CHP-1)
            1. [By path](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_15.html#perlhtmlmason-CHP-1)
            1. [By hostname](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_15.html#perlhtmlmason-CHP-1)
        1. [Multiple  Server Configurations](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_15.html#perlhtmlmason-CHP-1)
        1. [Managing DBI Connections](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_15.html#perlhtmlmason-CHP-1)
    1. [Using Mason Outside of Dynamic Web Sites](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_15.html#perlhtmlmason-CHP-1)
        1. [Generating a Static Site from Components](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_15.html#perlhtmlmason-CHP-1)
        1. [Generating Config Files](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_15.html#perlhtmlmason-CHP-1)
1. [12. Custom Mason Subclasses](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_16.html)
    1. [Class::Container as a Superclass](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_16.html#perlhtmlmason-CHP-1)
    1. [Syntax: Your Very Own Lexer](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_16.html#perlhtmlmason-CHP-1)
    1. [Output: Compiling to a Different Output](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_16.html#perlhtmlmason-CHP-1)
    1. [Storage: Replacing the Resolver](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_16.html#perlhtmlmason-CHP-1)
    1. [Request: A Request Object with a Built-in Session](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_16.html#perlhtmlmason-CHP-1)
    1. [Argument Munging: ApacheHandler](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_16.html#perlhtmlmason-CHP-1)
    1. [More Reader Exercises](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_16.html#perlhtmlmason-CHP-1)
1. [A. The Mason API](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_17.html)
    1. [Interpreter](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_17.html#perlhtmlmason-APP-A)
        1. [Object Properties](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_17.html#perlhtmlmason-APP-A)
        1. [ Directories](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_17.html#perlhtmlmason-APP-A)
        1. [  Runtime Methods](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_17.html#perlhtmlmason-APP-A)
    1. [Request](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_17.html#perlhtmlmason-APP-A)
        1. [Object  Properties](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_17.html#perlhtmlmason-APP-A)
        1. [Altering the Request Flow](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_17.html#perlhtmlmason-APP-A)
        1. [  Caching](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_17.html#perlhtmlmason-APP-A)
        1. [ Introspection](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_17.html#perlhtmlmason-APP-A)
        1. [Content and Output](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_17.html#perlhtmlmason-APP-A)
        1. [Fetching/Running Components](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_17.html#perlhtmlmason-APP-A)
        1. [ Subrequests](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_17.html#perlhtmlmason-APP-A)
    1. [Component](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_17.html#perlhtmlmason-APP-A)
        1. [ Object Properties](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_17.html#perlhtmlmason-APP-A)
        1. [Component Relationships](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_17.html#perlhtmlmason-APP-A)
        1. [   Inheritance](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_17.html#perlhtmlmason-APP-A)
    1. [Resolver](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_17.html#perlhtmlmason-APP-A)
    1. [ApacheHandler](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_17.html#perlhtmlmason-APP-A)
    1. [CGIHandler](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_17.html#perlhtmlmason-APP-A)
    1. [Compiler](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_17.html#perlhtmlmason-APP-A)
        1. [ Object Properties](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_17.html#perlhtmlmason-APP-A)
        1. [Compilation Callbacks](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_17.html#perlhtmlmason-APP-A)
    1. [Lexer](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_17.html#perlhtmlmason-APP-A)
1. [B. Object Constructor Parameters](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_18.html)
    1. [  HTML::Mason::Interp](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_18.html#perlhtmlmason-APP-B)
    1. [  HTML::Mason::Request](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_18.html#perlhtmlmason-APP-B)
    1. [HTML::Mason::Resolver::File](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_18.html#perlhtmlmason-APP-B)
    1. [  HTML::Mason::ApacheHandler](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_18.html#perlhtmlmason-APP-B)
    1. [  HTML::Mason::Compiler](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_18.html#perlhtmlmason-APP-B)
    1. [HTML::Mason::Component](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_18.html#perlhtmlmason-APP-B)
    1. [HTML::Mason::Buffer](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_18.html#perlhtmlmason-APP-B)
    1. [HTML::Mason::CGIHandler](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_18.html#perlhtmlmason-APP-B)
    1. [HTML::Mason::Lexer](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_18.html#perlhtmlmason-APP-B)
1. [C. Text Editors That Understand Mason](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_19.html)
    1. [Emacs](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_19.html#perlhtmlmason-APP-C)
    1. [Vim](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_19.html#perlhtmlmason-APP-C)
1. [D. Content Management with Bricolage](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_20.html)
    1. [Installing Bricolage](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_20.html#perlhtmlmason-APP-D)
    1. [Elements: the Building Blocks of Content](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_20.html#perlhtmlmason-APP-D)
    1. [Content Editing](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_20.html#perlhtmlmason-APP-D)
    1. [Templates](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_20.html#perlhtmlmason-APP-D)
    1. [Where to Learn More](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_20.html#perlhtmlmason-APP-D)
1. [Glossary](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_21.html)
1. [Index](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_22.html)
1. [About the Authors](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_23.html)
1. [Colophon](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_24.html)
1. [Copyright](https://ebookreading.net/view/book/Embedding+Perl+in+HTML+with+Mason-EB0596002254_25.html)