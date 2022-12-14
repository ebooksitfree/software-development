![Cover image for Designing Distributed Systems](https://imgdetail.ebookreading.net/cover/cover/software_development/EB9781491983638.jpg)

[Designing Distributed Systems](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_1.html "Designing Distributed Systems")
====================================================================================================================

Author : [Brendan Burns](https://ebookreading.net/search/author/Brendan+Burns)

Release Date : 2018/02/01

ISBN : 9781491983638

Topic : [Software Development](https://ebookreading.net/search/category/software-development)

Book Description
-----------------

Without established design patterns to guide them, developers have had to build distributed systems from scratch, and most of these systems are very unique indeed. Today, the increasing use of containers has paved the way for core distributed system patterns and reusable containerized components. This practical guide presents a collection of repeatable, generic patterns to help make the development of reliable distributed systems far more approachable and efficient.
Author Brendan Burns—Director of Engineering at Microsoft Azure—demonstrates how you can adapt existing software design patterns for designing and building reliable distributed applications. Systems engineers and application developers will learn how these long-established patterns provide a common language and framework for dramatically increasing the quality of your system.
Understand how patterns and reusable components enable the rapid development of reliable distributed systemsUse the side-car, adapter, and ambassador patterns to split your application into a group of containers on a single machineExplore loosely coupled multi-node distributed patterns for replication, scaling, and communication between the componentsLearn distributed system patterns for large-scale batch data processing covering work-queues, event-based processing, and coordinated workflows              
Table of Contents
-----------------

1. [Preface](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_3.html#idm139824744643248)
    1. [Who Should Read This Book](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_3.html#idm139824744498144)
    1. [Why I Wrote This Book](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_3.html#idm139824744745040)
    1. [The World of Distributed Systems Today](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_3.html#idm139824744775600)
    1. [Navigating This Book](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_3.html#idm139824744726256)
    1. [Conventions Used in This Book](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_3.html#idm139824744912688)
    1. [Online Resources](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_3.html#idm139824744606832)
    1. [Using Code Examples](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_3.html#idm139824744616624)
    1. [O’Reilly Safari](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_3.html#idm139824744395920)
    1. [How to Contact Us](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_3.html#idm139824744389536)
    1. [Acknowledgments](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_3.html#idm139824744388944)
1. [1. Introduction](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_4.html#introduction_chapte)
    1. [A Brief History of Systems Development](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_4.html#idm139824744368304)
    1. [A Brief History of Patterns in Software Development](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_4.html#idm139824743303664)
        1. [Formalization of Algorithmic Programming](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_4.html#idm139824743299360)
        1. [Patterns for Object-Oriented Programming](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_4.html#idm139824743293952)
        1. [The Rise of Open Source Software](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_4.html#idm139824743287024)
    1. [The Value of Patterns, Practices, and Components](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_4.html#idm139824743278656)
        1. [Standing on the Shoulders of Giants](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_4.html#idm139824743273984)
        1. [A Shared Language for Discussing Our Practice](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_4.html#idm139824743269024)
        1. [Shared Components for Easy Reuse](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_4.html#idm139824744832352)
    1. [Summary](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_4.html#idm139824744824720)
1. [I. Single-Node Patterns](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_5.html#part01)
    1. [Motivations](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_5.html#idm139824744805872)
    1. [Summary](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_5.html#idm139824744440624)
1. [2. The Sidecar Pattern](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_6.html#sidecar_chapter_id)
    1. [An Example Sidecar: Adding HTTPS to a Legacy Service](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_6.html#idm139824744418064)
    1. [Dynamic Configuration with Sidecars](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_6.html#idm139824744409360)
    1. [Modular Application Containers](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_6.html#idm139824744398880)
        1. [Hands On: Deploying the topz Container](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_6.html#idm139824744592288)
    1. [Building a Simple PaaS with Sidecars](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_6.html#idm139824739791536)
    1. [Designing Sidecars for Modularity and Reusability](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_6.html#idm139824741226976)
        1. [Parameterized Containers](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_6.html#idm139824740990464)
        1. [Define Each Container’s API](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_6.html#idm139824739601232)
        1. [Documenting Your Containers](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_6.html#idm139824744576736)
    1. [Summary](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_6.html#idm139824744576112)
1. [3. Ambassadors](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_7.html#ambassadors_id)
    1. [Using an Ambassador to Shard a Service](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_7.html#idm139824739640656)
        1. [Hands On: Implementing a Sharded Redis](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_7.html#idm139824739575520)
    1. [Using an Ambassador for Service Brokering](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_7.html#idm139824739574928)
    1. [Using an Ambassador to Do Experimentation or Request Splitting](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_7.html#idm139824739150208)
        1. [Hands On: Implementing 10% Experiments](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_7.html#idm139824739139168)
1. [4. Adapters](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_8.html#adapters_id)
    1. [Monitoring](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_8.html#idm139824738910608)
        1. [Hands On: Using Prometheus for Monitoring](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_8.html#idm139824738902496)
    1. [Logging](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_8.html#idm139824738889488)
        1. [Hands On: Normalizing Different Logging Formats with Fluentd](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_8.html#idm139824738877712)
    1. [Adding a Health Monitor](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_8.html#idm139824738858656)
        1. [Hands On: Adding Rich Health Monitoring for MySQL](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_8.html#idm139824738845552)
1. [II. Serving Patterns](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_9.html#part02)
    1. [Introduction to Microservices](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_9.html#idm139824738817872)
1. [5. Replicated Load-Balanced Services](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_10.html#replicated_load_bal)
    1. [Stateless Services](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_10.html#idm139824738719296)
        1. [Readiness Probes for Load Balancing](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_10.html#idm139824738700608)
        1. [Hands On: Creating a Replicated Service in Kubernetes](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_10.html#idm139824738694016)
    1. [Session Tracked Services](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_10.html#idm139824738693392)
    1. [Application-Layer Replicated Services](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_10.html#idm139824738508352)
    1. [Introducing a Caching Layer](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_10.html#idm139824738504592)
        1. [Deploying Your Cache](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_10.html#idm139824738398880)
        1. [Hands On: Deploying the Caching Layer](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_10.html#idm139824738569312)
    1. [Expanding the Caching Layer](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_10.html#idm139824738568688)
        1. [Rate Limiting and Denial-of-Service Defense](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_10.html#idm139824738043728)
        1. [SSL Termination](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_10.html#idm139824738047408)
        1. [Hands On: Deploying nginx and SSL Termination](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_10.html#idm139824738134288)
    1. [Summary](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_10.html#idm139824738133344)
1. [6. Sharded Services](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_11.html#sharded_id)
    1. [Sharded Caching](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_11.html#idm139824737781248)
        1. [Why You Might Need a Sharded Cache](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_11.html#idm139824737890592)
        1. [The Role of the Cache in System Performance](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_11.html#idm139824737886544)
        1. [Replicated, Sharded Caches](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_11.html#idm139824737873296)
        1. [Hands On: Deploying an Ambassador and Memcache for a Sharded Cache](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_11.html#idm139824737868400)
    1. [An Examination of Sharding Functions](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_11.html#idm139824737867456)
        1. [Selecting a Key](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_11.html#idm139824736971600)
        1. [Consistent Hashing Functions](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_11.html#idm139824736971040)
        1. [Hands On: Building a Consistent HTTP Sharding Proxy](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_11.html#idm139824737135296)
    1. [Sharded, Replicated Serving](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_11.html#idm139824737012704)
    1. [Hot Sharding Systems](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_11.html#idm139824737093184)
1. [7. Scatter/Gather](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_12.html#scatter_gather_id)
    1. [Scatter/Gather with Root Distribution](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_12.html#idm139824736936256)
        1. [Hands On: Distributed Document Search](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_12.html#idm139824737106448)
    1. [Scatter/Gather with Leaf Sharding](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_12.html#idm139824736917696)
        1. [Hands On: Sharded Document Search](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_12.html#idm139824736909616)
        1. [Choosing the Right Number of Leaves](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_12.html#idm139824736899344)
    1. [Scaling Scatter/Gather for Reliability and Scale](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_12.html#idm139824736883808)
1. [8. Functions and Event-Driven Processing](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_13.html#functions_id)
    1. [Determining When FaaS Makes Sense](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_13.html#idm139824736863360)
        1. [The Benefits of FaaS](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_13.html#idm139824736859728)
        1. [The Challenges of FaaS](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_13.html#idm139824736855216)
        1. [The Need for Background Processing](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_13.html#idm139824736826752)
        1. [The Need to Hold Data in Memory](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_13.html#idm139824736824032)
        1. [The Costs of Sustained Request-Based Processing](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_13.html#idm139824736820144)
    1. [Patterns for FaaS](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_13.html#idm139824736812000)
        1. [The Decorator Pattern: Request or Response Transformation](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_13.html#idm139824736807648)
        1. [Hands On: Adding Request Defaulting Prior to Request Processing](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_13.html#idm139824736786464)
        1. [Handling Events](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_13.html#idm139824736777456)
        1. [Hands On: Implementing Two-Factor Authentication](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_13.html#idm139824736767040)
        1. [Event-Based Pipelines](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_13.html#idm139824736766384)
        1. [Hands On: Implementing a Pipeline for New-User Signup](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_13.html#idm139824736743312)
1. [9. Ownership Election](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_14.html#master_election_id)
    1. [Determining If You Even Need Master Election](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_14.html#idm139824736711552)
    1. [The Basics of Master Election](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_14.html#idm139824736699872)
        1. [Hands On: Deploying etcd](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_14.html#idm139824736682864)
        1. [Implementing Locks](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_14.html#idm139824736682240)
        1. [Hands On: Implementing Locks in etcd](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_14.html#idm139824736557056)
        1. [Implementing Ownership](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_14.html#idm139824736345776)
        1. [Hands On: Implementing Leases in etcd](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_14.html#idm139824736265568)
    1. [Handling Concurrent Data Manipulation](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_14.html#idm139824736699280)
1. [III. Batch Computational Patterns](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_15.html#part03)
1. [10. Work Queue Systems](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_16.html#work_queues_id)
    1. [A Generic Work Queue System](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_16.html#idm139824736041920)
        1. [The Source Container Interface](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_16.html#idm139824736033472)
        1. [The Worker Container Interface](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_16.html#idm139824736026336)
        1. [The Shared Work Queue Infrastructure](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_16.html#idm139824735976512)
    1. [Hands On: Implementing a Video Thumbnailer](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_16.html#idm139824735975920)
    1. [Dynamic Scaling of the Workers](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_16.html#idm139824735956320)
    1. [The Multi-Worker Pattern](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_16.html#idm139824735936240)
1. [11. Event-Driven Batch Processing](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_17.html#event_driven_chapte)
    1. [Patterns of Event-Driven Processing](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_17.html#idm139824735917712)
        1. [Copier](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_17.html#idm139824735913168)
        1. [Filter](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_17.html#idm139824735905984)
        1. [Splitter](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_17.html#idm139824735898432)
        1. [Sharder](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_17.html#idm139824735890336)
        1. [Merger](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_17.html#idm139824735876720)
    1. [Hands On: Building an Event-Driven Flow for New User Sign-Up](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_17.html#idm139824735867456)
    1. [Publisher/Subscriber Infrastructure](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_17.html#idm139824735852848)
    1. [Hands On: Deploying Kafka](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_17.html#idm139824735844608)
1. [12. Coordinated Batch Processing](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_18.html#coordinated_process)
    1. [Join (or Barrier Synchronization)](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_18.html#idm139824735812976)
    1. [Reduce](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_18.html#idm139824735809440)
        1. [Hands On: Count](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_18.html#idm139824735719584)
        1. [Sum](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_18.html#idm139824735719056)
        1. [Histogram](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_18.html#idm139824735701936)
    1. [Hands On: An Image Tagging and Processing Pipeline](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_18.html#idm139824735694496)
1. [13. Conclusion: A New Beginning?](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_19.html#conclusion_chapter_)
1. [Index](https://ebookreading.net/view/book/Designing+Distributed+Systems-EB9781491983638_20.html#idm139824735622320)
