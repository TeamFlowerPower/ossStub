# FOSS example project stub 


A user will evalute in general the following points before he starts using a project. Try to address them:

1. What is the purpose of this project an what can it to for me?
    1. Just explain as much as necessary and refer to the documentation for details
1. Is is easy to use / usable at all (does it compile)?
1. What do I need to do to run it?
1. What an how many dependencies do I need to satisfy?
    1. If they can be installed via a package manager use a one-line for installation

If a developer is interested he would ask:

1. How can I contribute (is there a process defined)?
1. Is the project still active/maintained (-> is it worth contributing)?
1. Is the code clean, understandable and well documented?

The following chapters show how I would build some structure for the top level readme.

# Project name
If not obvious tell what the project means in one or two sentences.

> Explain in 3 to 6 lines what does it do and why I should use it. Highlight it somehow

Give a more detailed explanation about the functionality of your project. This could be a view paragraphs long but not more. Explain the

* stages of your tool-chain,
* I/O formats,
* which features are realised,
* ...

Cross-reference to specific files/documentation wherever you can.

**Use graphics/gif's for visualisation!**

# Contents
Include a table of contents for long documents.

1. [General Workflow](#general-workflow)
1. [Quick Start Guide](#Quick-Start-Guide)
1. [Full Documentation](#Full-documentation)
1. [Contribute](#Contribute)
1. [Dependencies & Licences](#Dependencies--Licences)

Install dependencies: `pip3 install <pgk1>, <pgk2>, <pgk3>, <pgk4>, <pgk5>`

# General Workflow
Describe the general workflow, I/O formats. Better: even visualise it (flowcharts are your friend).

# Quick Start Guide
Tell what is needed to run a minimal example. What is important to get the user starting. What you really need to configure? For optional stuff refer to the full documentation.

# Full documentation
For the full documentation please refer to the [`./doc/`](doc) directory.

# Contribute
We are glad if you want to participate. In [./doc/contribute.md](doc/contribute.md) you will find a guide telling you everything you need to know including coding conventions and more.

# Dependencies & Licences

Utility scripts in [`./doc/`](doc) need additional dependencies. As a normal user you can ignore this.

| Library (version)        | pip package name                                    | Licence                              | URL                                                                                                                                                |
|--------------------------|-----------------------------------------------------|--------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------|
| <pck-name> (v1.0.9+)    | [gprof2dot](https://pypi.org/project/gprof2dot/)     | SPDX-identifier                      | [https://www.example.com](https://www.example.com)                                                                                                 |


**Code snippets etc.:**

| Name (version)           | Kind                                                     | Modified?  | Licence         | URL                                                                                                                                                       |
|--------------------------|----------------------------------------------------------|------------|-----------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|
| <proj-name> (v1.1.0+)    | Explain usage / how is it included in you code/project   | Yes        | SPDX-identifier | [https://www.example.com](https://www.example.com); [https://www.example.com](https://www.example.com)                                                    |


For the full documentation please refer to the [`./doc/`](doc) directory.
