![Cover image for Introduction to Distributed Self-Stabilizing Algorithms](https://imgdetail.ebookreading.net/cover/cover/20200920/EB9781681735375.jpg)

[Introduction to Distributed Self-Stabilizing Algorithms](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_1.html "Introduction to Distributed Self-Stabilizing Algorithms")
====================================================================================================================

Author : [Karine Altisen](https://ebookreading.net/search/author/Karine+Altisen),[ 
            Stéphane Devismes](https://ebookreading.net/search/author/+%0D%0A++++++++++++St%C3%A9phane+Devismes),[ 
            Swan Dubois](https://ebookreading.net/search/author/+%0D%0A++++++++++++Swan+Dubois)

Release Date : 2019/04/01

Book Description
-----------------


    
    This book aims at being a comprehensive and pedagogical introduction to the concept of self-stabilization, introduced by Edsger Wybe Dijkstra in 1973.
Self-stabilization characterizes the ability of a distributed algorithm to converge within finite time to a configuration from which its behavior is correct (i.e., satisfies a given specification), regardless the arbitrary initial configuration of the system. This arbitrary initial configuration may be the result of the occurrence of a finite number of transient faults. Hence, self-stabilization is actually considered as a versatile non-masking fault tolerance approach, since it recovers from the effect of any finite number of such faults in a unified manner. Another major interest of such an automatic recovery method comes from the difficulty of resetting malfunctioning devices in a large-scale (and so, geographically spread) distributed system (the Internet, Pair-to-Pair networks, and Delay Tolerant Networks are examples of such distributed systems). Furthermore, self-stabilization is usually recognized as a lightweight property to achieve fault tolerance as compared to other classical fault tolerance approaches. Indeed, the overhead, both in terms of time and space, of state-of-the-art self-stabilizing algorithms is commonly small. This makes self-stabilization very attractive for distributed systems equipped of processes with low computational and memory capabilities, such as wireless sensor networks.
After more than 40 years of existence, self-stabilization is now sufficiently established as an important field of research in theoretical distributed computing to justify its teaching in advanced research-oriented graduate courses. This book is an initiation course, which consists of the formal definition of self-stabilization and its related concepts, followed by a deep review and study of classical (simple) algorithms, commonly used proof schemes and design patterns, as well as premium results issued from the self-stabilizing community. As often happens in the self-stabilizing area, in this book we focus on the proof of correctness and the analytical complexity of the studied distributed self-stabilizing algorithms.
Finally, we underline that most of the algorithms studied in this book are actually dedicated to the high-level atomic-state model, which is the most commonly used computational model in the self-stabilizing area. However, in the last chapter, we present general techniques to achieve self-stabilization in the low-level message passing model, as well as example algorithms.

  

Table of Contents
-----------------

1. [Preface](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_4.html)
1. [Acknowledgments](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_5.html)
1. [Introduction](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_6.html)
    1. [Distributed Self-Stabilizing Systems](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_7.html)
        1. [Major Advantage: Fault Tolerance](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_7.html)
        1. [A Lightweight Approach for Fault Tolerance](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_8.html)
        1. [Other Advantages](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_8.html)
        1. [Relative Drawbacks and Alternatives](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_9.html)
        1. [Expressiveness](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_10.html)
        1. [Taxonomy of the Self-Stabilizing Literature](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_11.html)
    1. [Roadmap of this Book](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_12.html)
1. [Preliminaries](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_13.html)
    1. [Network](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_13.html)
        1. [Local Labeling](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_13.html)
        1. [Graph Notions](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_13.html)
    1. [Computational Model](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_14.html)
        1. [Variables](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_14.html)
        1. [Actions](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_15.html)
        1. [Steps and Executions](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_15.html)
        1. [Daemons](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_16.html)
        1. [Formal Definition](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_17.html)
        1. [Self-Stabilization and Silence](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_17.html)
    1. [Complexity](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_18.html)
        1. [Time Complexity](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_18.html)
        1. [Space Complexity](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_19.html)
1. [Coloring under a Locally Central Unfair Daemon](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_20.html)
    1. [The Problem](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_20.html)
    1. [The Algorithm](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_21.html)
    1. [Proof of Self-Stabilization and Silence](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_22.html)
        1. [Partial Correctness](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_22.html)
        1. [Termination](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_23.html)
    1. [Complexity Analysis](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_24.html)
        1. [Memory Requirement](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_24.html)
        1. [Time Complexity](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_24.html)
1. [Synchronous Unison](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_25.html)
    1. [The Problem](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_25.html)
    1. [The Algorithm](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_25.html)
    1. [Correctness and Time Complexity](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_26.html)
        1. [Closure and Correctness](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_26.html)
        1. [Convergence and Complexity (1/2)](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_27.html)
        1. [Convergence and Complexity (2/2)](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_28.html)
        1. [Memory Requirement](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_29.html)
    1. [Related Work](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_30.html)
1. [BFS Spanning Tree Under a Distributed Unfair Daemon](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_31.html)
    1. [The Problem](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_31.html)
    1. [The Algorithm](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_32.html)
    1. [Proof of Self-Stabilization and Silence](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_33.html)
        1. [Partial Correctness](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_33.html)
        1. [Termination](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_34.html)
    1. [Complexity Analysis](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_35.html)
        1. [Memory Requirement](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_35.html)
        1. [Time Complexity](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_35.html)
1. [Dijkstra's Token Ring](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_37.html)
    1. [The Problem](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_37.html)
    1. [The Algorithm](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_38.html)
    1. [Study Assuming K n and a Distributed Unfair Daemon](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_39.html)
        1. [Proof of Self-Stabilization](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_39.html)
        1. [Complexity Analysis (1/3)](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_41.html)
        1. [Complexity Analysis (2/3)](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_42.html)
        1. [Complexity Analysis (3/3)](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_43.html)
    1. [Study Assuming K n-1 and a Locally Central Unfair Daemon](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_44.html)
        1. [Proof of Self-Stabilization](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_44.html)
        1. [Complexity Analysis (1/2)](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_45.html)
        1. [Complexity Analysis (2/2)](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_46.html)
1. [Hierarchical Collateral Composition](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_47.html)
    1. [Hierarchical Collateral Composition](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_48.html)
        1. [Definition](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_48.html)
        1. [A Sufficient Condition](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_48.html)
    1. [A Toy Example](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_49.html)
        1. [Algorithm BFS](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_50.html)
        1. [Algorithm STM](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_51.html)
        1. [Algorithm INMAX](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_52.html)
    1. [Hierarchical vs. Nonhierarchical Collateral Composition](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_53.html)
1. [Self-Stabilization in Message Passing Systems](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_54.html)
    1. [Message Passing for Self-Stabilizing Systems](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_54.html)
        1. [Communication Links](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_54.html)
        1. [Process Execution](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_55.html)
        1. [Configurations of the System](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_56.html)
    1. [Related Work](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_56.html)
    1. [A Lightweight Technique for Silent Algorithms](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_57.html)
        1. [Silence in Message Passing](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_57.html)
        1. [The Transformer](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_58.html)
        1. [An Example](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_58.html)
        1. [Memory Requirement](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_59.html)
        1. [Children](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_60.html)
        1. [Limit](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_60.html)
    1. [Self-Stabilization Assuming Bounded-Capacity Links](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_60.html)
        1. [Message Passing Version of the Token Ring Algorithm of Dijkstra](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_60.html)
        1. [Data-Link Protocol](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_61.html)
        1. [From Atomic-State to Message Passing Model](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_62.html)
        1. [Propagation of Information with Feedback (PIF)](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_63.html)
        1. [A PIF-Based Universal Transformer](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_64.html)
    1. [Stabilization Time in Message Passing](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_65.html)
1. [Bibliography (1/3)](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_66.html)
1. [Bibliography (2/3)](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_67.html)
1. [Bibliography (3/3)](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_68.html)
1. [Authors' Biographies](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_69.html)
1. [Index](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_70.html)
1. [Blank Page (1/3)](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_1.html)
1. [Blank Page (2/3)](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_2.html)
1. [Blank Page (3/3)](https://ebookreading.net/view/book/Introduction+to+Distributed+Self-Stabilizing+Algorithms-EB9781681735375_3.html)
