![Cover image for Creating Solid APIs with Lua](https://imgdetail.ebookreading.net/cover/cover/software_development/EB9781491986301.jpg)

[Creating Solid APIs with Lua](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_1.html "Creating Solid APIs with Lua")
====================================================================================================================

Author : [Tyler Neylon](https://ebookreading.net/search/author/Tyler+Neylon)

Release Date : 2017/02/01

ISBN : 9781491986301

Topic : [Software Development](https://ebookreading.net/search/category/software-development)

Book Description
-----------------

 Learn how you can build APIs by integrating the Lua and C programming languages. These APIs can be used to speed up development within your company, allow people to customize your app or game, and serve as the foundation of a domain-specific language within a platform you’re developing.
Author Tyler Neylon—a game designer with a PhD in applied math—shows you how C and Lua interface with each other, so you can create a set of Lua classes and functions that work programmatically with local applications. You’ll also learn how to guard against shady scripts written by users who either make mistakes or purposefully attempt to break your system.
Build Lua from source, then link the Lua library to a C program that can execute a Lua scriptWrite Lua-visible functions with the power of C by calling C functions from LuaWork with Lua data types from CAdd Lua classes to your API, implemented in either Lua or CManage Lua exceptions with error-handling functions, and add custom hook functions that can protect you from common programming errorsGive users the freedom to write their own scripts that can be run in a C-created sandboxed environmentLua is easy to learn, especially if you know JavaScript. Neylon’s free 3-part series on oreilly.com, Learn Lua from JavaScript, will help you get started.
        Show and hide more                
Table of Contents
-----------------

1. [Preface](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_4.html#preface)
    1. [Acknowledgments](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_4.html#acknowledgements)
1. [I. Making a Lua API](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_5.html#making_a_lua_api)
1. [1. Running a Lua Script from C](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_6.html#running_a_lua_scrip)
    1. [An Overview of the C/Lua Interface](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_6.html#overview_of_the_cso)
    1. [An Example: EatyGuy](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_6.html#example_eatyguy)
    1. [Getting the Lua Source](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_6.html#getting_the_lua_sou)
        1. [If You’re Using macOS or Linux…](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_6.html#if_youapostrophere_)
        1. [If You’re Using Windows…](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_6.html#if_youapostrophere_)
    1. [This Book’s GitHub Repo](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_6.html#this_reportapostrop)
    1. [Running a Lua Script from C](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_6.html#running_a_lua_scrip)
    1. [Lua Modules and Loading Them from C](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_6.html#lua_modules_and_loa)
    1. [Drawing Mazes](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_6.html#drawing_mazes)
    1. [One Way to Call a Lua Function from C](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_6.html#one_way_to_call_a_l)
        1. [Stack Indexes](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_6.html#stack_indexes)
    1. [Giving Lua the Power of C](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_6.html#giving_lua_the_powe)
1. [2. Calling C from Lua](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_7.html#calling_c_from_lua)
    1. [EatyGuy Version 1: A Lua-Callable C Function](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_7.html#eatyguy_version_1_a)
        1. [The tput Shell Command](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_7.html#tput_shell_command)
        1. [The Core Mechanics of Lua-Callable C Functions](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_7.html#core_mechanics_of_l)
    1. [EatyGuy Version 2: Adding an Animated Player](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_7.html#eatyguy_version_2_a)
        1. [Strings and Multiple Arguments with set_color() and set_pos()](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_7.html#strings_and_multipl)
        1. [Sending a Return Value from C to Lua by Using timestamp()](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_7.html#sending_a_return_va)
        1. [Fancier Maze Drawing](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_7.html#fancier_maze_drawin)
        1. [Starting, Stopping, and Sharing Functions with Lua](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_7.html#startingcomma_stopp)
        1. [Game State and Lua’s Event Loop](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_7.html#game_state_and_luaa)
        1. [Updating Player State](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_7.html#updating_player_sta)
        1. [Drawing the Player State](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_7.html#drawing_the_player_)
    1. [Calling Lua Functions from C More Effectively](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_7.html#calling_lua_functio)
1. [3. Using Lua Values in C](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_8.html#using_lua_values_in)
    1. [EatyGuy Version 3: Passing Data to a Lua Function](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_8.html#eatyguy_version_3_p)
        1. [Receiving Arrow Key Presses](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_8.html#receiving_arrow_key)
    1. [EatyGuy Version 4: Implementing API Functions Within Lua](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_8.html#eatyguy_version_4_i)
        1. [Fixing the tput Bottleneck](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_8.html#fixing_the_tput_bot)
    1. [EatyGuy Version 5: Working with Lua Tables from C](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_8.html#eatyguy_version_5_w)
        1. [Where Tables Live](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_8.html#where_tables_live)
        1. [The Primary Table Functions](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_8.html#primary_table_funct)
        1. [Using a Table to Send Game State to Lua](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_8.html#using_a_table_to_se)
    1. [Adding Some Class to Your API](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_8.html#adding_some_class_t)
1. [4. Making Your API Classy](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_9.html#making_your_api_cla)
    1. [EatyGuy Version 6: Writing a Class in Lua](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_9.html#eatyguy_version_6_w)
        1. [A Common Code Pattern for Lua Classes](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_9.html#common_code_pattern)
        1. [The Character Class Example](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_9.html#character_class_exa)
    1. [EatyGuy Version 7: Class Inheritance](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_9.html#eatyguy_version_7_c)
        1. [Subclasses in Lua](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_9.html#subclasses_in_lua)
        1. [The Baddy Class](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_9.html#baddy_class)
    1. [EatyGuy Version 8: Introducing the userdata Type](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_9.html#eatyguy_version_8_i)
    1. [Writing a Lua-Loadable Module in C](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_9.html#writing_a_lua-loada)
        1. [Implementing a Class-Like userdata Type](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_9.html#implementing_a_clas)
        1. [Integrating a C Module into Your API](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_9.html#integrating_a_c_mod)
    1. [Making Your Code Debug-Friendly](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_9.html#making_your_code_de)
1. [II. Script Safety](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_10.html#script_safety)
1. [5. Detecting Errors](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_11.html#detecting_errors)
    1. [Throwing and Catching Errors in Lua](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_11.html#throwing_and_catchi)
    1. [When Should You Throw an Exception?](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_11.html#when_should_you_thr)
    1. [Don’t Panic!](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_11.html#donapostrophet_pani)
        1. [Lua Errors in C](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_11.html#lua_errors_in_c)
    1. [How lua_pcall() Handles Errors](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_11.html#how_luaunderscorepc)
    1. [Turtles All the Way Down](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_11.html#turtles_all_the_way)
    1. [Getting Strict About Globals and Typos](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_11.html#getting_strict_abou)
    1. [The Environment of Freshly Loaded Chunks](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_11.html#environment_of_fres)
    1. [A Version of strict.lua](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_11.html#version_of_strictdo)
    1. [EatyGuy Version 9: Death, Strictly](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_11.html#eatyguy_version_9_d)
    1. [A Brief but Quickly Dismissed Question of Morality](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_11.html#brief_but_quickly_d)
1. [6. Sandboxing User Scripts](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_12.html#sandboxing_user_scr)
    1. [EatyGuy Version 10: The Baddy Construction Kit](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_12.html#eatyguy_version_10_)
        1. [The Code of Scum and Villainy](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_12.html#code_of_scum_and_vi)
    1. [Scripts Gone Wild](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_12.html#scripts_gone_wild)
    1. [Controlling Library Access](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_12.html#controlling_library)
    1. [Managing Memory Use](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_12.html#managing_memory_use)
    1. [Managing CPU Use](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_12.html#managing_cpu_use)
    1. [End == Nigh](https://ebookreading.net/view/book/Creating+Solid+APIs+with+Lua-EB9781491986301_12.html#end_equalsequals_ni)
