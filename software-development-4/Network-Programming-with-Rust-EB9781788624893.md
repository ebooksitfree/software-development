![Cover image for Network Programming with Rust](https://imgdetail.ebookreading.net/cover/cover/software_development/EB9781788624893.jpg)

[Network Programming with Rust](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_1.html "Network Programming with Rust")
====================================================================================================================

Author : [Abhishek Chanda](https://ebookreading.net/search/author/Abhishek+Chanda)

Release Date : 2018/02/01

ISBN : 9781788624893

Topic : [Software Development](https://ebookreading.net/search/category/software-development)

Book Description
-----------------

Learn to write servers and network clients using Rust's low-level socket classes with this guide
About This Book
Build a solid foundation in Rust while also mastering important network programming detailsLeverage the power of a number of available libraries to perform network operations in RustDevelop a fully functional web server to gain the skills you need, fastWho This Book Is For
This book is for software developers who want to write networking software with Rust. A basic familiarity with networking concepts is assumed. Beginner-level knowledge of Rust will help but is not necessary.
What You Will Learn
Appreciate why networking is important in implementing distributed systemsWrite a non-asynchronous echo server over TCP that talks to a client over a networkParse JSON and binary data using parser combinators such as nomWrite an HTTP client that talks to the server using reqwestModify an existing Rust HTTTP server and add SSL to itMaster asynchronous programming support in RustUse external packages in a Rust projectIn Detail
Rust is low-level enough to provide fine-grained control over memory while providing safety through compile-time validation. This makes it uniquely suitable for writing low-level networking applications.
This book is divided into three main parts that will take you on an exciting journey of building a fully functional web server. The book starts with a solid introduction to Rust and essential networking concepts. This will lay a foundation for, and set the tone of, the entire book. In the second part, we will take an in-depth look at using Rust for networking software. From client-server networking using sockets to IPv4/v6, DNS, TCP, UDP, you will also learn about serializing and deserializing data using serde. The book shows how to communicate with REST servers over HTTP. The final part of the book discusses asynchronous network programming using the Tokio stack. Given the importance of security for modern systems, you will see how Rust supports common primitives such as TLS and public-key cryptography.
After reading this book, you will be more than confident enough to use Rust to build effective networking software
Style and approach
This book will get you started with building networking software in Rust by taking you through all the essential concepts. 
Downloading the example code for this book You can download the example code files for all Packt books you have purchased from your account at http://www.PacktPub.com. If you purchased this book elsewhere, you can visit http://www.PacktPub.com/support and register to have the files e-mailed directly to you.
              
Table of Contents
-----------------

1. [Title Page](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_2.html)
1. [Copyright and Credits](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_3.html)
    1. [Network Programming with Rust](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_4.html)
1. [Dedication](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_5.html)
1. [Packt Upsell](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_6.html)
    1. [Why subscribe?](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_7.html)
    1. [PacktPub.com](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_8.html)
1. [Contributors](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_9.html)
    1. [About the author](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_10.html)
    1. [About the reviewer](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_11.html)
    1. [Packt is searching for authors like you](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_12.html)
1. [Preface](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_14.html)
    1. [Who this book is for](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_15.html)
    1. [What this book covers](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_16.html)
    1. [To get the most out of this book](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_17.html)
        1. [Download the example code files](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_18.html)
        1. [Conventions used](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_19.html)
    1. [Get in touch](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_20.html)
        1. [Reviews](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_21.html)
1. [Introduction to Client/Server Networking](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_22.html)
    1. [A brief history of networks](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_23.html)
    1. [Layering in networks](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_24.html)
    1. [Addressing in networks](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_25.html)
    1. [How IP routing works](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_26.html)
    1. [How DNS works](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_27.html)
    1. [Common service models](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_28.html)
        1. [Connection-oriented service](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_29.html)
        1. [Connectionless service](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_30.html)
    1. [The network programming interface in Linux](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_31.html)
    1. [Summary](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_32.html)
1. [Introduction to Rust and its Ecosystem](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_33.html)
    1. [The Rust ecosystem](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_34.html)
    1. [Getting started with Rust](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_35.html)
    1. [Introduction to the borrow checker](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_36.html)
    1. [Generics and the trait system](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_37.html)
    1. [Error handling](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_38.html)
    1. [The macro system](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_39.html)
        1. [Syntactic macros](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_40.html)
        1. [Procedural macros](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_41.html)
    1. [Functional features in Rust](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_42.html)
        1. [Higher-order functions](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_43.html)
        1. [Iterators](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_44.html)
    1. [Concurrency primitives](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_45.html)
    1. [Testing](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_46.html)
    1. [Summary](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_47.html)
1. [TCP and UDP Using Rust](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_48.html)
    1. [A Simple TCP server and client](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_49.html)
    1. [A Simple UDP server and client](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_50.html)
        1. [UDP multicasting](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_51.html)
    1. [Miscellaneous utilities in std::net](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_52.html)
    1. [Some related crates](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_53.html)
    1. [Summary](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_54.html)
1. [Data Serialization, Deserialization, and Parsing](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_55.html)
    1. [Serialization and deserialization using Serde](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_56.html)
        1. [Custom serialization and deserialization](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_57.html)
    1. [Parsing textual data](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_58.html)
    1. [Parsing binary data](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_59.html)
    1. [Summary](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_60.html)
1. [Application Layer Protocols](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_61.html)
    1. [Introduction to RPC](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_62.html)
    1. [Introduction to SMTP](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_63.html)
    1. [Introduction to FTP and TFTP](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_64.html)
    1. [Summary](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_65.html)
1. [Talking HTTP in the Internet](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_66.html)
    1. [Introducing Hyper](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_67.html)
    1. [Introducing Rocket](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_68.html)
    1. [Introducing&amp;#xA0;reqwest](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_69.html)
    1. [Summary](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_70.html)
1. [Asynchronous Network Programming Using Tokio](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_71.html)
    1. [Looking into the Future](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_72.html)
        1. [Working with streams and sinks](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_73.html)
    1. [Heading to tokio](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_74.html)
        1. [Socket multiplexing in tokio](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_75.html)
        1. [Writing streaming protocols](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_76.html)
        1. [The larger tokio ecosystem](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_77.html)
    1. [Conclusion](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_78.html)
1. [Security](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_79.html)
    1. [Securing the web](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_80.html)
        1. [Letsencrypt using Rust](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_81.html)
        1. [OpenSSL using Rust](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_82.html)
        1. [Securing tokio applications](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_83.html)
    1. [Cryptography using ring](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_84.html)
    1. [Summary](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_85.html)
1. [Appendix](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_86.html)
    1. [Introduction to coroutines and generators](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_87.html)
        1. [How May handles coroutines](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_88.html)
    1. [Awaiting the future](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_89.html)
    1. [Data parallelism](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_90.html)
    1. [Parsing using Pest](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_91.html)
    1. [Miscellaneous utilities](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_92.html)
    1. [Summary](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_93.html)
1. [Other Books You May Enjoy](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_94.html)
    1. [Leave a review - let other readers know what you think](https://ebookreading.net/view/book/Network+Programming+with+Rust-EB9781788624893_95.html)
