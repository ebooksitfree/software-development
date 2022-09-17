![Cover image for Testing iOS Apps with HadoopUnit](https://imgdetail.ebookreading.net/cover/cover/software_development/EB9781627056519.jpg)

[Testing iOS Apps with HadoopUnit](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_1.html "Testing iOS Apps with HadoopUnit")
====================================================================================================================

Author : [Krissada Dechokul](https://ebookreading.net/search/author/Krissada+Dechokul),[ Scott Tilley](https://ebookreading.net/search/author/+Scott+Tilley)

Release Date : 2014/11/01

ISBN : 9781627056519

Topic : [Software Development](https://ebookreading.net/search/category/software-development)

Book Description
-----------------

Smartphone users have come to expect high-quality apps. This has increased the importance of software testing in mobile software development. Unfortunately, testing apps&#8212;particularly the GUI&#8212;can be very time-consuming. Exercising every user interface element and verifying transitions between different views of the app under test quickly becomes problematic. For example, execution of iOS GUI test suites using Apple&#8217;s UI Automation framework can take an hour or more if the app&#8217;s interface is complicated. The longer it takes to run a test, the less frequently the test can be run, which in turn reduces software quality.  This book describes how to accelerate the testing process for iOS apps using HadoopUnit, a distributed test execution environment that leverages the parallelism inherent in the Hadoop platform. HadoopUnit was previously used to run unit and system tests in the cloud. It has been modified to perform GUI testing of iOS apps on a small-scale cluster&#8212;a modest computing infrastructure available to almost every developer.  Experimental results have shown that distributed test execution with HadoopUnit can significantly outperform the test execution on a single machine, even if the size of the cluster used for the execution is as small as two nodes. This means that the approach described in this book could be adopted without a huge investment in IT resources. HadoopUnit is a cost-effective solution for reducing lengthy test execution times of system-level GUI testing of iOS apps.              
Table of Contents
-----------------

1. [Cover](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_1.html)
1. [Copyright](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_4.html)
1. [Title](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_5.html)
1. [Contents](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_7.html)
1. [Figures](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_8.html)
1. [Tables](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_9.html)
1. [Foreword](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_10.html)
1. [Preface](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_11.html)
1. [Acknowledgments](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_12.html)
1. [Dedication](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_13.html)
1. [1. Introduction](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_14.html)
    1. [1.1. GUI Testing of iOS Apps](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_14.html#sec1.1)
    1. [1.2. Rapid Testing with HadoopUnit](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_14.html#sec1.2)
    1. [1.3. Related Work](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_14.html#sec1.3)
        1. [1.3.1. GUI Testing Tools](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_14.html#sec1.3.1)
        1. [1.3.2. Distributed Testing Platforms](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_14.html#sec1.3.2)
1. [2. Background](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_15.html)
    1. [2.1. Software Testing](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_15.html#sec2.1)
        1. [2.1.1. Regression Testing](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_15.html#sec2.1.1)
        1. [2.1.2. GUI Testing](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_15.html#sec2.1.2)
    1. [2.2. UI Automation](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_15.html#sec2.2)
        1. [2.2.1. UI Automation Script](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_15.html#sec2.2.1)
        1. [2.2.2. Command-Line Workflow with UI Automation](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_15.html#sec2.2.2)
        1. [2.2.3. Rake](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_15.html#sec2.2.3)
        1. [2.2.4. Virtualization](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_15.html#sec2.2.4)
    1. [2.3. Hadoop and HadoopUnit](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_15.html#sec2.3)
        1. [2.3.1. Hadoop](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_15.html#sec2.3.1)
        1. [2.3.2. HadoopUnit](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_15.html#sec2.3.2)
1. [3. Using UI Automation with HadoopUnit](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_16.html)
    1. [3.1. UI Automation Test Suites](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_16.html#sec3.1)
        1. [3.1.1. Test Case Design](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_16.html#sec3.1.1)
        1. [3.1.2. Test Case Analysis](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_16.html#sec3.1.2)
    1. [3.2. HadoopUnit Customization](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_16.html#sec3.2)
        1. [3.2.1. Operational Environment](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_16.html#sec3.2.1)
        1. [3.2.2. Test Results](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_16.html#sec3.2.2)
        1. [3.2.3. Revised Architecture](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_16.html#sec3.2.3)
    1. [3.3. Using HadoopUnit](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_16.html#sec3.3)
        1. [3.3.1. Test Case List](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_16.html#sec3.3.1)
        1. [3.3.2. Rake](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_16.html#sec3.3.2)
        1. [3.3.3. Test Execution](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_16.html#sec3.3.3)
1. [4. Rapid GUI Testing of iOS Apps](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_17.html)
    1. [4.1. Experiments](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_17.html#sec4.1)
        1. [4.1.1. Experiment I](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_17.html#sec4.1.1)
        1. [4.1.2. Experiment II](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_17.html#sec4.1.2)
        1. [4.1.3. Experiment III](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_17.html#sec4.1.3)
    1. [4.2. Discussion of Results](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_17.html#sec4.2)
    1. [4.3. Threats to Validity](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_17.html#sec4.3)
        1. [4.3.1. Test Suites](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_17.html#sec4.3.1)
        1. [4.3.2. Hadoop Optimization](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_17.html#sec4.3.2)
        1. [4.3.3. Network Issues](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_17.html#sec4.3.3)
1. [5. Summary](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_18.html)
    1. [5.1. Summary of Results](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_18.html#sec5.1)
        1. [5.1.1. Research Objectives](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_18.html#sec5.1.1)
        1. [5.1.2. Research Contributions](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_18.html#sec5.1.2)
    1. [5.2. Future Work](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_18.html#sec5.2)
    1. [5.3. Concluding Remarks](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_18.html#sec5.3)
1. [Appendix A: Setting up a HadoopUnit Cluster on Mac OS X](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_19.html)
1. [Appendix B: HadoopUnit Source Code for iOS GUI Testing](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_20.html)
1. [References](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_21.html)
1. [About the Authors](https://ebookreading.net/view/book/Testing+iOS+Apps+with+HadoopUnit-EB9781627056519_22.html)
