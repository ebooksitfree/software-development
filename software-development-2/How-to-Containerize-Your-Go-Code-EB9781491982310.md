![Cover image for How to Containerize Your Go Code](https://imgdetail.ebookreading.net/cover/cover/software_development/EB9781491982310.jpg)

[How to Containerize Your Go Code](https://ebookreading.net/view/book/How+to+Containerize+Your+Go+Code-EB9781491982310_1.html "How to Containerize Your Go Code")
====================================================================================================================

Author : [Liz Rice](https://ebookreading.net/search/author/Liz+Rice)

Release Date : 2017/04/01

ISBN : 9781491982310

Topic : [Software Development](https://ebookreading.net/search/category/software-development)

Book Description
-----------------

 This report shows how Go programmers can build small, efficient containers for their Go code. It explains what's inside a container image and walks you through how to build and run containers for your Go projects.
What you'll learn—and how you can apply it
You'll learn how to containerize the Go code you're working on, with worked examples to show you exactly what to do. You'll see how to build a container from the scratch image, and why that's a good idea for Go code. You'll also learn how to set up port bindings so that the outside work can connect to the code running in your container, and how to pass in configuration environment variables.
This report is for you because…
You've heard of containers, but you're not sure whether they're right for your project, or how you would use them in your daily workflow.Prerequisites
We'll assume you're comfortable with the command lineWe're using Go in this lesson but many of the concepts are applicable to other languages as wellMaterials or downloads needed in advance
Install DockerInstall the Go tools        Show and hide more                
Table of Contents
-----------------

1. [How to Containerize Your Go Code](https://ebookreading.net/view/book/How+to+Containerize+Your+Go+Code-EB9781491982310_4.html#idm140204518954448)
    1. [Introduction and Motivations](https://ebookreading.net/view/book/How+to+Containerize+Your+Go+Code-EB9781491982310_4.html#idm140204518953248)
        1. [Example Code](https://ebookreading.net/view/book/How+to+Containerize+Your+Go+Code-EB9781491982310_4.html#idm140204518951312)
        1. [Using Docker](https://ebookreading.net/view/book/How+to+Containerize+Your+Go+Code-EB9781491982310_4.html#idm140204518950048)
    1. [What Is a Container?](https://ebookreading.net/view/book/How+to+Containerize+Your+Go+Code-EB9781491982310_4.html#idm140204518940864)
    1. [Bundling Go Code into a Container Image](https://ebookreading.net/view/book/How+to+Containerize+Your+Go+Code-EB9781491982310_4.html#idm140204518939264)
        1. [Building a Container Image](https://ebookreading.net/view/book/How+to+Containerize+Your+Go+Code-EB9781491982310_4.html#idm140204518913040)
        1. [A Linux Executable](https://ebookreading.net/view/book/How+to+Containerize+Your+Go+Code-EB9781491982310_4.html#idm140204518895808)
        1. [Building the Container Image](https://ebookreading.net/view/book/How+to+Containerize+Your+Go+Code-EB9781491982310_4.html#idm140204518912560)
        1. [Running the Container](https://ebookreading.net/view/book/How+to+Containerize+Your+Go+Code-EB9781491982310_4.html#idm140204518894960)
        1. [Digging Deeper: What’s Inside the Container?](https://ebookreading.net/view/book/How+to+Containerize+Your+Go+Code-EB9781491982310_4.html#idm140204518878048)
        1. [Why Build from Scratch?](https://ebookreading.net/view/book/How+to+Containerize+Your+Go+Code-EB9781491982310_4.html#idm140204518876880)
        1. [Cleaning Up](https://ebookreading.net/view/book/How+to+Containerize+Your+Go+Code-EB9781491982310_4.html#idm140204518843296)
        1. [Summary](https://ebookreading.net/view/book/How+to+Containerize+Your+Go+Code-EB9781491982310_4.html#idm140204518837936)
        1. [Image Commands](https://ebookreading.net/view/book/How+to+Containerize+Your+Go+Code-EB9781491982310_4.html#idm140204518829296)
        1. [Container commands](https://ebookreading.net/view/book/How+to+Containerize+Your+Go+Code-EB9781491982310_4.html#idm140204518821280)
    1. [Environment Variables and Port Mappings](https://ebookreading.net/view/book/How+to+Containerize+Your+Go+Code-EB9781491982310_4.html#idm140204518805632)
        1. [Building env vars into the container image](https://ebookreading.net/view/book/How+to+Containerize+Your+Go+Code-EB9781491982310_4.html#idm140204518801728)
        1. [Overriding the env var](https://ebookreading.net/view/book/How+to+Containerize+Your+Go+Code-EB9781491982310_4.html#idm140204518736192)
        1. [Specifying the Port Mapping](https://ebookreading.net/view/book/How+to+Containerize+Your+Go+Code-EB9781491982310_4.html#idm140204518732544)
        1. [Back to the Dockerfile](https://ebookreading.net/view/book/How+to+Containerize+Your+Go+Code-EB9781491982310_4.html#idm140204518720848)
        1. [Summary](https://ebookreading.net/view/book/How+to+Containerize+Your+Go+Code-EB9781491982310_4.html#idm140204518714944)
    1. [Recap](https://ebookreading.net/view/book/How+to+Containerize+Your+Go+Code-EB9781491982310_4.html#idm140204518811120)
