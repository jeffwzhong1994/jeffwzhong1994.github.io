---
layout: page
title: Projects
subtitle: Fun things that I worked on
---

### Genomics Annotation Services

> A fully operational software-as-a-service for genomics analysis served on AWS. 


The software consists of multiple components, including a web app (an interface for users to upload files and check job status), an annotation service (a process by which a sequenced genome sample is analyzed to identify the location of genes and all of the coding regions in a genome, and determine what those genes do), and several utility programs such as notifying users via email when jobs are done, archiving files for free users from s3 to glacier, and restoring files for free users once they subscribe to become premium users. Utilized load balancers and auto-scalers for scaling purposes and performed load testing using Locust and simple scripts. 


### MPCS Shell

> A Unix-like shell crafted in C


The key features of the Unix-like shell include command parsing, job control for foreground and background processes, custom signal handling for process management, and implementation of built-in commands such as job listing, command history, and process manipulation (e.g., `bg`, `fg`, `kill` etc.). The shell supports dynamic command line argument processing, interactive and batch mode executions, and leverage C programming concepts like pointer manipulation, dynamic memory allocation, and modular design for extendibility.


### Raft REST Message Queue

> A distributed message queue system using Raft concensus algorithm to ensure consistency across multiple nodes.

The Raft REST Message Queue (RRMQ) system faciliates messages addition and consumption through a REST API, supporting PUT/GET operations for appending and retrieving messages from a topic's queue, adhering to FIFO protocol. The project implementation covered single-node message queue functionality, leader election with fault recovery, log replication among nodes, and comprehensive testing to verify the fault tolerance mechanisms.


### Password Cracking system

> A distributed password cracking system using Flask


The Distributed password cracking system employs Flask to create RESTful services, faciliating the distribution of password serach space across multiple instances for efficient parallel processing. The system's architecture supports JSON-based communication, enabling clients to distribute cracking tasks among services that attempt to brute force crack hashed passwords. Fault tolerance mechanism was implemented to ensure the system's resilience against individual services failures, and in-memory caching mechnism was implemented within the web service to enhance performance.


### You've Got Issues!

> An iOS application that displays open/closed GitHub issues of repository using Swift UIKit and Github's REST API


An innovative iOS application that utilizes Swift's UIKit and GitHub's REST API to display open and closed issues from GitHub repositories. It incorporates a UITabBarController for issue categorization, customized UITableViewCell subclasses for issue representation, and an IssueDetailViewController for comprehensive issue details, including Safari redirects. Employing async/await for data fetching and Codable structs for JSON parsing, the app ensures data is efficiently handled and displayed. The application is further enhanced with pull-to-refresh functionality and UI improvements for a seamless user experience.


### My Kind of Town

> A map-based iOS application that accentuates landmarks across Chicago using MapKit


The app features a full-screen map devoid of Apple's default points of interest, showcasing Apple's default points of interest in favor of custom annotations and provides an immersive interface complete with a transparent HUD for detailed landmark information. Designed with adaptability in mind, the app supports various device orientations and sizes using Storyboards for UI layout, ensuring a versatile experience across all iPhone models.


### Linguistic Forensics: A Markov Model Approach to Speaker Recognition

> A Markov model-based text analysis system alongside a custom hash tables


The text analysis system leverages Markov models alongside a bespoke hash table implementation. It focused on utilizing Markov models for statistical analysis of texts, capturing not only the frequencies but also intricate contextual relationships between sequences. Additionally, the project entailed the creation of an efficient hash table utilizing separate chaining for data management. This component was designed to adeptly manage collision resolutions and enable the tailored design of data structures, thereby enhancing the overall efficiency and adaptability of the system.