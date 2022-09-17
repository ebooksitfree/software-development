![Cover image for High Performance Python](https://imgdetail.ebookreading.net/cover/cover/software_development/EB9781449361747.jpg)

[High Performance Python](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_1.html "High Performance Python")
====================================================================================================================

Author : [Ian Ozsvald](https://ebookreading.net/search/author/Ian+Ozsvald),[ Micha Gorelick](https://ebookreading.net/search/author/+Micha+Gorelick)

Release Date : 2014/09/01

ISBN : 9781449361747

Topic : [Software Development](https://ebookreading.net/search/category/software-development)

Book Description
-----------------

Your Python code may run correctly, but you need it to run faster. By exploring the fundamental theory behind design choices, this practical guide helps you gain a deeper understanding of Python’s implementation. You’ll learn how to locate performance bottlenecks and significantly speed up your code in high-data-volume programs.
How can you take advantage of multi-core architectures or clusters? Or build a system that can scale up and down without losing reliability? Experienced Python programmers will learn concrete solutions to these and other issues, along with war stories from companies that use high performance Python for social media analytics, productionized machine learning, and other situations.
Get a better grasp of numpy, Cython, and profilersLearn how Python abstracts the underlying computer architectureUse profiling to find bottlenecks in CPU time and memory usageWrite efficient programs by choosing appropriate data structuresSpeed up matrix and vector computationsUse tools to compile Python down to machine codeManage multiple I/O and computational operations concurrentlyConvert multiprocessing code to run on a local or remote clusterSolve large problems while using less RAM              
Table of Contents
-----------------

1. [Preface](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_3.html)
    1. [Who This Book Is For](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_3.html#_who_this_book_is_f)
    1. [Who This Book Is Not For](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_3.html#_who_this_book_is_n)
    1. [What You’ll Learn](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_3.html#_what_you_8217_ll_l)
    1. [Python 2.7](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_3.html#_python_2_7)
    1. [Moving to Python 3](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_3.html#_moving_to_python_3)
    1. [License](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_3.html#_license)
    1. [How to Make an Attribution](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_3.html#_how_to_make_an_att)
    1. [Errata and Feedback](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_3.html#_errata_and_feedbac)
    1. [Conventions Used in This Book](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_3.html#_conventions_used_i)
    1. [Using Code Examples](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_3.html#_using_code_example)
    1. [Safari® Books Online](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_3.html#_safari_books_onlin)
    1. [How to Contact Us](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_3.html#how_to_contact_us)
    1. [Acknowledgments](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_3.html#_acknowledgments)
1. [1. Understanding Performant Python](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_4.html)
    1. [The Fundamental Computer System](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_4.html#_the_fundamental_co)
        1. [Computing Units](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_4.html#_computing_units)
        1. [Memory Units](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_4.html#_memory_units)
        1. [Communications Layers](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_4.html#understanding_pp_co)
    1. [Putting the Fundamental Elements Together](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_4.html#_putting_the_fundam)
        1. [Idealized Computing Versus the Python Virtual Machine](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_4.html#understanding-perfo)
            1. [Idealized computing](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_4.html#_idealized_computin)
            1. [Python’s virtual machine](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_4.html#_python_8217_s_virt)
    1. [So Why Use Python?](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_4.html#_so_why_use_python)
1. [2. Profiling to Find Bottlenecks](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_5.html)
    1. [Profiling Efficiently](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_5.html#_profiling_efficien)
    1. [Introducing the Julia Set](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_5.html#_introducing_the_ju)
    1. [Calculating the Full Julia Set](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_5.html#_calculating_the_fu)
    1. [Simple Approaches to Timing—print and a Decorator](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_5.html#_simple_approaches_)
    1. [Simple Timing Using the Unix time Command](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_5.html#_simple_timing_usin)
    1. [Using the cProfile Module](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_5.html#profiling-cprofile)
    1. [Using runsnakerun to Visualize cProfile Output](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_5.html#_using_runsnakerun_)
    1. [Using line_profiler for Line-by-Line Measurements](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_5.html#profiling-line-prof)
    1. [Using memory_profiler to Diagnose Memory Usage](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_5.html#memory_profiler)
    1. [Inspecting Objects on the Heap with heapy](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_5.html#profiling-heapy)
    1. [Using dowser for Live Graphing of Instantiated Variables](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_5.html#profiling-dowser)
    1. [Using the dis Module to Examine CPython Bytecode](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_5.html#profiling-dis)
        1. [Different Approaches, Different Complexity](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_5.html#_different_approach)
    1. [Unit Testing During Optimization to Maintain Correctness](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_5.html#profiling-unit-test)
        1. [No-op @profile Decorator](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_5.html#no_op_profile_decor)
    1. [Strategies to Profile Your Code Successfully](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_5.html#profiling-strategie)
    1. [Wrap-Up](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_5.html#_wrap_up)
1. [3. Lists and Tuples](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_6.html)
    1. [A More Efficient Search](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_6.html#_a_more_efficient_s)
    1. [Lists Versus Tuples](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_6.html#_lists_versus_tuple)
        1. [Lists as Dynamic Arrays](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_6.html#list_as_dynamic_arr)
        1. [Tuples As Static Arrays](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_6.html#tuples_as_static_ar)
    1. [Wrap-Up](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_6.html#_wrap_up_2)
1. [4. Dictionaries and Sets](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_7.html)
    1. [How Do Dictionaries and Sets Work?](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_7.html#dict_set_how_work)
        1. [Inserting and Retrieving](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_7.html#_inserting_and_retr)
        1. [Deletion](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_7.html#_deletion)
        1. [Resizing](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_7.html#_resizing)
        1. [Hash Functions and Entropy](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_7.html#SEC-dict-set-hash-a)
    1. [Dictionaries and Namespaces](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_7.html#dict_namespace)
    1. [Wrap-Up](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_7.html#_wrap_up_3)
1. [5. Iterators and Generators](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_8.html)
    1. [Iterators for Infinite Series](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_8.html#iterators_inf)
    1. [Lazy Generator Evaluation](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_8.html#_lazy_generator_eva)
    1. [Wrap-Up](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_8.html#_wrap_up_4)
1. [6. Matrix and Vector Computation](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_9.html)
    1. [Introduction to the Problem](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_9.html#matrix_intro)
    1. [Aren’t Python Lists Good Enough?](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_9.html#arent_python_lists_)
        1. [Problems with Allocating Too Much](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_9.html#_problems_with_allo)
    1. [Memory Fragmentation](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_9.html#matrix_memory_fragm)
        1. [Understanding perf](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_9.html#_understanding_perf)
        1. [Making Decisions with perf’s Output](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_9.html#_making_decisions_w)
        1. [Enter numpy](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_9.html#_enter_numpy)
    1. [Applying numpy to the Diffusion Problem](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_9.html#_applying_numpy_to_)
        1. [Memory Allocations and In-Place Operations](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_9.html#_memory_allocations)
        1. [Selective Optimizations: Finding What Needs to Be Fixed](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_9.html#matrix_selective_op)
    1. [numexpr: Making In-Place Operations Faster and Easier](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_9.html#_numexpr_making_in_)
    1. [A Cautionary Tale: Verify “Optimizations” (scipy)](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_9.html#_a_cautionary_tale_)
    1. [Wrap-Up](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_9.html#_wrap_up_5)
1. [7. Compiling to C](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_10.html)
    1. [What Sort of Speed Gains Are Possible?](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_10.html#_what_sort_of_speed)
    1. [JIT Versus AOT Compilers](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_10.html#jit_vs_compiler)
    1. [Why Does Type Information Help the Code Run Faster?](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_10.html#_why_does_type_info)
    1. [Using a C Compiler](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_10.html#_using_a_c_compiler)
    1. [Reviewing the Julia Set Example](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_10.html#_reviewing_the_juli)
    1. [Cython](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_10.html#compiling-cython)
        1. [Compiling a Pure-Python Version Using Cython](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_10.html#_compiling_a_pure_p)
        1. [Cython Annotations to Analyze a Block of Code](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_10.html#_cython_annotations)
        1. [Adding Some Type Annotations](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_10.html#_adding_some_type_a)
    1. [Shed Skin](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_10.html#_shed_skin)
        1. [Building an Extension Module](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_10.html#_building_an_extens)
        1. [The Cost of the Memory Copies](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_10.html#_the_cost_of_the_me)
    1. [Cython and numpy](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_10.html#compiling-cython-an)
        1. [Parallelizing the Solution with OpenMP on One Machine](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_10.html#compiling-cython-om)
    1. [Numba](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_10.html#_numba)
    1. [Pythran](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_10.html#_pythran)
    1. [PyPy](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_10.html#compiling-pypy)
        1. [Garbage Collection Differences](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_10.html#_garbage_collection)
        1. [Running PyPy and Installing Modules](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_10.html#_running_pypy_and_i)
    1. [When to Use Each Technology](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_10.html#_when_to_use_each_t)
        1. [Other Upcoming Projects](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_10.html#_other_upcoming_pro)
        1. [A Note on Graphics Processing Units (GPUs)](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_10.html#_a_note_on_graphics)
        1. [A Wish for a Future Compiler Project](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_10.html#_a_wish_for_a_futur)
    1. [Foreign Function Interfaces](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_10.html#_foreign_function_i)
        1. [ctypes](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_10.html#_ctypes)
        1. [cffi](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_10.html#_cffi)
        1. [f2py](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_10.html#_f2py)
        1. [CPython Module](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_10.html#_cpython_module)
    1. [Wrap-Up](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_10.html#_wrap_up_6)
1. [8. Concurrency](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_11.html)
    1. [Introduction to Asynchronous Programming](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_11.html#_introduction_to_as)
    1. [Serial Crawler](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_11.html#_serial_crawler)
    1. [gevent](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_11.html#_gevent)
    1. [tornado](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_11.html#_tornado)
    1. [AsyncIO](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_11.html#_asyncio)
    1. [Database Example](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_11.html#_database_example)
    1. [Wrap-Up](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_11.html#_wrap_up_7)
1. [9. The multiprocessing Module](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_12.html)
    1. [An Overview of the Multiprocessing Module](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_12.html#_an_overview_of_the)
    1. [Estimating Pi Using the Monte Carlo Method](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_12.html#_estimating_pi_usin)
    1. [Estimating Pi Using Processes and Threads](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_12.html#multiprocessing-est)
        1. [Using Python Objects](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_12.html#_using_python_objec)
        1. [Random Numbers in Parallel Systems](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_12.html#multiprocessing-ran)
        1. [Using numpy](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_12.html#multiprocessing-est)
    1. [Finding Prime Numbers](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_12.html#multiprocessing-fin)
        1. [Queues of Work](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_12.html#_queues_of_work)
            1. [Asynchronously adding jobs to the Queue](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_12.html#_asynchronously_add)
    1. [Verifying Primes Using Interprocess Communication](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_12.html#multiprocessing-ver)
        1. [Serial Solution](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_12.html#_serial_solution)
        1. [Naive Pool Solution](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_12.html#_naive_pool_solutio)
        1. [A Less Naive Pool Solution](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_12.html#_a_less_naive_pool_)
        1. [Using Manager.Value as a Flag](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_12.html#_using_manager_valu)
        1. [Using Redis as a Flag](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_12.html#multiprocessing-usi)
        1. [Using RawValue as a Flag](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_12.html#_using_rawvalue_as_)
        1. [Using mmap as a Flag](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_12.html#_using_mmap_as_a_fl)
        1. [Using mmap as a Flag Redux](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_12.html#_using_mmap_as_a_fl)
    1. [Sharing numpy Data with multiprocessing](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_12.html#multiprocessing-sha)
    1. [Synchronizing File and Variable Access](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_12.html#_synchronizing_file)
        1. [File Locking](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_12.html#_file_locking)
        1. [Locking a Value](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_12.html#_locking_a_value)
    1. [Wrap-Up](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_12.html#_wrap_up_8)
1. [10. Clusters and Job Queues](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_13.html)
    1. [Benefits of Clustering](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_13.html#_benefits_of_cluste)
    1. [Drawbacks of Clustering](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_13.html#_drawbacks_of_clust)
        1. [$462 Million Wall Street Loss Through Poor Cluster Upgrade Strategy](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_13.html#_462_million_wall_s)
        1. [Skype’s 24-Hour Global Outage](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_13.html#_skype_8217_s_24_ho)
    1. [Common Cluster Designs](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_13.html#_common_cluster_des)
    1. [How to Start a Clustered Solution](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_13.html#_how_to_start_a_clu)
    1. [Ways to Avoid Pain When Using Clusters](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_13.html#_ways_to_avoid_pain)
    1. [Three Clustering Solutions](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_13.html#_three_clustering_s)
        1. [Using the Parallel Python Module for Simple Local Clusters](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_13.html#cluster-parallelpyt)
        1. [Using IPython Parallel to Support Research](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_13.html#clustering-ipython)
    1. [NSQ for Robust Production Clustering](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_13.html#_nsq_for_robust_pro)
        1. [Queues](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_13.html#_queues)
        1. [Pub/sub](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_13.html#_pub_sub)
        1. [Distributed Prime Calculation](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_13.html#_distributed_prime_)
    1. [Other Clustering Tools to Look At](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_13.html#_other_clustering_t)
    1. [Wrap-Up](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_13.html#_wrap_up_9)
1. [11. Using Less RAM](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_14.html)
    1. [Objects for Primitives Are Expensive](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_14.html#_objects_for_primit)
        1. [The Array Module Stores Many Primitive Objects Cheaply](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_14.html#_the_array_module_s)
    1. [Understanding the RAM Used in a Collection](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_14.html#_understanding_the_)
    1. [Bytes Versus Unicode](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_14.html#_bytes_versus_unico)
    1. [Efficiently Storing Lots of Text in RAM](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_14.html#_efficiently_storin)
        1. [Trying These Approaches on 8 Million Tokens](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_14.html#_trying_these_appro)
            1. [list](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_14.html#_list)
            1. [set](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_14.html#_set)
            1. [More efficient tree structures](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_14.html#_more_efficient_tre)
            1. [Directed acyclic word graph (DAWG)](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_14.html#_directed_acyclic_w)
            1. [Marisa trie](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_14.html#_marisa_trie)
            1. [Datrie](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_14.html#memory_datrie)
            1. [HAT trie](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_14.html#_hat_trie)
            1. [Using tries (and DAWGs) in production systems](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_14.html#_using_tries_and_da)
    1. [Tips for Using Less RAM](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_14.html#_tips_for_using_les)
    1. [Probabilistic Data Structures](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_14.html#less_ram_prob_ds)
        1. [Very Approximate Counting with a 1-byte Morris Counter](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_14.html#_very_approximate_c)
        1. [K-Minimum Values](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_14.html#_k_minimum_values)
        1. [Bloom Filters](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_14.html#_bloom_filters)
        1. [LogLog Counter](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_14.html#_loglog_counter)
        1. [Real-World Example](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_14.html#_real_world_example)
1. [12. Lessons from the Field](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_15.html)
    1. [Adaptive Lab’s Social Media Analytics (SoMA)](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_15.html#lessons-from-field-)
        1. [Python at Adaptive Lab](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_15.html#_python_at_adaptive)
        1. [SoMA’s Design](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_15.html#_soma_s_design)
        1. [Our Development Methodology](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_15.html#_our_development_me)
        1. [Maintaining SoMA](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_15.html#_maintaining_soma)
        1. [Advice for Fellow Engineers](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_15.html#_advice_for_fellow_)
    1. [Making Deep Learning Fly with RadimRehurek.com](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_15.html#lessons-from-field-)
        1. [The Sweet Spot](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_15.html#_the_sweet_spot)
        1. [Lessons in Optimizing](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_15.html#_lessons_in_optimiz)
        1. [Wrap-Up](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_15.html#_wrap_up_10)
    1. [Large-Scale Productionized Machine Learning at Lyst.com](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_15.html#lessons-from-field-)
        1. [Python’s Place at Lyst](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_15.html#_python_s_place_at_)
        1. [Cluster Design](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_15.html#_cluster_design)
        1. [Code Evolution in a Fast-Moving Start-Up](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_15.html#_code_evolution_in_)
        1. [Building the Recommendation Engine](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_15.html#_building_the_recom)
        1. [Reporting and Monitoring](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_15.html#_reporting_and_moni)
        1. [Some Advice](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_15.html#_some_advice)
    1. [Large-Scale Social Media Analysis at Smesh](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_15.html#lessons-from-field-)
        1. [Python’s Role at Smesh](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_15.html#_python_s_role_at_s)
        1. [The Platform](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_15.html#_the_platform)
        1. [High Performance Real-Time String Matching](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_15.html#_high_performance_r)
        1. [Reporting, Monitoring, Debugging, and Deployment](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_15.html#_reporting_monitori)
    1. [PyPy for Successful Web and Data Processing Systems](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_15.html#lessons-from-field-)
        1. [Prerequisites](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_15.html#_prerequisites)
        1. [The Database](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_15.html#_the_database)
        1. [The Web Application](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_15.html#_the_web_applicatio)
        1. [OCR and Translation](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_15.html#_ocr_and_translatio)
        1. [Task Distribution and Workers](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_15.html#_task_distribution_)
        1. [Conclusion](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_15.html#_conclusion)
    1. [Task Queues at Lanyrd.com](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_15.html#lessons-from-field-)
        1. [Python’s Role at Lanyrd](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_15.html#_python_s_role_at_l)
        1. [Making the Task Queue Performant](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_15.html#_making_the_task_qu)
        1. [Reporting, Monitoring, Debugging, and Deployment](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_15.html#_reporting_monitori)
        1. [Advice to a Fellow Developer](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_15.html#_advice_to_a_fellow)
1. [Index](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_16.html)
1. [Colophon](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_17.html)
1. [Copyright](https://ebookreading.net/view/book/High+Performance+Python-EB9781449361747_18.html)