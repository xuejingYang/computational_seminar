# Introduction

## Computational Methods Seminar, Fall 2021

Pablo Winant

----

### About me

- A computational economist
- Formerly Worked in institutions (IMF, BOE)
- Now at ESCP and CREST/Polytechnique
- Research on models about:
    - Inequality (heterogeneity)
    - International Finance
    - Monetary Policy
    - Artificial Intelligence
- Using:
  - data-science (econometrics and machine learning)
  - dynamic programming
- Involved in several opensource projects (Dolo, QuantEcon, ARK)
  - special interest in Python/Julia

----

### Communication for this seminar

- github repository for the course: https://github.com/albop/computational_seminar
- enroll by:
  - creating a github account if needed
  - forking the repository
  - making a PR on participants.md
- join on [Zulip](econforge.zulipchat.org)
  - we'll communicate in the `computational_seminar` room
  - goes on between the sessions...
- my email: `pwinant@escp.eu`
- any way I can help about your PhD? Don't hesitate to get in touch

----

### Evaluation

- No exam (we're grown-ups)
- (light) Homework between the sessions
- Participate:
  - make a presentation
  - complete a small "computational" project
- Workgroup encouraged
- The ultimate goal would be to transform this seminar into a "special interest group"

---

## Computations?

----

### What do I mean by computational methods

- Researchers spend a lot of time...
  - doing computations
    - cleaning data
    - writing algorithms
      - waiting for the results...
    - scripting regressions
    - replicating work
  - writing code
    - all of the above
    - writing papers
  - using computers
    - laptop, servers
    - cloud
- ... and develop very diverse skillsets

----

### We can do better

- Be more productive
  - by using some tricks from software development
  - by looking for the right tools
- Produce better results:
  - clean
  - interactive
  - replicable
- Let's do it in the open
  - opensource software is amazing
  - there is a vibrant community ready to help

----

### Environment

We will need:
- Git
- VSCode (Visual Studio Code)
- Anaconda Python or Miniconda
- ...?
  - possibly Julia depending on interests

---

## Operating system, Linux, the Console

----

### Linux

- Unix-machines are __ubiquitous__ !
  - Linux
  - MacOS X
  - Android
  - even Windows (WSL)
- powers many instances in the cloud

----

### The console

- "The Console" aka "The Terminal"
- A shell to interact with the operating system
  - explore filesystem
  - launch progams
  - more complicated tasks (with scripts)
- Two main flavours
  - Windows: DOS -> Powershell
  - UNIX: Bash, zsh
- Again: bash/zsh are everywhere !
  - macOS, windows (git bash), matlab (!)

----

### Cloud computing

- many "servers" are in the cloud
- an instance is a "virtual computer" running an OS
  - virtualization technologies
- many instances run on one or several computers
- advantage: they can be created/destroyed easily (scalability)
- how do you compute an instance in the cloud?
  - with a graphical connection (VNC, RDesktop)
  - with a terminal
  - or a webapp
- there are instance providers (Azure, AWS, Google Cloud)...
  - ... but often you don't realize they are created

---

## Editing Environment

----

### Code

- We are using lots of languages. Here are some examples.
- Text:
  - markdown (for note taking, paper prototyping)
    - Easy to read. Simple wysisym syntax.
    - Can be converted to anything.
  - latex (scientific documents)
  - html (webpages)
- Programming languages
  - C,Fortran,Javascript,Python,Julia, ...

----

### VSCode

- light and flexible opensource code-editor
- can do anything with plugins
  - brilliant integration of git/ 
- can run in the cloud !

... try it

----

### Jupyter Lab

- Jupyter Notebooks constitute a de facto standard for literate programming
  - i.e. code mixed with texts and graphs
- Jupyter Lab is an in browser IDE

... launch a jupyter server

---

## Source Control


----

### Git

- Git is the de facto standard for source versioning
- Keep successive versions over time
- Keep alternative versions at the same time
- Collaborate with several coworkers
- Disseminate code

---

## Next Time?