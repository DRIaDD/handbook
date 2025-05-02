---
layout: default
title: Rigour and reproducibility
subtitle: 
---

## Rigour and reproducibility

### Why is reproducibility (scientific rigour) important?

Replication serves as the foundation of advancing scientific knowledge over time. While completely duplicating studies with independently gathered data can be challenging, there has been a growing demand for ensuring research reproducibility as a fundamental benchmark for evaluating the credibility of scientific assertions. Reproducibility isn't just an obligation to the scientific community; it also holds significance for individual researchers and teams in ensuring efforts are not duplicated. 

### Documentation 

Whenever a result holds the possibility of being valuable, maintain a record of the methods used to obtain it. We refer to such a series of actions, whether they are automated or carried out manually, as an analysis workflow. While a single step often constitutes the core of an analysis, the entire sequence of preliminary and follow-up processes frequently plays a vital role in achieving the final outcome. *As a minimum requirement*, it is advisable to document enough information about software programs, settings, and manual processes so that you can roughly replicate the results after some time, perhaps a year or more. 

### Avoid manual data manipulation 

Whenever you can, use computer programs rather than doing things manually to change data. Manual methods are not only slow and prone to mistakes but also hard to replicate.

### Version control

Maintaining a record of modifications made to your data, software and code by either yourself or your collaborators is a vital aspect of research. The ability to identify and retrieve a specific version of the entire project or code is instrumental in achieving research reproducibility. This is beneficial at various stages of your research journey, including the pre-publication phase, responding to reviewer comments, and providing supplementary information to reviewers, editors, and readers. The standard solution to track evolution of code is to use a version control system, such as Subversion, Git, or Mercurial.

*Git* is a version control software that allows tracking changes in a folder. It can be used like the "track change" option in Word, LibreOffice or Google docs, but for all types of files. By default, one uses a terminal to give Git instructions in the command line. To avoid using the command line terminal, you could use the client/interface *Github Desktop*, which uses Git in the background to manage your files, both locally on your computer, and remotely on a Github server. Details on how to install, set up a Github account, concepts and basic functions can be accessed [here](https://epirhandbook.com/en/version-control-and-collaboration-with-git-and-github.html).

### Code and software

We use various software tools and programming languages, including R, C++, Python, Julia, and STATA,, for tasks such as data cleaning, wrangling, manipulation, analysis, and simulations. Regardless of the software you choose, it's good practice to prioritise reproducibility.

### Documentation standard

* Provide textual statements to the underlying project (introduction that explains the project's purpose, goals, and any relevant background information).
* List all the materials, software, datasets, or hardware required for the project.
* Break down the project into a series of well-defined steps. Each step should be clear and unambiguous.
* For each step, provide detailed instructions on what should be done. Include specific commands, code to write or run, settings to configure, input data, and expected outputs.
* Provide a section on acknowledgement of limitation (if applicable).

### Further resources

* [Ten Simple Rules for Reproducible Computational Research](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003285)
* [Good enough practices in scientific computing](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005510#sec009)
