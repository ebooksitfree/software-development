![Cover image for Virtualizing and Tuning Large-Scale Java Platforms](https://imgdetail.ebookreading.net/cover/cover/software_development/EB9780133491425.jpg)

[Virtualizing and Tuning Large-Scale Java Platforms](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_1.html "Virtualizing and Tuning Large-Scale Java Platforms")
====================================================================================================================

Author : [Emad Benjamin](https://ebookreading.net/search/author/Emad+Benjamin)

Release Date : 2013/12/01

ISBN : 9780133491425

Topic : [Software Development](https://ebookreading.net/search/category/software-development)

Book Description
-----------------

Virtualizing and Tuning Large-Scale Java Platforms
Technical best practices and real-world tips for optimizing enterprise Java applications on VMware vSphere®
Enterprises no longer ask, “Can Java be virtualized”? Today, they ask, “Just how large can we scale virtualized Java application platforms, and just how efficiently can we tune them?” Now, the leading expert on Java virtualization answers these questions, offering detailed technical information you can apply in any production or QA/test environment.
Emad Benjamin has spent nine years virtualizing VMware’s own enterprise Java applications and working with nearly 300 leading VMware customers on projects of all types and sizes—from 100 JVMs to 10,000+, with heaps from 1GB to 360GB, and including massive big-data applications built on clustered JVMs. Reflecting all this experience, he shows you how to successfully size and tune any Java workload.
This reference and performance “cookbook” identifies high-value optimization opportunities that apply to physical environments, virtual environments, or both. You learn how to rationalize and scale existing Java infrastructure, modernize architecture for new applications, and systematically benchmark and improve every aspect of virtualized Java performance. Throughout, Benjamin offers real performance studies, specific advice, and “from-the-trenches” insights into monitoring and troubleshooting.
Coverage includes
--Performance issues associated with large-scale Java platforms, including consolidation, elasticity, and flexibility
--Technical considerations arising from theoretical and practical limits of Java platforms
--Building horizontal in-memory databases with VMware vFabric SQLFire to improve scalability and response times
--Tuning large-scale Java using throughput/parallel GC and Concurrent Mark and Sweep (CMS) techniques
--Designing and sizing a new virtualized Java environment
--Designing and sizing new large-scale Java platforms when migrating from physical to virtualized deployments
--Designing and sizing large-scale Java platforms for latency-sensitive in-memory databases
--Real-world performance studies: SQLFire vs. RDBMS, Spring-based Java web apps, vFabric SpringTrader, application tiers, data tiers, and more
--Performance differences between ESXi3, 4.1, and 5
--Best-practice considerations for each type of workload: architecture, performance, design, sizing, and high availability
--Identifying bottlenecks in the load balancer, web server, Java application server, or DB Server tiers
--Advanced vSphere Java performance troubleshooting with esxtop
--Performance FAQs: answers to specific questions enterprise customers have asked
              
Table of Contents
-----------------

1. [Title Page](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_2.html)
1. [Copyright Page](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_3.html)
1. [Dedication](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_4.html)
1. [Contents](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_5.html)
1. [Preface](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_7.html)
    1. [Motivation for Writing This Book](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_7.html#pref02lev1sec1)
    1. [Prerequisites](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_7.html#pref02lev1sec2)
    1. [What do you really need to know first!?](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_7.html#pref02lev1sec3)
    1. [Is 4GB Java Heap the new 1GB? Why?](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_7.html#pref02lev1sec4)
    1. [Why should I bother with Virtualization – what are key benefits?](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_7.html#pref02lev1sec5)
    1. [Why should I bother with Virtualization – what are key benefits?](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_7.html#pref02lev1sec6)
    1. [Who Should Read This Book](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_7.html#pref02lev1sec7)
    1. [How to Use This Book](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_7.html#pref02lev1sec8)
1. [About the Author](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_8.html)
1. [Acknowledgments](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_9.html)
1. [We Want to Hear from You!](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_10.html)
1. [Reader Services](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_11.html)
1. [Chapter 1. Introduction to Large-Scale Java Platforms](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_12.html)
    1. [Large-Scale Java Platform Categories](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_12.html#ch01lev1sec1)
    1. [Large-Scale Java Platform Trends and Requirements](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_12.html#ch01lev1sec2)
    1. [Large-Scale Java Platform Technical Considerations](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_12.html#ch01lev1sec3)
    1. [Summary](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_12.html#ch01lev1sec4)
1. [Chapter 2. Design and Sizing Large Scale Java Platforms](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_13.html)
    1. [Designing and Sizing a New Environment for a Virtualized Large Scale Java Platform](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_13.html#ch02lev1sec1)
    1. [Sizing vFabric SQLFire Java Platforms - Category 2 Workloads](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_13.html#ch02lev1sec2)
    1. [Chapter Summary](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_13.html#ch02lev1sec3)
1. [Chapter 3. Tuning Large-Scale Java Platforms](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_14.html)
    1. [GC Tuning Recipe](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_14.html#ch03lev1sec1)
    1. [Chapter Summary](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_14.html#ch03lev1sec2)
1. [Chapter 4. Modern Scalable Data Platforms](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_15.html)
    1. [SQLFire Topologies](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_15.html#ch04lev1sec1)
    1. [SQLFire Features](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_15.html#ch04lev1sec2)
    1. [Active-Active Architectures and Modern Data Platforms](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_15.html#ch04lev1sec3)
    1. [Chapter Summary](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_15.html#ch04lev1sec4)
1. [Chapter 5. Performance Studies](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_16.html)
    1. [SQLFire versus RDBMS Performance Study](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_16.html#ch05lev1sec1)
    1. [The Olio Workload on tcServer and vSphere Performance Study](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_16.html#ch05lev1sec2)
    1. [SpringTrader Performance Study](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_16.html#ch05lev1sec3)
    1. [Performance Differences between ESXi3, 4.1 and 5](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_16.html#ch05lev1sec4)
    1. [vSphere 5 Performance Enhancements](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_16.html#ch05lev1sec5)
    1. [Chapter Summary](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_16.html#ch05lev1sec6)
1. [Chapter 6. Best Practices](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_17.html)
    1. [Enterprise Java Applications on vSphere Best Practices (Category-1)](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_17.html#ch06lev1sec1)
    1. [SQLFire Best Practices, and SQLFire on vSphere Best Practices (Category 2 JVM workload best practices)](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_17.html#ch06lev1sec2)
    1. [Category 3 Workloads Best Practices](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_17.html#ch06lev1sec3)
    1. [IBM JVM and Oracle jRockit JVMs](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_17.html#ch06lev1sec4)
    1. [Chapter Summary](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_17.html#ch06lev1sec5)
1. [Chapter 7. Monitoring and Troubleshooting Primer](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_18.html)
    1. [Open a Support-request Ticket](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_18.html#ch07lev1sec1)
    1. [Collecting Metrics from vCenter](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_18.html#ch07lev1sec2)
    1. [Troubleshooting Techniques for vSphere with esxtop](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_18.html#ch07lev1sec3)
    1. [Java Troubleshooting Primer](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_18.html#ch07lev1sec4)
    1. [Chapter Summary](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_18.html#ch07lev1sec5)
1. [Appendix. FAQs](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_19.html)
    1. [“We have virtualized our WebSphere environment and we are now considering open source applications server alternatives, what options do we have in this space”](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_19.html#app01lev1sec1)
    1. [“Are there any customer testimonies, from customers who have virtualized and tuned large Scale Java Platforms that follow the recommendations you provided?”](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_19.html#app01lev1sec2)
    1. [“I’m afraid that performance will suffer if I virtualize the enterprise Java application.”](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_19.html#app01lev1sec3)
    1. [“I looked at virtualization, and in my environment I can only get a three-to-one server-consolidation ratio, so I don’t think it’s worth it.”](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_19.html#app01lev1sec4)
    1. [“Where can I get support?”](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_19.html#app01lev1sec5)
    1. [“Why would I choose to virtualize enterprise Java applications?”](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_19.html#app01lev1sec6)
    1. [“Are there any performance issues?”](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_19.html#app01lev1sec7)
    1. [“We have an environment of 8000 JVMs all made of Weblogic application instances, how could we possibly virtualize this?”](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_19.html#app01lev1sec8)
    1. [“What Technology Tools and Runtime Services are contained in vFabric?”](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_19.html#app01lev1sec9)
    1. [“Do I have to code Java differently when running on vSphere?”](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_19.html#app01lev1sec10)
    1. [“Are there any Java best practices for vSphere?”](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_19.html#app01lev1sec11)
    1. [“How would you achieve vertical scalability of Java applications running on vSphere?”](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_19.html#app01lev1sec12)
    1. [“How would you achieve horizontal scalability of Java applications running on vSphere?”](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_19.html#app01lev1sec13)
    1. [“How would you guard against server hardware failure when running Java applications on vSphere?”](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_19.html#app01lev1sec14)
    1. [“How would you achieve high availability of Java applications running on vSphere?”](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_19.html#app01lev1sec15)
    1. [“How many JVMs can I stack on a single VM and how many vCPUs should the VM use?”](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_19.html#app01lev1sec16)
    1. [“Which application servers have been proven on vSphere in production?”](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_19.html#app01lev1sec17)
    1. [“What kind of testing has been done to validate running Weblogic on vSphere?”](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_19.html#app01lev1sec18)
    1. [“Which Web servers have been proven on vSphere in production?”](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_19.html#app01lev1sec19)
    1. [“Java applications platforms are multitier, which tiers make sense to virtualize first?”](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_19.html#app01lev1sec20)
    1. [“How does vSphere help with business continuity for enterprise Java applications?”](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_19.html#app01lev1sec21)
    1. [“If I have a problem with Oracle WebLogic Server running on VMware virtual infrastructure, who should I call for support?”](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_19.html#app01lev1sec22)
    1. [“If I have a problem with IBM Websphere Server running on VMware vSphere, who should I call for support?”](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_19.html#app01lev1sec23)
    1. [“What about licensing?”](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_19.html#app01lev1sec24)
    1. [“Are there any customer references?”](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_19.html#app01lev1sec25)
    1. [“What decisions must be made due to virtualization?”](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_19.html#app01lev1sec26)
    1. [“I have conducted extensive GC sizing and tuning for our current enterprise Java application running on physical. Do I have to adjust anything related to sizing when moving this Java application to a ](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_19.html#app01lev1sec27)
    1. [“How many and what size of virtual machines will I need?”](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_19.html#app01lev1sec28)
    1. [“What is the correct number of JVMs per virtual machine?”](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_19.html#app01lev1sec29)
    1. [“We would like to use the full logical CPU capacity of a host and take full advantage of HT.”](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_19.html#app01lev1sec30)
    1. [“We have a monitoring system that is a single JVM heap of 360GB large could we tune this?”](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_19.html#app01lev1sec31)
    1. [“We are in the DevOps team and we get challenged about our JVM knowledge by the developers, can you help us with some preliminary information about the JVM internals and how it needs to be sized?”](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_19.html#app01lev1sec32)
1. [Glossary](https://ebookreading.net/view/book/Virtualizing+and+Tuning+Large-Scale+Java+Platforms-EB9780133491425_20.html)
