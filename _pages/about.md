---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I‘m a Master of Engineering student in Electrical & Computer Engineering (ECE) at Duke University currently. I received my Bachelor of Engineering degree in Computer Science from Wuhan University of Technology in June 2023. I have practical experience in software development and test engineering from several internships, including software development at TikTok(Bytedance) and test engineering at Huawei Technology. At Duke, I currently focus on studying the field in Edge Computing and want to go deeper in this field!

Education
======
* M.Eng. in Electrical & Computer Engineering, Duke University, 2025(expected)
* B.Eng. in Computer Science, Wuhan University of Technology, 2023
  * 93/100, rank: 3%, National Merit

Work experience
======
* Summer 2022: Software Engineer Intern
  * Bytedance
  * Department: Lark Business Application
  * Duties included: Backend Development
    * Assisted the team in developing the leave management system for over 100k employees within the company.
    * Developed microservices with Golang RPC framework and database framework Gorm, and secured all data with transactions.
    * Deployed codes into Docker containers and managed them centrally through Kubernetes.
    * Conducted code functional and performance testing with Golang Test framework on about 2k lines code with over 85% coverage.
    * Improved overall code execution speed through caching, thread pooling and asynchronous programming.
    * Collaborated on multi-person programming by Git and GitLab.

* Fall 2021 & Winter 2022: Test Engineer Intern
  * Huawei Technology
  * Department: Kunpeng Audio Chip
  * Duties included: Build & maintain Test framework
    * Assisted developers in optimizing internal function libraries for mobile phone chips by building testing environment with CMake and C++ testing framework Google Test (GTest).
    * Conducted functional and performance testing on hundreds of lines code in Linux environment with C++ and Linux Shell.
    * Implemented automated testing with over 500k data by Python
  
Skills
======
* **Programming Languages**: Golang, Java, C/C++, Python, Linux Shell, JavaScript, HTML/CSS, MATLAB
* **Frameworks**: Gin, gRPC, Spring, Vue.js, React.js, Gorm, Mybatis, Hibernate
* **Databases**: MySQL, MongoDB, Redis, ElasticSearch, SQLite
* **Tools**: Git, Docker, Kubernetes, AWS, Linux, RabbitMQ, Nginx
* **Courses**: Data Structures, Computer Networks, Computer Architecture, Operating Systems, Distributed Architecture, Cloud Computing

Projects
======

* Online Medical Consultation Platform (Graduate Design) | Mar 2023 – May 2023
  * Built a web consultation platform by Vue.js, Gin, and Gorm frameworks, with MySQL as databases and Redis for caching.
  * Optimized search functions with ElasticSearch to increase the speed of search by about 30%.
  * Developed a web instant messaging platform with WebSocket and used MongoDB to store conversation logs.
  * Improved system concurrency using Goroutines and RabbitMQ, and used Nginx for load balancing.

* AES Encoder & Decoder | Sep 2022 – Oct 2022
  * Designed the module architecture for the AES program, encompassing input and output specifications, interconnections between modules, etc.
  * Developed a Verilog program for 128-bit AES Encoder and Decoder, and subsequently integrate it into an FPGA platform for rigorous functional validation.
  * Conducted comprehensive testing of the code using a Verilog testbench at a large scale, with the primary objective of verifying the code’s functional integrity.

* NFT Analysis System (Zhejiang Univ Summer Camp Program) | Jun 2022 – July 2022
  * Crawled thousands of NFT data from websites like Opensea, Axie Marketplace using the Python framework PySpider. Preprocessed the data and stored it in MySQL.
  * Developed the system using Spring Boot for the backend, React.js + Bootstrap for the frontend, and MySQL as the database.
  * Implemented risk and security detection for various types of NFTs using AliCloud’s content detection API.

* Mahjong Game | C++ Software Developer Mar 2022 – May 2022
  * Developed the game GUI with C++ MFC framework, including the start, login, game interface, etc.
  * Used C++ object-oriented programming method to implement all functions of the game, and stored user’s game data with SQLite and Cloud MySQL.
  * Implemented the multiplayer mode and real-time chat room function with C++ Socket.

* Blog Sharing Website |  Sep 2021 – Oct 2021
  * Developed the website using Vue.js, SpringBoot, and MyBatis frameworks, with Cloud MySQL.
  * Implemented permission management with JWT and Spring Security, and used Redis to store JWT tokens.
  * Implemented quick search for 2 million blogs based on ElasticSearch.
  * Improved system concurrency and lower the latency by thread pooling and RabbitMQ.
  * Splitted the whole big project into several sub-projects and unified them through Maven.




<!-- This is the front page of a website that is powered by the [academicpages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this repository](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! An older version of this template powers my own personal website at [stuartgeiger.com](http://stuartgeiger.com), which uses [this Github repository](https://github.com/staeiou/staeiou.github.io).

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->
