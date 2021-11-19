# Session 3

## Computational Methods Seminar, Fall 2021

Pablo Winant

----


### Last week


<div class="container">


<div class="col">

- Git
  - store modifications
  - upload them
  - synchronize them

</div>

<div class="col">

- Project description

- Introduction to Python
  - setup VSCode
  - super basics (basic types ***)


</div>

</div>

</div>

---

### This week


<div class="container">


<div class="col">

- Super Quick Recap.

- Git
  - list branches / create a branch
  - checkout a branch
  - merge a branch
  - create a PR

- Introduction to Python (2)
  - super basics (containers)
  - numeric python
  - plot data
  - pandas dataframe

</div>

<div class="col">

- Challenge for *next* time
  - choose one graph from [ourworldindata](https://ourworldindata.org/)
  - replicate it as well as possible
  - requirement: all the code should be in your github repo
  - bonus points:
    - make result available online
      - on github pages (for simple browsing)
      - full replicability on mybinder.org
    - add interactivity (with altair instead of matplotlib?)

</div>

</div>

---

## Quick Recap

----

### MyBinder

- Suppose your work:
  - is hosted on github (ex: `https://github.com/albop/computational_seminar.git`)
  - consists in jupyter notebooks
- You can spawn a small online virtual instance using MyBinder
  - copy the repo address in `mybinder.org`
- Edit / run python / Julia / R code
  - behavior can be customized by making modifications to requirements.txt in the repo (for Python)
- Remember: the data on this instance is ephemeral
  - you need to save it by downloading your work...
  - ... or by pushing modifications in another repo

----

### Logging work with Git (1/6)

- Assume:
  - the path to your work directory is: `/home/pablo/MyResearch`
  - you have a github repository `https://github.com/albop/MyResearch.git`
  - you have a terminal open in `MyResearch`

----

### Logging work with Git (2/6)

- Getting started:
  - `git init`:  put the directory under file control
  - `git add somefile`:  stage the file `somefile` so that its state will be recorded
  - `git commit -m "My First Commit"`: records the staged files

----

### Logging work with Git (3/6)

- To log your work, follow the following steps:
  - make some modifications
  - `git add thisfile thisotherfile...`
    - mark some files so their state will be recorded
  - `git commit -m "Some modifications"`
    - "commit" (record) the modifications
  - remark:
    - if you don't want to mark individual files, you can do one single step 
    - `git commit -a -m "Some modififications"`
    - all files that have previously been modified will be saved

----

### Logging work with Git (5/6)

- To log your work, follow the following steps:
  - make some modifications
  - `git add thisfile thisotherfile...`
    - mark some files so their state will be recorded
  - `git commit -m "Some modifications"`
    - "commit" (record) the modifications
  - remark:
    - if you don't want to mark individual files, you can do one single step 
    - `git commit -a -m "Some modififications"`
    - all files that have previously been modified will be saved

----


### Logging work with Git (6/6)

- Before you can save your work you need to add a remote repository
- `git add remote MyResearchRepo https://github.com/albop/MyResearch.git`
  - we give a short name `MyResearchRepo` to the git repository
- `git fetch`
  - see what has changed online
- `git push MyResearchRepo`
  - push the modifications online


----

### Using VSCode

![VSCode](../vscode_git.png)