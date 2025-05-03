---
layout: page
title: Projects
permalink: /projects/
---
## Introduction 

In this section you will find posts related to the projects I have developed and released. My goal is to publish a new project every few weeks, and usually on weekends, as I am currently working late and cannot complete the posts any faster.

Each project will generally be developed as a single package or library in Python, C++, Java, Rust or Go, depending on the flavor of the week.

The Python projects are usually structured as follows:

```
📦repo
 ┣ 📂notebook
 ┃ ┗ 📜demo.ipynb
 ┣ 📂src
 ┃ ┣ 📂project_name
 ┃ ┃ ┣ 📜module.py
 ┃ ┃ ┗ 📜__init__.py
 ┃ ┗ 📂test
 ┃ ┃ ┗ 📜test_module.py
 ┣ 📜.gitignore
 ┣ 📜pyproject.toml
 ┣ 📜README.md
 ┗ 📜requirements.txt
```

The C++/Java projects will structured as follows:

```
📦repo
 ┣ 📂inc
 ┃ ┗ 📜example.hpp
 ┣ 📂src
 ┃ ┃ ┣ 📜example.cpp
 ┃ ┗ 📂test
 ┃ ┃ ┗ 📜example.cpp
 ┣ 📜 main.cpp
 ┣ 📜.gitignore
 ┣ 📜CMakeLists.txt
 ┣ 📜README.md
 ┗ 📜requirements.txt
```