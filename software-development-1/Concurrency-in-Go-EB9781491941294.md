![Cover image for Concurrency in Go](https://imgdetail.ebookreading.net/cover/cover/software_development/EB9781491941294.jpg)

[Concurrency in Go](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_1.html "Concurrency in Go")
====================================================================================================================

Author : [Katherine Cox-Buday](https://ebookreading.net/search/author/Katherine+Cox-Buday)

Release Date : 2017/08/01

ISBN : 9781491941294

Topic : [Software Development](https://ebookreading.net/search/category/software-development)

Book Description
-----------------

 Concurrency can be notoriously difficult to get right, but fortunately, the Go open source programming language makes working with concurrency tractable and even easy. If you’re a developer familiar with Go, this practical book demonstrates best practices and patterns to help you incorporate concurrency into your systems.
Author Katherine Cox-Buday takes you step-by-step through the process. You’ll understand how Go chooses to model concurrency, what issues arise from this model, and how you can compose primitives within this model to solve problems. Learn the skills and tooling you need to confidently write and implement concurrent systems of any size.
Understand how Go addresses fundamental problems that make concurrency difficult to do correctlyLearn the key differences between concurrency and parallelismDig into the syntax of Go’s memory synchronization primitivesForm patterns with these primitives to write maintainable concurrent codeCompose patterns into a series of practices that enable you to write large, distributed systems that scaleLearn the sophistication behind goroutines and how Go’s runtime stitches everything together        Show and hide more                
Table of Contents
-----------------

1. [Preface](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_5.html#idm140183166942944)
    1. [Who Should Read This Book](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_5.html#idm140183166935824)
    1. [Navigating This Book](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_5.html#idm140183166866176)
    1. [Online Resources](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_5.html#idm140183166964688)
    1. [Conventions Used in This Book](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_5.html#idm140183166949984)
    1. [Using Code Examples](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_5.html#idm140183167006848)
    1. [O’Reilly Safari](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_5.html#idm140183167003312)
    1. [How to Contact Us](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_5.html#idm140183166996640)
    1. [Acknowledgments](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_5.html#idm140183166996048)
1. [1. An Introduction to Concurrency](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_6.html#intro_to_concurrenc)
    1. [Moore’s Law, Web Scale, and the Mess We’re In](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_6.html#idm140183167028768)
    1. [Why Is Concurrency Hard?](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_6.html#concurrency_hard_q)
        1. [Race Conditions](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_6.html#idm140183162916800)
        1. [Atomicity](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_6.html#atomicity)
        1. [Memory Access Synchronization](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_6.html#memory_access_synch)
        1. [Deadlocks, Livelocks, and Starvation](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_6.html#deadlocks_livelocks)
        1. [Determining Concurrency Safety](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_6.html#det_concur_safety)
    1. [Simplicity in the Face of Complexity](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_6.html#idm140183162920560)
1. [2. Modeling Your Code: Communicating Sequential Processes](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_7.html#modelling_your_code)
    1. [The Difference Between Concurrency and Parallelism](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_7.html#dif_concur_parallel)
    1. [What Is CSP?](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_7.html#idm140183157800528)
    1. [How This Helps You](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_7.html#how_this_helps_you)
    1. [Go’s Philosophy on Concurrency](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_7.html#go_philosophy)
1. [3. Go’s Concurrency Building Blocks](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_8.html#gos_concurrency_bui)
    1. [Goroutines](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_8.html#goroutines)
    1. [The sync Package](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_8.html#sync_package)
        1. [WaitGroup](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_8.html#idm140183156311376)
        1. [Mutex and RWMutex](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_8.html#idm140183156107584)
        1. [Cond](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_8.html#idm140183156036720)
        1. [Once](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_8.html#idm140183155727232)
        1. [Pool](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_8.html#idm140183154950464)
    1. [Channels](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_8.html#channels)
    1. [The select Statement](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_8.html#select_statement)
    1. [The GOMAXPROCS Lever](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_8.html#idm140183153247184)
    1. [Conclusion](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_8.html#idm140183150835728)
1. [4. Concurrency Patterns in Go](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_9.html#concurrency_pattern)
    1. [Confinement](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_9.html#confinement)
    1. [The for-select Loop](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_9.html#idm140183150292448)
    1. [Preventing Goroutine Leaks](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_9.html#prevent_gor_leaks)
    1. [The or-channel](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_9.html#or_channel)
    1. [Error Handling](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_9.html#error_handling)
    1. [Pipelines](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_9.html#pipelines)
        1. [Best Practices for Constructing Pipelines](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_9.html#idm140183147854032)
        1. [Some Handy Generators](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_9.html#idm140183147853056)
    1. [Fan-Out, Fan-In](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_9.html#fano_fani)
    1. [The or-done-channel](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_9.html#idm140183146210128)
    1. [The tee-channel](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_9.html#idm140183145449632)
    1. [The bridge-channel](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_9.html#bridgechannel)
    1. [Queuing](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_9.html#queuing)
    1. [The context Package](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_9.html#context_package)
    1. [Summary](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_9.html#idm140183143866304)
1. [5. Concurrency at Scale](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_10.html#concurrency_at_scal)
    1. [Error Propagation](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_10.html#idm140183140127008)
    1. [Timeouts and Cancellation](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_10.html#idm140183140125520)
    1. [Heartbeats](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_10.html#heartbeats)
    1. [Replicated Requests](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_10.html#replicated_requests)
    1. [Rate Limiting](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_10.html#idm140183142368240)
    1. [Healing Unhealthy Goroutines](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_10.html#healing_unhealthy_g)
    1. [Summary](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_10.html#idm140183135458960)
1. [6. Goroutines and the Go Runtime](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_11.html#goroutines_and_the_)
    1. [Work Stealing](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_11.html#idm140183134033776)
        1. [Stealing Tasks or Continuations?](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_11.html#idm140183133747952)
    1. [Presenting All of This to the Developer](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_11.html#idm140183133746272)
    1. [Conclusion](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_11.html#idm140183133370400)
1. [A. Appendix](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_12.html#appendix)
    1. [Anatomy of a Goroutine Error](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_12.html#idm140183133366192)
    1. [Race Detection](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_12.html#idm140183133318704)
    1. [pprof](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_12.html#idm140183133318176)
1. [Index](https://ebookreading.net/view/book/Concurrency+in+Go-EB9781491941294_13.html#idm140183132894992)
