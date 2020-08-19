---
layout: page
permalink: /projects/
---

# Capstone Project List


Please file your top THREE choices as an issue with a title beginning with PROJECT (will go over in class) by Wednesday (26 August) morning at 11:59 AM (i.e., right before noon). Please list them in the order that you prefer them.  You will be informed as to your project BY the next Capstone class on Friday (28 August). YOU MUST FILE AN ISSUE IN ORDER TO BE PLACED ON A PROJECT AND THUS GET CREDIT FOR THE COURSE!  YOU WILL NOT BE PLACED ON A PROJECT IF YOU DO NOT FILE AN ISSUE!

REMEMBER TO ADD "PROJECT" TO THE BEGINNING OF YOUR ISSUE TITLE!

Along with your selections, please include any qualifications or specific reasons for interest that you have for those specific projects. Remember that you are "interviewing" for the project against others, especially if you have selected popular projects. Students who respond early also show enthusiasm for the projects, which goes a long way to showing that they actually want to do them.

I will attempt to place you in one of your top three choices. Usually, every student gets into one of their top three (and a majority into their #1 choice), although I cannot make any guarantees.

Note: Some of you may be working on private projects. Please file an issue on this repository (as above) but note that you have already been assigned to a project. List the project and the name of the POC (e.g. faculty member or supervisor). If we have not discussed you being placed on a private project, do not put yourself on one.

## Industry Capstone Projects

### NetApp - Two projects

Project 1

TBD

Project 2

TBD
**Note: NDA and/or IP agreement will need to be signed for this project.**


### INTALERE - ONLY 1 OF THE FOLLOWING

**Note: NDA and/or IP agreement will need to be signed for this project.**

### CGI - CGI Client Onboarding Portal

**Note: NDA and/or IP agreement will need to be signed for this project.**


## CS Faculty Projects


### RISC-V web based simulator for CS447

For DECADES CS 447 was taught using MIPS assembly language. However, MIPS processors are not that common anymore (RIP PS and PS2).
On the other hand, the RISC-V architecture (open-source) is gaining some momentum, and you can even buy some boards to have fun with it.

We are still using MARS (which we all hate ;), but we want to push the development of an alternative that uses RISC-V. wilkie developed a web-based alternative, but it's still not ready for primetime: https://gitlab.com/wilkie/rawrs
This tool is called RAWRS (RISC-V Assembler and Workable, Rewritable System) - it's an acronym it can mean whatever we want! - and it's a web-based tools (bye bye Java).

The objective for this project is to develop this tool further to a point where it can be used for CS 447.

The tool is written in (modern) Javascript where we predict most of the development will be focused. But you will also have the opportunity to stretch your assembly muscles. As the RISC-V simulator is backed by a RISC-V kernel :D

* Team Size: 3-4 students
* POC: David Wilkinson (wilkie) and Luis Oliveira


### Learning-based Resource Management on Heterogeneous CPU/Memory Systems

Computer systems are increasingly being used to support a wide variety of applications such as web browsers, social networks, email clients, audio and video players. Heterogeneous processors (i.e., different types of cores in a single CPU) and hybrid memory/storage systems (i.e., different types of memory accessible by the CPU) have been recently adopted by hardware vendors to balance performance and energy efficiency on computing devices. Still, the main research challenge for runtime systems software is to automatically allocate the execution tasks and associated data to the heterogeneous resources, while meeting user-facing performance targets with minimal resource consumption. Our research project will experimentally investigate and evaluate ideas to solve that problem, leveraging OS-level techniques, including profiling and tracing, and machine learning models that can help us characterize the application behavior from hardware-assisted performance monitoring counters. Specifically, students will learn how to use perf (a tool to monitor the performance of applications), deploy and run benchmarks to collect data, organize and clean the data, and experiment with different machine learning algorithms to extract policies for automatic resource allocation.

* Areas of Interest: Operating Systems, Computer Architecture
* Helpful Skills: Knowledge of Linux, C Programming, Python, Machine Learning
* Group Size: 2-3 students
* POC: Vinicius Petrucci (vpetrucci@pitt.edu) & Daniel Mossé (mosse@pitt.edu)


### Optimizing Web Browsing Energy Efficiency

While the Web has been around for decades and is available on practically every device from mobile phones to refrigerators, web browsing is a complex task that is still actively being researched. An ever-growing amount of mobile devices trying to stretch their battery life, in conjunction with increasingly complex web pages, create a delicate balancing act between energy efficiency and performance. Existing OS-based power management techniques designed to tackle this issue rely on generic system-level metrics that are unable to anticipate the complex behavior of a web browser, which can lead to energy inefficiency or poor user experience during web browsing activities.

In this project, we propose a new power management approach that leverages application-level information by interpositioning important functions corresponding to major phases in the web browser (Chromium in our study). This allows us to monitor the behavior of the application at a finer granularity (compared to OS schemes). Based on runtime observations, we can modify the web browser's behavior to evaluate the effect of different hardware mappings (CPU type and speed) on performance/energy usage. Ultimately, we seek to design a better method of mapping application phases to appropriate hardware usage patterns. We have already built the interpositioning and monitoring platform and now would like to design and implement our power management mechanism based on this infrastructure. This is an ongoing project initiated by Will Sumner and new students will be able to leverage his experimental infrastructure
(https://github.com/WilliamASumner/Chromium-Experiments).

* Areas of Interest: Operating Systems, Computer Architecture
* Helpful Skills: Knowledge of Linux, System Programming (C/C++), Python, Machine Learning
* Group Size: 2-3 students
* POC: Vinicius Petrucci (vpetrucci@pitt.edu)

### Experimenting with Disaggregated OS

Disaggregated hardware resources have recently been proposed as a way to allow flexible and efficient allocation of server capacity to large-scale applications. In this project, we would like to experiment with a research operating system for hardware resource disaggregation, called LegoOS (https://github.com/WukLab/LegoOS), released by researchers from Purdue University. LegoOS breaks the traditional monolithic server design into a network of independent hardware components (CPU, memory, disk, etc.). It splits the major OS functions into loosely-coupled monitors running on specialized hardware components, while fast network messaging is used to allow those components to communicate.

Experimentally we would like to understand how data-intensive applications spanning multiple machines could benefit, for instance, from the separation of the CPU from the memory system (DRAM disaggregation). For conducting our experiments, we will be using the CloudLab platform (https://www.cloudlab.us/).

* Areas of Interest: Operating Systems, Computer Architecture
* Helpful Skills: Knowledge of Linux Kernel, C Programming
* Group Size: 2 students
* POC: Vinicius Petrucci (vpetrucci@pitt.edu)




### A website for handing-in programming assignments


Tim Hoffman's hand-in system is behind the VPN. Due to so many students having trouble getting the VPN to work – he needs a workaround.  There are around 280 students and doing this by email by hand is very time consuming.

Perhaps a  structured Dropbox with course assignment id nested folders that can be script harvested and auto copied to a directory on AFS.

This is pretty vague and wide open since I have no ideas on a specific approach to get around the VPN.

If someone has a great idea I’d love to give them a shot at it.

* Team Size: 2-3 students
* POC: Tim Hoffman


### Stephen Lee - two projects

1.	Project Background (exploratory):  The practical applications of Blockchains have evolved beyond cryptocurrency. Blockchain applications show promise in disrupting many sectors, including supply chain, energy, finance, etc. However, blockchain technology needs to overcome its scalability issue to enable widespread adoption. Today most blockchain technology support throughput in tens of thousands. This project will explore off-chain computation to improve the scalability of blockchains. In particular, we will integrate an existing permissioned Blockchain (Hyperledger Sawtooth) with a serverless computing infrastructure (ApachOpen Whisk) and study the impact of elasticity on performance.

Students are required to have strong programming skills and eager to learn new languages, including Go, Scala, etc.

* Number of students: 2-3

2.	Project Background (development): LIDAR sensors are becoming increasingly popular to capture semantically rich information. Google Earth is one such example, where lidar data is fused with a satellite image to present an interactive and immersive experience. The visualization tool also serves as a framework for other projects such as Google Sunroof Project and Maps. This project will involve developing a visualization tool for LiDAR data collected using aerial drones. We will use publicly available LIDAR data and satellite images to visualize building rooftops.

Students are required to have familiarity with HTML, Javascript, and python. Knowledge of any existing HTML/Javascript framework is a plus.

* Number of students: 2-3


### Polkadot - Visualization for bitcoin
Polkadot (https://polkadot.network/) is a heterogenous multi-chain; that is, it provides the ability for multiple different blockchains ("parachains") to share consensus and communicate securely with each other through a central relay chain.  Currently, while there are visualization tools for the relay chain (such as https://polkadot.js.org/apps/#/explorer/forks), and tools available for individual parachains, there are no tools that allow a user to have a cohesive view of the entire system.  The goal of this project is to produce a web application which will display the current status of the relay chain and various parachains in an easy-to-read format, including the last finalized block and current block candidates of the relay chain, status of various parachains, and status of the different parachains' message queues.

Ideally, this will start as a text-based system to ensure accurate collection of data, and then visualization features will be added to it.

This project will be especially interesting for people interested in blockchain technology or information visualization.

Technologies: This will mostly be done in JavaScript and node.js, along with display libraries of the group's choice and the Polkadot API.  However, it may require some code spelunking in the Polkadot Rust codebase.  We have team members that can assist you with all of these.

Team Size: 3-4 students
POC: Bill Laboon, Web3 Foundation Technical Education Lead (and Lecturer currently on leave from the University of Pittsburgh) - bill@web3.foundation


# Other university projects

## Green Guide Recycling Game



Pitt Sustainability want to make a game to teach people to recycle, compost, and donate on campus.

The Game Dynamic is expected to go like this: User should be asked to sort objects to the correct end-of-life option. When user gets it right they gain points, when they get it wrong a message appears with the correct answer. User can replay game as many times as they want. It may be fun to have a high score board on the game so people can compete to see who gets the most right answers in a set timeframe.

Below are just a few examples of possible scenarios that can be presented.
Scenario Examples
|Item|End-of-Life|
|-|-|
|Container strawberries come in from the store| Trash
|Torn pair of jeans|Textile recycling or thriftsburgh to be repaired|
|Shirt that no longer fits|Thriftsburgh|
|Dead batteries|On-campus battery recycling|
|Pizza box with grease|Trash|
|Cardboard box|Recycling|
|Single use plastic bag|Trash|
|Orange peel|Compost|
|Worn out sneakers|Textile recycling|
|Unopened Ramen you no longer want|Pitt Pantry|
|Almond milk cardboard container|Trash|
|Empty Ink Cartridge|Campus Mail to be recycled|
|Starbucks to go cup|Trash|


The plan is to embedded-in/link to the Student Green Guide and Employee Green Guide pages on sustainable.pitt.edu.

Here are some examples of similar ideas:
- UBC (Canada) – [yuluo.psych.ubc.ca/studies/Sorting_fun](yuluo.psych.ubc.ca/studies/Sorting_fun)
- Penn State Recycling Game (a but little slow): [https://recyclinggame.la.psu.edu/](https://recyclinggame.la.psu.edu/)
- Monroe County : [https://www2.monroecounty.gov/files/DES/education/SortItOut/index.html](https://www2.monroecounty.gov/files/DES/education/SortItOut/index.html)
- Virtual waste sorting game from UMBC: [quiz.tryinteract.com/#/5e999a59e1b7600014a65aec](quiz.tryinteract.com/#/5e999a59e1b7600014a65aec)
  - All of our answers aren’t the same on-campus, but in general the answers are reflective of Pitt and Pittsburgh’s waste diversion reality.

Team Size: 3-4 students
* POC: Aurora Sharrard, Director of Sustainability, University of Pittsburgh
* POC: Samantha Ford. Sustainability Projects Coordinator, University of Pittsburgh


### Decision support Police
### NLP police
