![Cover image for Mastering Entity Framework Core 2.0](https://imgdetail.ebookreading.net/cover/cover/software_development/EB9781788294133.jpg)

[Mastering Entity Framework Core 2.0](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_1.html "Mastering Entity Framework Core 2.0")
====================================================================================================================

Author : [Prabhakaran Anbazhagan](https://ebookreading.net/search/author/Prabhakaran+Anbazhagan)

Release Date : 2017/12/01

ISBN : 9781788294133

Topic : [Software Development](https://ebookreading.net/search/category/software-development)

Book Description
-----------------

 Learn how to leverage the features of the new Entity Framework Core APIs and use them to build pure .NET Core applications.
About This Book
Learn how to effectively manage your database to make it more productive and maintainable.Write simplified queries using LINQ to acquire the desired data easilyRaise the abstraction level from data to objects so teams can function independently, resulting in easily maintainable codeWho This Book Is For
This book is for .NET Core developers who would like to integrate EF Core in their application. Prior knowledge of .NET Core and C# is assumed.
What You Will Learn
Create databases and perform CRUD operations on themUnderstand and build relationships (related to entities, keys, and properties)Understand in-built, custom, and remote validation (both client and server side)You will learn to handle concurrency to build responsive applicationsYou will handle transactions and multi-tenancy while also improving performanceIn Detail
Being able to create and maintain data-oriented applications has become crucial in modern programming. This is why Microsoft came up with Entity Framework so architects can optimize storage requirements while also writing efficient and maintainable application code. This book is a comprehensive guide that will show how to utilize the power of the Entity Framework to build efficient .NET Core applications. It not only teaches all the fundamentals of Entity Framework Core but also demonstrates how to use it practically so you can implement it in your software development.
The book is divided into three modules. The first module focuses on building entities and relationships. Here you will also learn about different mapping techniques, which will help you choose the one best suited to your application design. Once you have understood the fundamentals of the Entity Framework, you will move on to learn about validation and querying in the second module. It will also teach you how to execute raw SQL queries and extend the Entity Framework to leverage Query Objects using the Query Object Pattern. The final module of the book focuses on performance optimization and managing the security of your application. You will learn to implement failsafe mechanisms using concurrency tokens. The book also explores row-level security and multitenant databases in detail.
By the end of the book, you will be proficient in implementing Entity Framework on your .NET Core applications.
Style and approach
This book is filled with various examples that will help you use Entity Framework Core 2.0 to write efficient software.
Downloading the example code for this book. You can download the example code files for all Packt books you have purchased from your account at http://www.PacktPub.com. If you purchased this book elsewhere, you can visit http://www.PacktPub.com/support and register to have the code file.
        Show and hide more                
Table of Contents
-----------------

1. [Preface](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_13.html)
    1. [What this book covers](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_14.html)
    1. [What you need for this book](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_15.html)
    1. [Who this book is for](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_16.html)
    1. [Conventions](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_17.html)
    1. [Reader feedback](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_18.html)
    1. [Customer support](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_19.html)
        1. [Downloading the example code](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_20.html)
        1. [Downloading the color images of this book](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_21.html)
        1. [Errata](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_22.html)
        1. [Piracy](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_23.html)
        1. [Questions](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_24.html)
1. [Kickstart - Introduction to Entity Framework Core](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_25.html)
    1. [Prerequisites](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_26.html)
    1. [Creating a new project](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_27.html)
        1. [The Start??page](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_28.html)
        1. [The File menu](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_29.html)
        1. [Structuring the web app](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_30.html)
    1. [Installing Entity Framework](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_31.html)
    1. [Data models](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_32.html)
        1. [ Blog entity](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_33.html)
            1. [Post??entity](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_34.html)
    1. [Database context](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_35.html)
    1. [Registering the??context in services (.NET Core DI)](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_36.html)
    1. [Creating and seeding databases](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_37.html)
    1. [CRUD operations](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_38.html)
    1. [Summary](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_39.html)
1. [The Other Way Around ??? Database First Approach](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_40.html)
    1. [Preparing the database](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_41.html)
        1. [Blog entity script](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_42.html)
        1. [Post entity script](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_43.html)
    1. [Creating?? new project](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_44.html)
        1. [Installing Entity Framework](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_45.html)
    1. [Reverse engineering the??database](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_46.html)
        1. [Configuring data context](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_47.html)
        1. [Working with the Blog entity](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_48.html)
        1. [Working with the Post entity](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_49.html)
    1. [Registering context in services (.NET Core DI)](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_50.html)
        1. [Refactoring the OnConfiguring() method](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_51.html)
        1. [Refactoring the ConfigureServices method](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_52.html)
        1. [The appsettings.json setting](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_53.html)
    1. [Performing CRUD operations](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_54.html)
        1. [Creating controller action](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_55.html)
        1. [Edit controller action](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_56.html)
        1. [The Delete??view](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_57.html)
    1. [Summary](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_58.html)
1. [Relationships ??? Terminology and Conventions](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_59.html)
    1. [Understanding relationship terms](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_60.html)
        1. [Data models](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_61.html)
            1. [Blog entity](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_62.html)
            1. [The Post entity](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_63.html)
        1. [Principal entity](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_64.html)
        1. [Principal key](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_65.html)
        1. [Dependent entity](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_66.html)
        1. [Foreign key](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_67.html)
        1. [Navigation property](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_68.html)
            1. [Collection navigation property](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_69.html)
            1. [Reference navigation property](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_70.html)
            1. [Inverse navigation property](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_71.html)
    1. [Conventions in a relationship](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_72.html)
        1. [Fully-defined relationships](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_73.html)
            1. [Fully-defined relationships - under the hood](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_74.html)
        1. [No foreign key property](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_75.html)
            1. [No foreign key property - under the hood](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_76.html)
        1. [Single navigation property](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_77.html)
        1. [Foreign key](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_78.html)
        1. [Inverse property](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_79.html)
    1. [Summary](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_80.html)
1. [Building Relationships ??? Understanding Mapping](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_81.html)
    1. [Relationships](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_82.html)
        1. [The one-to-one relationship](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_83.html)
            1. [Building one-to-one relationships using the Fluent API](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_84.html)
        1. [The one-to-many relationship](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_85.html)
        1. [The many-to-many relationship](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_86.html)
            1. [Building many-to-many relationship using the Fluent API](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_87.html)
    1. [Fluent API](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_88.html)
        1. [Identifying navigation property and inverse navigation](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_89.html)
        1. [Identifying the single navigation property](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_90.html)
        1. [Relationship-building techniques](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_91.html)
            1. [Building relationship using a foreign key](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_92.html)
            1. [Building relationships using a principal key](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_93.html)
            1. [Building relationships using the IsRequired method](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_94.html)
        1. [Cascade??delete](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_95.html)
        1. [Data migration issue with EF Core 2.0](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_96.html)
    1. [Summary](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_97.html)
1. [Know the Validation ??? Explore Inbuilt Validations](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_98.html)
    1. [Diving into built-in validations](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_99.html)
    1. [Required field validation](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_100.html)
        1. [Incorporating the Required validation in blogging system models](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_101.html)
    1. [EmailAddress field validation](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_102.html)
        1. [Incorporating EmailAddress validation in blogging system models](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_103.html)
    1. [Compare field validation](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_104.html)
        1. [Incorporating the Compare validation in blogging system models](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_105.html)
    1. [Url field validation](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_106.html)
        1. [Incorporating Url validation in blogging system models](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_107.html)
    1. [MinLength field validation](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_108.html)
    1. [MaxLength field validation](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_109.html)
    1. [RegularExpression field validation](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_110.html)
    1. [Summary](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_111.html)
1. [Save Yourself ??? Hack Proof Your Entities](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_112.html)
    1. [Client-side validation](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_113.html)
    1. [Validating data without client-side scripting](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_114.html)
        1. [Server-side validation](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_115.html)
        1. [Manual validation](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_116.html)
    1. [Custom validation](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_117.html)
        1. [Creating client-side logic for custom validation](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_118.html)
    1. [Remote validation](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_119.html)
    1. [Summary](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_120.html)
1. [Going Raw ??? Leveraging SQL Queries in LINQ](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_121.html)
    1. [Basic raw SQL queries](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_122.html)
    1. [Building parameterized queries](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_123.html)
    1. [Composing with LINQ](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_124.html)
    1. [Executing SQL query without a DBSet or POCO](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_125.html)
    1. [Summary](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_126.html)
1. [Query Is All We Need ??? Query Object Pattern](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_127.html)
    1. [Introduction to query objects](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_128.html)
    1. [Improving repositories with the query object pattern](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_129.html)
        1. [Introduction to repositories](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_130.html)
            1. [Solution to the repository assignment](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_131.html)
        1. [Incorporating the query object pattern into repositories](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_132.html)
            1. [List query object support in the repository](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_133.html)
            1. [Single query object support in the repository](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_134.html)
            1. [Solution to the repository with the queries assignment](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_135.html)
    1. [Composing queries with commands](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_136.html)
        1. [Solution to the command queries assignment](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_137.html)
    1. [Enhancing queries with expression trees](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_138.html)
        1. [Solution to the expression trees assignment](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_139.html)
    1. [Summary](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_140.html)
1. [Fail Safe Mechanism ??? Transactions](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_141.html)
    1. [Default behavior of a transaction](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_142.html)
        1. [Adding tags support in the blogging system](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_143.html)
        1. [Leveraging default transaction behavior](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_144.html)
    1. [Creating a simple transaction](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_145.html)
    1. [Creating a cross-context transaction](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_146.html)
        1. [File upload support to the blogging system](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_147.html)
        1. [Limitations to the transaction scope](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_148.html)
        1. [Custom transaction scope support](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_149.html)
        1. [Adding date picker support to the blogging system](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_150.html)
    1. [Leveraging transactions between multiple technologies](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_151.html)
        1. [Recent posts support to the blogging system](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_152.html)
        1. [Anonymous posts list and individual blog post](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_153.html)
        1. [Listing comments](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_154.html)
        1. [Adding comments using external database transactions](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_155.html)
    1. [Summary](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_156.html)
1. [Make It Real ??? Handling Concurrencies](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_157.html)
    1. [Handling??concurrency in EF](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_158.html)
        1. [Understanding the concurrency conflicts](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_159.html)
            1. [Optimistic concurrency](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_160.html)
            1. [Pessimistic concurrency](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_161.html)
    1. [Introducing concurrency tokens](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_162.html)
    1. [Non-timestamp based concurrency tokens](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_163.html)
        1. [Configuring non-timestamp tokens through data annotation](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_164.html)
        1. [Configuring non-timestamp tokens through Fluent API](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_165.html)
    1. [Timestamp-based concurrency tokens](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_166.html)
        1. [Configuring timestamp tokens through data annotation](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_167.html)
        1. [Configuring timestamp tokens through Fluent API](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_168.html)
    1. [Handling concurrency conflicts](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_169.html)
        1. [Applying optimistic concurrency](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_170.html)
            1. [Database wins](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_171.html)
            1. [Client wins](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_172.html)
            1. [User-specific custom resolution](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_173.html)
        1. [Applying pessimistic concurrency](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_174.html)
    1. [Summary](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_175.html)
1. [Performance ??? It&amp;#x27;s All About Execution Time](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_176.html)
    1. [The AsNoTracking() method](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_177.html)
        1. [How does tracking work?](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_178.html)
            1. [No-tracking queries](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_179.html)
            1. [Projections](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_180.html)
    1. [Detecting changes](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_181.html)
    1. [Asynchronous operations](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_182.html)
        1. [Transactions leveraging asynchronous operations](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_183.html)
    1. [Unnecessary volume returned](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_184.html)
    1. [The N+1 Select problem](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_185.html)
    1. [More??data than required](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_186.html)
    1. [Mismatched data types](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_187.html)
    1. [Missing indexes](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_188.html)
    1. [Summary](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_189.html)
1. [Isolation ??? Building a Multi-Tenant Database](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_190.html)
    1. [Authentication in the blogging system](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_191.html)
    1. [Row-Level Security](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_192.html)
        1. [Filter predicate](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_193.html)
        1. [Block predicate](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_194.html)
    1. [Multi-tenancy](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_195.html)
        1. [Standalone](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_196.html)
        1. [Database-per-tenant](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_197.html)
        1. [Shared multi-tenant](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_198.html)
        1. [Dive into multi-tenancy](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_199.html)
        1. [Blocking cross-tenant write operation](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_200.html)
    1. [Summary](https://ebookreading.net/view/book/Mastering+Entity+Framework+Core+2.0-EB9781788294133_201.html)
