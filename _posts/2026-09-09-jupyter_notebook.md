---
layout: post
title: Setup Python Coding Workspace with VS Code
date: 2026-09-09 22:14:00
description: Installing Python, VS-Code and setting up Jupyter notebook.
tags: python VS-Code research jupyter automation coding
categories: coding
thumbnail: assets/img/blog/setup_coding_workspace.webp
og_image: /assets/img/blog/setup_coding_workspace.webp
giscus_comments: false
related_posts: true
toc:
  sidebar: left
mermaid:
  enabled: false
---

Setting up a coding workspace with Python and VS Code is straightforward. In this guide, we will install Python, install VS Code, configure a Python environment, and run our first Python program in a Jupyter notebook.

[[add video link]]

#### Install Python
- Download the latest Python installer from the [official Python website](https://www.python.org/).
- In the installer window click <input type="checkbox" checked> **Add python.exe to PATH** ⚠️
- Complete the installation.


#### Install VS Code
- Download VS Code from [https://code.visualstudio.com/](https://code.visualstudio.com/)
- in the installer window, enable <input type="checkbox" checked> **"Open with Code" in the Windows Explorer context menu.**. It will help you open folders in VS Code easily.
- Complete the installation.

#### Integrate VS Code and Python
Now that both Python and VS Code are installed, let us create our coding workspace. The first time, there will be a few installations to complete, so be patient and read the prompts carefully before cancelling.

- Create a folder named codes/python in Explorer. Right-click on the folder > Open with Code.
- VS Code asks whether you trust the authors of the files in the folder; select `Trust`.
- Create a new file named **test.ipynb**.
- Click `+ Code` on top and type 
 ```Python
    print("Hello World!")
 ```
- Run the cell by clicking ▷. Click the prompt **Install/Enable suggested extensions Python + Jupyter** and wait for the installation to complete.
- Upon completion, there will be a prompt to select **Python Environments...**. Click and select the Python you just installed.
- click run ▷ again and in the prompt install `ipykernel`.
- Finally, you will see the output of the cell 
 ```text
 Hello World!
 ```
#### Installing packages with pip
Now install some packages in Python.
- In the VS Code window press **Ctrl + `** to open the integrated terminal.
- Check Python version by the `python -V` command. It should match the Python version you just installed.
- for installing packages **scipy** and **pymoosh** give command 
 ``` shell
    pip install scipy pymoosh
 ```
- After installing, you can see the packages with the `pip list` command.

#### Try the notebook
```Python
import hello
```
```Python
import this
```
```Python
import antigravity
```

You now have a working Python + VS Code + Jupyter environment and are ready to start coding!


#### Further Reading
- [Python for Beginners](https://www.python.org/about/gettingstarted/) — The official Python beginner guide, including tutorials, documentation, and learning resources.
- [Python Tutorial](https://docs.python.org/3/tutorial/) — The official tutorial covering Python syntax, data structures, functions, modules, and more.
- [Real Python – Beginner Tutorials](https://realpython.com/tutorials/basics/) — Beginner-friendly tutorials and structured learning paths with practical examples and projects.
- [Automate the Boring Stuff with Python](https://automatetheboringstuff.com/) — A practical introduction to Python through automation projects such as working with files, spreadsheets, PDFs, and web scraping. The current edition is available online for free.
