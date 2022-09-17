![Cover image for Clojure Cookbook](https://imgdetail.ebookreading.net/cover/cover/software_development/EB9781449366384.jpg)

[Clojure Cookbook](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_1.html "Clojure Cookbook")
====================================================================================================================

Author : [Luke VanderHart](https://ebookreading.net/search/author/Luke+VanderHart),[ Ryan Neufeld](https://ebookreading.net/search/author/+Ryan+Neufeld)

Release Date : 2014/03/01

ISBN : 9781449366384

Topic : [Software Development](https://ebookreading.net/search/category/software-development)

Book Description
-----------------

With more than 150 detailed recipes, this cookbook shows experienced Clojure developers how to solve a variety of programming tasks with this JVM language. The solutions cover everything from building dynamic websites and working with databases to network communication, cloud computing, and advanced testing strategies. And more than 60 of the world’s best Clojurians contributed recipes.
Each recipe includes code that you can use right away, along with a discussion on how and why the solution works, so you can adapt these patterns, approaches, and techniques to situations not specifically covered in this cookbook.
Master built-in primitive and composite data structuresCreate, develop and publish libraries, using the Leiningen toolInteract with the local computer that’s running your applicationManage network communication protocols and librariesUse techniques for connecting to and using a variety of databasesBuild and maintain dynamic websites, using the Ring HTTP server libraryTackle application tasks such as packaging, distributing, profiling, and loggingTake on cloud computing and heavyweight distributed data crunchingDive into unit, integration, simulation, and property-based testingClojure Cookbook is a collaborative project with contributions from some of the world’s best Clojurians, whose backgrounds range from aerospace to social media, banking to robotics, AI research to e-commerce.              
Table of Contents
-----------------

1. [Preface](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_3.html)
    1. [How This Book Was Written](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_3.html#_how_this_book_was_)
    1. [Audience](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_3.html#_audience)
    1. [Other Resources](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_3.html#_other_resources)
    1. [Structure](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_3.html#_structure)
    1. [Software Prerequisites](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_3.html#_software_prerequis)
    1. [Conventions Used in This Book](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_3.html#_conventions_used_i)
    1. [Using Code Examples](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_3.html#_using_code_example)
    1. [Safari® Books Online](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_3.html#_safari_books_onlin)
    1. [How to Contact Us](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_3.html#_how_to_contact_us)
    1. [Acknowledgments](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_3.html#_acknowledgments)
1. [1. Primitive Data](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_4.html)
    1. [1.0. Introduction](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_4.html#_introduction)
    1. [1.1. Changing the Capitalization of a String](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_4.html#_changing_the_capit)
    1. [1.2. Cleaning Up Whitespace in a String](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_4.html#_cleaning_up_whites)
    1. [1.3. Building a String from Parts](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_4.html#sec_primitives_buil)
    1. [1.4. Treating a String as a Sequence of Characters](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_4.html#sec_primitives_stri)
    1. [1.5. Converting Between Characters and Integers](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_4.html#sec_primitives_conv)
    1. [1.6. Formatting Strings](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_4.html#sec_primitives_stri)
    1. [1.7. Searching a String by Pattern](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_4.html#sec_primitives_stri)
    1. [1.8. Pulling Values Out of a String Using Regular Expressions](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_4.html#sec_primitives_stri)
    1. [1.9. Performing Find and Replace on Strings](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_4.html#sec_primitives_stri)
    1. [1.10. Splitting a String into Parts](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_4.html#_splitting_a_string)
    1. [1.11. Pluralizing Strings Based on a Quantity](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_4.html#_pluralizing_string)
    1. [1.12. Converting Between Strings, Symbols, and Keywords](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_4.html#_converting_between)
    1. [1.13. Maintaining Accuracy with Extremely Large/Small Numbers](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_4.html#sec_primitives_math)
    1. [1.14. Working with Rational Numbers](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_4.html#sec_primitives_rati)
    1. [1.15. Parsing Numbers](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_4.html#sec_primitives_numb)
    1. [1.16. Truncating and Rounding Numbers](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_4.html#sec_primitives_numb)
    1. [1.17. Performing Fuzzy Comparison](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_4.html#sec_primitives_numb)
    1. [1.18. Performing Trigonometry](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_4.html#_performing_trigono)
    1. [1.19. Inputting and Outputting Integers with Different Bases](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_4.html#_inputting_and_outp)
    1. [1.20. Calculating Statistics on Collections of Numbers](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_4.html#_calculating_statis)
    1. [1.21. Performing Bitwise Operations](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_4.html#sec_primitives_math)
    1. [1.22. Generating Random Numbers](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_4.html#_generating_random_)
    1. [1.23. Working with Currency](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_4.html#_working_with_curre)
    1. [1.24. Generating Unique IDs](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_4.html#sec_primitives_math)
    1. [1.25. Obtaining the Current Date and Time](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_4.html#sec_primitives_date)
    1. [1.26. Representing Dates as Literals](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_4.html#sec_primitives_date)
    1. [1.27. Parsing Dates and Times Using clj-time](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_4.html#sec_primitives_date)
    1. [1.28. Formatting Dates Using clj-time](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_4.html#sec_primitives_date)
    1. [1.29. Comparing Dates](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_4.html#sec_primitives_date)
    1. [1.30. Calculating the Length of a Time Interval](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_4.html#sec_primitives_date)
    1. [1.31. Generating Ranges of Dates and Times](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_4.html#sec_primitives_date)
    1. [1.32. Generating Ranges of Dates and Times Using Native Java Types](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_4.html#sec_date_range_nati)
    1. [1.33. Retrieving Dates Relative to One Another](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_4.html#sec_primitives_date)
    1. [1.34. Working with Time Zones](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_4.html#_working_with_time_)
    1. [1.35. Converting a Unix Timestamp to a Date](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_4.html#sec_date_from_unix_)
    1. [1.36. Converting a Date to a Unix Timestamp](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_4.html#sec_date_to_unix_ti)
1. [2. Composite Data](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_5.html)
    1. [2.0. Introduction](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_5.html#_introduction_2)
    1. [2.1. Creating a List](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_5.html#sec_creating_a_list)
    1. [2.2. Creating a List from an Existing Data Structure](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_5.html#sec_creating_a_list)
    1. [2.3. “Adding” an Item to a List](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_5.html#sec_adding_to_a_lis)
    1. [2.4. “Removing” an Item from a List](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_5.html#sec_removing_an_ite)
    1. [2.5. Testing for a List](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_5.html#_testing_for_a_list)
    1. [2.6. Creating a Vector](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_5.html#sec_composite_creat)
    1. [2.7. “Adding” an Item to a Vector](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_5.html#sec_adding_to_a_vec)
    1. [2.8. “Removing” an Item from a Vector](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_5.html#sec_composite_remov)
    1. [2.9. Getting the Value at an Index](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_5.html#_getting_the_value_)
    1. [2.10. Setting the Value at an Index](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_5.html#_setting_the_value_)
    1. [2.11. Creating a Set](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_5.html#sec_composite_creat)
    1. [2.12. Adding and Removing Items from Sets](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_5.html#sec_adding_removing)
    1. [2.13. Testing Set Membership](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_5.html#sec_testing_set_mem)
    1. [2.14. Using Set Operations](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_5.html#sec_set_operations)
    1. [2.15. Creating a Map](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_5.html#_creating_a_map)
    1. [2.16. Retrieving Values from a Map](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_5.html#sec_composite_retri)
    1. [2.17. Retrieving Multiple Keys from a Map Simultaneously](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_5.html#sec_retrieving_mult)
    1. [2.18. Setting Keys in a Map](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_5.html#sec_composite_data_)
    1. [2.19. Using Composite Values as Map Keys](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_5.html#sec_composites_as_k)
    1. [2.20. Treating Maps as Sequences (and Vice Versa)](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_5.html#sec_composite_maps_)
    1. [2.21. Applying Functions to Maps](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_5.html#sec_composites_appl)
    1. [2.22. Keeping Multiple Values for a Key](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_5.html#sec_composite_data_)
    1. [2.23. Combining Maps](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_5.html#sec_composite_combi)
    1. [2.24. Comparing and Sorting Values](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_5.html#sec_composite_sorti)
    1. [2.25. Removing Duplicate Elements from a Collection](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_5.html#_removing_duplicate)
    1. [2.26. Determining if a Collection Holds One of Several Values](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_5.html#sec_test_collection)
    1. [2.27. Implementing Custom Data Structures: Red-Black Trees—Part I](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_5.html#sec_red_black_part_)
    1. [2.28. Implementing Custom Data Structures: Red-Black Trees—Part II](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_5.html#sec_red_black_part_)
1. [3. General Computing](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_6.html)
    1. [3.0. Introduction](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_6.html#_introduction_3)
    1. [3.1. Running a Minimal Clojure REPL](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_6.html#_running_a_minimal_)
    1. [3.2. Interactive Documentation](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_6.html#sec_interactive_doc)
    1. [3.3. Exploring Namespaces](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_6.html#sec_exploring_names)
    1. [3.4. Trying a Library Without Explicit Dependencies](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_6.html#sec_try_library)
    1. [3.5. Running Clojure Programs](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_6.html#sec_running_program)
    1. [3.6. Running Programs from the Command Line](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_6.html#sec_command_line_ap)
    1. [3.7. Parsing Command-Line Arguments](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_6.html#sec_parse_command_l)
    1. [3.8. Creating Custom Project Templates](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_6.html#_creating_custom_pr)
    1. [3.9. Building Functions with Polymorphic Behavior](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_6.html#polymorphism_with_p)
    1. [3.10. Extending a Built-In Type](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_6.html#extend_built_in)
    1. [3.11. Decoupling Consumers and Producers with core.async](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_6.html#sec_general_core_as)
    1. [3.12. Making a Parser for Clojure Expressions Using core.match](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_6.html#sec_core_match_pars)
    1. [3.13. Querying Hierarchical Graphs with core.logic](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_6.html#_querying_hierarchi)
    1. [3.14. Playing a Nursery Rhyme](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_6.html#_playing_a_nursery_)
1. [4. Local I/O](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_7.html)
    1. [4.0. Introduction](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_7.html#_introduction_4)
    1. [4.1. Writing to STDOUT and STDERR](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_7.html#sec_local_io_writin)
    1. [4.2. Reading a Single Keystroke from the Console](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_7.html#_reading_a_single_k)
    1. [4.3. Executing System Commands](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_7.html#_executing_system_c)
    1. [4.4. Accessing Resource Files](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_7.html#sec_local_io_get_lo)
    1. [4.5. Copying Files](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_7.html#_copying_files)
    1. [4.6. Deleting Files or Directories](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_7.html#_deleting_files_or_)
    1. [4.7. Listing Files in a Directory](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_7.html#sec_local-io_files_)
    1. [4.8. Memory Mapping a File](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_7.html#_memory_mapping_a_f)
    1. [4.9. Reading and Writing Text Files](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_7.html#sec_local-io_read_w)
    1. [4.10. Using Temporary Files](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_7.html#_using_temporary_fi)
    1. [4.11. Reading and Writing Files at Arbitrary Positions](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_7.html#sec_local-random-ac)
    1. [4.12. Parallelizing File Processing](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_7.html#_parallelizing_file)
    1. [4.13. Parallelizing File Processing with Reducers](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_7.html#rec_local_io_parall)
    1. [4.14. Reading and Writing Clojure Data](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_7.html#sec_local_io_clojur)
    1. [4.15. Using edn for Configuration Files](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_7.html#sec_edn_configs)
    1. [4.16. Emitting Records as edn Values](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_7.html#sec_edn_record)
    1. [4.17. Handling Unknown Tagged Literals When Reading Clojure Data](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_7.html#sec_default_data_re)
    1. [4.18. Reading Properties from a File](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_7.html#_reading_properties)
    1. [4.19. Reading and Writing Binary Files](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_7.html#sec_local-io_handle)
    1. [4.20. Reading and Writing CSV Data](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_7.html#_reading_and_writin)
    1. [4.21. Reading and Writing Compressed Files](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_7.html#_reading_and_writin)
    1. [4.22. Working with XML Data](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_7.html#sec_read_write_xml)
    1. [4.23. Reading and Writing JSON Data](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_7.html#sec_local_io_json)
    1. [4.24. Generating PDF Files](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_7.html#sec_local_io_pdf)
    1. [4.25. Making a GUI Window with Scrollable Text](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_7.html#_making_a_gui_windo)
1. [5. Network I/O and Web Services](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_8.html)
    1. [5.0. Introduction](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_8.html#_introduction_5)
    1. [5.1. Making HTTP Requests](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_8.html#sec_http_request)
    1. [5.2. Performing Asynchronous HTTP Requests](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_8.html#sec_async_http)
    1. [5.3. Sending a Ping Request](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_8.html#_sending_a_ping_req)
    1. [5.4. Retrieving and Parsing RSS Data](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_8.html#_retrieving_and_par)
    1. [5.5. Sending Email](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_8.html#_sending_email)
    1. [5.6. Communicating over Queues Using RabbitMQ](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_8.html#_communicating_over)
    1. [5.7. Communicating with Embedded Devices via MQTT](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_8.html#_communicating_with)
    1. [5.8. Using ZeroMQ Concurrently](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_8.html#sec_concurrent_zmq)
    1. [5.9. Creating a TCP Client](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_8.html#sec_network_io_tcp_)
    1. [5.10. Creating a TCP Server](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_8.html#sec_network_io_tcp_)
    1. [5.11. Sending and Receiving UDP Packets](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_8.html#_sending_and_receiv)
1. [6. Databases](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_9.html)
    1. [6.0. Introduction](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_9.html#_introduction_6)
    1. [6.1. Connecting to an SQL Database](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_9.html#sec_db_connecting_t)
    1. [6.2. Connecting to an SQL Database with a Connection Pool](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_9.html#sec_db_connecting_w)
    1. [6.3. Manipulating an SQL Database](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_9.html#sec_db_manipulating)
    1. [6.4. Simplifying SQL with Korma](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_9.html#sec_sql_korma)
    1. [6.5. Performing Full-Text Search with Lucene](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_9.html#_performing_full_te)
    1. [6.6. Indexing Data with ElasticSearch](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_9.html#_indexing_data_with)
    1. [6.7. Working with Cassandra](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_9.html#_working_with_cassa)
    1. [6.8. Working with MongoDB](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_9.html#_working_with_mongo)
    1. [6.9. Working with Redis](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_9.html#_working_with_redis)
    1. [6.10. Connecting to a Datomic Database](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_9.html#sec_datomic_connect)
    1. [6.11. Defining a Schema for a Datomic Database](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_9.html#sec_datomic_schema)
    1. [6.12. Writing Data to Datomic](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_9.html#sec_datomic_transac)
    1. [6.13. Removing Data from a Datomic Database](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_9.html#sec_retract_data)
    1. [6.14. Trying Datomic Transactions Without Committing Them](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_9.html#sec_datomic_dry_run)
    1. [6.15. Traversing Datomic Indexes](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_9.html#_traversing_datomic)
1. [7. Web Applications](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_10.html)
    1. [7.0. Introduction](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_10.html#_introduction_7)
    1. [7.1. Introduction to Ring](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_10.html#sec_webapps_ring_in)
    1. [7.2. Using Ring Middleware](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_10.html#sec_ring_middleware)
    1. [7.3. Serving Static Files with Ring](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_10.html#_serving_static_fil)
    1. [7.4. Handling Form Data with Ring](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_10.html#_handling_form_data)
    1. [7.5. Handling Cookies with Ring](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_10.html#_handling_cookies_w)
    1. [7.6. Storing Sessions with Ring](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_10.html#_storing_sessions_w)
    1. [7.7. Reading and Writing Request and Response Headers in Ring](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_10.html#_reading_and_writin)
    1. [7.8. Routing Requests with Compojure](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_10.html#sec_webapps_compoju)
    1. [7.9. Performing HTTP Redirects with Ring](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_10.html#_performing_http_re)
    1. [7.10. Building a RESTful Application with Liberator](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_10.html#_building_a_restful)
    1. [7.11. Templating HTML with Enlive](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_10.html#sec_enlive)
    1. [7.12. Templating with Selmer](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_10.html#sec_webapps_templat)
    1. [7.13. Templating with Hiccup](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_10.html#sec_hiccup)
    1. [7.14. Rendering Markdown Documents](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_10.html#sec_webapps__markdo)
    1. [7.15. Building Applications with Luminus](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_10.html#sec_webapps__luminu)
1. [8. Performance and Production](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_11.html)
    1. [8.0. Introduction](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_11.html#_introduction_8)
    1. [8.1. AOT Compilation](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_11.html#sec_aot_compilation)
    1. [8.2. Packaging a Project into a JAR File](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_11.html#sec_packaging_jars)
    1. [8.3. Creating a WAR File](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_11.html#_creating_a_war_fil)
    1. [8.4. Running an Application as a Daemon](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_11.html#sec_daemons)
    1. [8.5. Alleviating Performance Problems with Type Hinting](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_11.html#sec_primitives_math)
    1. [8.6. Fast Math with Primitive Java Arrays](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_11.html#sec_deployment_prim)
    1. [8.7. Simple Profiling with Timbre](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_11.html#sec_profiling_timbr)
    1. [8.8. Logging with Timbre](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_11.html#_logging_with_timbr)
    1. [8.9. Releasing a Library to Clojars](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_11.html#sec_deploy_clojars)
    1. [8.10. Using Macros to Simplify API Deprecations](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_11.html#_using_macros_to_si)
1. [9. Distributed Computation](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_12.html)
    1. [9.0. Introduction](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_12.html#_introduction_9)
    1. [9.1. Building an Activity Feed System with Storm](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_12.html#_building_an_activi)
    1. [9.2. Processing Data with an Extract Transform Load (ETL) Pipeline](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_12.html#sec_cascalog_etl)
    1. [9.3. Aggregating Large Files](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_12.html#sec_aggregating_lar)
    1. [9.4. Testing Cascalog Workflows](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_12.html#_testing_cascalog_w)
    1. [9.5. Checkpointing Cascalog Jobs](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_12.html#_checkpointing_casc)
    1. [9.6. Explaining a Cascalog Query](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_12.html#_explaining_a_casca)
    1. [9.7. Running a Cascalog Job on Elastic MapReduce](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_12.html#sec_cascalog_emr)
1. [10. Testing](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_13.html)
    1. [10.0. Introduction](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_13.html#_introduction_10)
    1. [10.1. Unit Testing](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_13.html#sec_unit_testing)
    1. [10.2. Testing with Midje](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_13.html#sec_midje)
    1. [10.3. Thoroughly Testing by Randomizing Inputs](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_13.html#sec_testing_generat)
    1. [10.4. Finding Values That Cause Failure](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_13.html#sec_simplecheck)
    1. [10.5. Running Browser-Based Tests](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_13.html#_running_browser_ba)
    1. [10.6. Tracing Code Execution](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_13.html#_tracing_code_execu)
    1. [10.7. Avoiding Null-Pointer Exceptions with core.typed](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_13.html#sec_avoid_null)
    1. [10.8. Verifying Java Interop Using core.typed](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_13.html#sec_verify_java)
    1. [10.9. Type Checking Higher-Order Functions with core.typed](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_13.html#sec_verify_hof)
1. [Index](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_14.html)
1. [About the Authors](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_15.html)
1. [Colophon](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_16.html)
1. [Copyright](https://ebookreading.net/view/book/Clojure+Cookbook-EB9781449366384_17.html)