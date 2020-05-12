# Course syllabus

## Session 1: Efficient Workflows for Data- and Computation-intensive Projects [(Hannes Datta)](about.md#hannes-datta)

### Learning Objectives

- Review the key building blocks of efficient workflows, following
  [tilburgsciencehub.com](http://tilburgsciencehub.com/workflow)
    - e.g., understand the concept of project pipelines and project components,
    and how they apply to your own research project
    - e.g., learn about the benefits of automating your project's pipeline

- Replicate a reproducible workflow for enriching JSON data from Twitter
  with text mining metrics, and producing an RMarkdown document with results.

- Discuss and implement advanced workflows to manage complex computational projects
    - Adhere to a grow-as-you go directory structure to keep source code organized
    - Learn how to automate your project infrastructure using `make`
    - Integrate cloud storage from AWS S3, Google Drive, or Dropbox
    - Version your project's source code and manage Issues/To do's using Git/GitHub
    - Collaborate on open source projects

- Formulate steps to professionalize data and code management in your own research projects

### Preparation

To be able to follow the class, you need to prepare the following things:

- Setup your computer, following [our installation guide](http://tilburgsciencehub.com/setup). Please install:
    - [Python 3.x via Anaconda](http://tilburgsciencehub.com/setup/python)
    - [R >= 3.x and RStudio](http://tilburgsciencehub.com/setup/r)
    - [GNU Make](http://tilburgsciencehub.com/setup/make)

    - It is important that these software tools are callable from the command line/terminal.
        - Mac users: try whether running `python`, `R` and `make` from the terminal works.
        - Windows users: please configure your environment variables so that you can call `python`, `R` and `make` from *Anaconda Prompt*.

- Familiarize yourself with [http://tilburgsciencehub.com](). In particular,
    - browse our section where we document the basics of [efficient workflow design](http://tilburgsciencehub.com/workflow)
    - explore the various other sections of the website

- Follow our [tutorial to implement a basic automated workflow](http://tilburgsciencehub.com/tutorial) to enrich JSON data with text mining metrics.
    - Please allow sufficient time to follow this tutorial (approx. 4 hours should suffice, if you have the software setup right).

-	Be prepared to show the directory of a recent project you’re working on – be able to explain that structure (you don’t need to revise the structure before class!)
