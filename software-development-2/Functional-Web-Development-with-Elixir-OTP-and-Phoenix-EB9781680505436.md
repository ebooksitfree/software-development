![Cover image for Functional Web Development with Elixir, OTP, and Phoenix](https://imgdetail.ebookreading.net/cover/cover/software_development/EB9781680505436.jpg)

[Functional Web Development with Elixir, OTP, and Phoenix](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_1.html "Functional Web Development with Elixir, OTP, and Phoenix")
====================================================================================================================

Author : [Lance Halvorsen](https://ebookreading.net/search/author/Lance+Halvorsen)

Release Date : 2018/01/01

ISBN : 9781680505436

Topic : [Software Development](https://ebookreading.net/search/category/software-development)

Book Description
-----------------

 Elixir and Phoenix are generating tremendous excitement as an unbeatable platform for building modern web applications. For decades OTP has helped developers create incredibly robust, scalable applications with unparalleled uptime. Make the most of them as you build a stateful web app with Elixir, OTP, and Phoenix. Model domain entities without an ORM or a database. Manage server state and keep your code clean with OTP Behaviours. Layer on a Phoenix web interface without coupling it to the business logic. Open doors to powerful new techniques that will get you thinking about web development in fundamentally new ways.
Elixir and OTP provide exceptional tools to build rock-solid back-end applications that scale. In this book, you'll build a web application in a radically different way, with a back end that holds application state. You'll use persistent Phoenix Channel connections instead of HTTP's request-response, and create the full application in distinct, decoupled layers.
In Part 1, start by building the business logic as a separate application, without Phoenix. Model the application domain with Elixir functions and simple data structures. By keeping state in memory instead of a database, you can reduce latency and simplify your code. In Part 2, add in the GenServer Behaviour to make managing in-memory state a breeze. Create a supervision tree to boost fault tolerance while separating error handling from business logic.
Phoenix is a modern web framework you can layer on top of business logic while keeping the two completely decoupled. In Part 3, you'll do exactly that as you build a web interface with Phoenix. Bring in the application from Part 2 as a dependency to a new Phoenix project. Then use ultra-scalable Phoenix Channels to establish persistent connections between the stateful server and a stateful front-end client.
You're going to love this way of building web apps!
What You Need:
You'll need a computer that can run Elixir version 1.5 or higher and Phoenix 1.3 or higher. Some familiarity with Elixir and Phoenix is recommended.
        Show and hide more                
Table of Contents
-----------------

1. [&amp;#160;Acknowledgments](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_6.html#d24e161)
1. [&amp;#160;Introduction](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_7.html#d24e192)
    1. [Who This Book Is For](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_8.html#d24e226)
    1. [Who This Book Is Not For](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_9.html#d24e244)
    1. [About This Book](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_10.html#d24e299)
    1. [Online Resources](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_11.html#d24e362)
1. [1. Mapping Our Route](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_12.html#chapter.route_map)
    1. [Lay the Foundation with Elixir](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_13.html#d24e486)
    1. [Add a Web Interface with Phoenix](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_14.html#d24e541)
    1. [Functional Web Development](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_15.html#d24e576)
    1. [The Game of Islands](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_16.html#d24e599)
1. [Part I. Define the Functional Core in Elixir](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_17.html#part_one)
    1. [2. Model Data and Behavior](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_18.html#chapter.model_data)
        1. [The Benefits](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_19.html#d24e677)
        1. [Let’s Build It](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_20.html#d24e750)
        1. [Discover the Entities and Model the Domain](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_21.html#d24e925)
        1. [Transforming Data](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_22.html#d24e2999)
        1. [Putting the Pieces Together](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_23.html#d24e4819)
        1. [Wrapping Up](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_24.html#d24e5796)
    1. [3. Manage State with a State Machine](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_25.html#chapter.functional_)
        1. [A Quick Look at State](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_26.html#d24e5848)
        1. [A Bit of History](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_27.html#d24e5886)
        1. [State Machines](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_28.html#d24e5984)
        1. [A Functional State Machine for Islands](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_29.html#d24e6046)
        1. [Working Through the States](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_30.html#d24e6253)
        1. [Wrapping Up](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_31.html#d24e8869)
1. [Part II. Add OTP for Concurrency and Fault Tolerance](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_33.html#part_two)
    1. [4. Wrap It Up in a GenServer](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_34.html#chapter.gen_server)
        1. [A Look at Micro-Services](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_35.html#d24e8939)
        1. [OTP Solutions](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_36.html#d24e9009)
        1. [Getting Started with GenServer](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_37.html#d24e9315)
        1. [Initializing GenServer State](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_38.html#d24e10524)
        1. [Customizing GenServer Behavior](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_39.html#d24e10946)
        1. [Naming GenServer Processes](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_40.html#d24e13749)
        1. [Wrapping Up](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_41.html#d24e14463)
    1. [5. Process Supervision for Recovery](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_42.html#chapter.design_for_)
        1. [Fault Tolerance](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_43.html#d24e14544)
        1. [Linking Processes](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_44.html#d24e14626)
        1. [Introducing the Supervisor Behaviour](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_45.html#d24e15675)
        1. [Supervision Strategies](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_46.html#d24e15785)
        1. [The Child Specification](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_47.html#d24e15924)
        1. [A Supervisor for the Game](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_48.html#d24e16328)
        1. [Starting the Supervision Tree](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_49.html#d24e16766)
        1. [Starting and Stopping Child Processes](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_50.html#d24e16913)
        1. [Putting the Pieces Together](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_51.html#d24e17734)
        1. [Recovering State After a Crash](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_52.html#d24e18030)
        1. [Wrapping Up](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_53.html#d24e19656)
1. [Part III. Add a Web Interface with Phoenix](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_55.html#part_three)
    1. [6. Generate a New Web Interface with&amp;#160;PhoenixGenerate a New Web Interface with Phoenix](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_56.html#chapter.new_phoenix)
        1. [Frameworks](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_57.html#d24e19737)
        1. [Applications](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_58.html#d24e19875)
        1. [Generate a New Phoenix Application](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_59.html#d24e21234)
        1. [Adding a New Dependency](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_60.html#d24e21709)
        1. [Call the Logic from the Interface](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_61.html#d24e22143)
        1. [Wrapping Up](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_62.html#d24e22642)
    1. [7. Create Persistent Connections with&amp;#160;Phoenix ChannelsCreate Persistent Connections with Phoenix Channels](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_63.html#chapter.connect_wit)
        1. [The Beauty of Channels](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_64.html#d24e22686)
        1. [The Pieces That Make a Channel](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_65.html#d24e22741)
        1. [Let’s Build It](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_66.html#d24e22926)
        1. [Establish a Client Connection](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_67.html#d24e23319)
        1. [Converse Over a Channel](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_68.html#d24e23731)
        1. [Connect the Channel to the Game](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_69.html#d24e24428)
        1. [Phoenix Presence](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_70.html#d24e26627)
        1. [Authorization](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_71.html#d24e27165)
        1. [Wrapping Up](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_72.html#d24e27600)
1. [A1. Installing System Dependencies](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_74.html#appendix.installati)
    1. [Elixir](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_75.html#d24e27706)
    1. [Erlang](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_76.html#d24e27769)
    1. [Phoenix](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_77.html#d24e27828)
    1. [Node.js and NPM](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_78.html#d24e27861)
1. [&amp;#160;Bibliography](https://ebookreading.net/view/book/Functional+Web+Development+with+Elixir%2C+OTP%2C+and+Phoenix-EB9781680505436_79.html#d24e27894)
