---
layout: default
title: Coding guides and advice
subtitle: 
---

# Coding guides / advice

## Effective Coding and Modelling: Using Julia and R to Their Full Potential

Currently, R and Julia are the main programming languages used in our group.

For R:

* RStudio: An integrated development environment (IDE) that enhances R's usability. You can download it from [RStudio's official download page](https://posit.co/download/rstudio-desktop/).
* Basic R: The fundamental R environment for those who prefer a more traditional approach. Accessible from [R's official website](https://www.r-project.org/).
* Emacs, via the Emacs Speaks Statistics package. A highly customizable text editor. Has a somewhat steep learning curve, but is very versatile. Can be run within a terminal and hence is useful for working on remote servers.

For Julia:

* Julia can be operated through several interfaces, catering to diverse user preferences. It can be downloaded from [Julia's official download page](https://julialang.org/downloads/).
* Popular interfaces for Julia include:
** Jupyter Notebooks: Offering a web-based interactive computational environment.
** VS Code: With the Julia extension, it provides a powerful development tool for Julia users.
** REPL: The built-in Read-Eval-Print Loop that comes with the standard Julia installation for executing Julia commands.
** Emacs, via the Emacs Speaks Statistics package. See above for description.

## Guidelines when writing code

From [Cobey's Lab handbook for coding](https://github.com/cobeylab/lab_handbook/blob/master/05-coding.Rmd), there are 5 suggested guidelines when writing code:

* Comment your code for your peers and your future self: comments include intention, meta-information, future uses. Do it as you go, even rough notes are valuable.
* Use a linter, a tool to mark occurrences of suspicious and non-structural code (i.e. potential bugs) in source code. This helps the review process. There are linter tools in R {styler}, {lintr} , VS Code, and also AI tools such as Copilot which could help you to write and review code live. Copilot is free for students.
* Write tests: Unit tests written early will give you confidence to refactor code, and they help to verify a user is getting the same results.
* Use version control such as GitHub, and release / push / make public changes into new versions.

Refer to a coding style guide for best practices and consistency: 

* For R, consider the guidelines such as [Google's R Style Guide](https://google.github.io/styleguide/Rguide.html) and [Wickham's R for Data Science](https://r4ds.hadley.nz/).
* Julia programmers can consult the official [Julia Style Guide](https://docs.julialang.org/en/v1/manual/style-guide/) for conventions.

Include dependencies (libraries, packages and their versions), outputs (charts, files), and data if possible. [Check the university data policies for this](https://compliance.admin.ox.ac.uk/data-protection-policy), connect to open data or even dummy data is preferable than none. 

Write code that's meant to be reproduced: write clear and understandable concepts, 

* Clarify purpose, state of the code, data, and environment are controlled so the user produces the same result as the researcher.
* Interoperability: How well the code interfaces with other tools, and has a standard method for interacting with it.

Use a version control system that is hosted in a repository—such as GitHub, GitLab, or Bitbucket that makes collaboration easy. This serves to catch errors, roll back, and track progress. To serve its purposes, the repository is best to be updated daily, either with new code or tasks assigned. Document the repository. And remember the repository has to be made public when a manuscript is submitted. It would be useful if your peers try to reproduce your results with your code as the only source of information.
