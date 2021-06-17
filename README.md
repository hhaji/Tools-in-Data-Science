The Webpage of This Repository: [Tools in Data Science](https://hhaji.github.io/Tools-in-Data-Science/) <br>
[Data Science Center](http://ds.sbu.ac.ir), [Shahid Beheshti University](http://www.sbu.ac.ir/)  

---
```javascript
In this repository, we introduce some videos, slides, notebooks, and papers about some of 
important tools in data science and also some tools to write or share your projects. 
```
---

### **Index:**
- [Command Line](#Command-Line)
- [Anaconda](#Anaconda)
- [Jupyter and IPython](#Jupyter-and-IPython)
  - [Jupyter Lab](#JLAB)
  - [R NoteBook](#RNoteBook)
- [Markdown](#Markdown) 
  - [R Markdown](#RMarkdown) 
- [Colaboratory](#Colaboratory) 
- [Git](#Git)
  - [Git Resources](#Git-Resources)
  - [Videos](#Videos)
  - [Git Cheat Sheets](#Git-Cheat-Sheets)
  - [Slides](#Slides)
  - [GitHub](#GitHub)
- [Programming Languages](#Programming-Languages)
  - [Python](#Python)
  - [R](#R)
  - [Useful R Sites](#URS)
  - [Useful R Tricks](#URT)
  - [Machine Learning in R](#MLR)
  - [Useful Machine Learning Sites in R](#UMLSR) 
  - [Practice Code](#Project-Euler)
  - [SQL](#SQL)
- [Python Libraries for Data Science](#Python-Libraries-for-Data-Science) 
  - [Numpy](#Numpy)
  - [Pandas](#Pandas)
  - [Matplotlib](#Matplotlib)
  - [Scikit-Learn](#Scikit-Learn)
  - [SciPy](#SciPy)
  - [Probabilistic Programming in Python](#PPP)
  - [A Fascinating Guide For Machine Learning](#A-Fascinating-Guide-For-Machine-Learning)
- Files
  - [Cheat Sheets](https://hhaji.github.io/Tools-in-Data-Science/Cheat%20Sheets)
  - [Python Libraries](https://hhaji.github.io/Tools-in-Data-Science/Python%20Libraries)
  
---

## <a name="Command-Line"></a>Command Line:  
    
   * [Introduction to the Command Line](https://github.com/justmarkham/DAT8/blob/master/code/02_command_line.md) by Kevin Markham   
   * Cheat Sheet: [Windows](http://www1.cs.columbia.edu/~sedwards/classes/2017/1102-spring/Command%20Prompt%20Cheatsheet.pdf)   
   * Cheat Sheet: [Linux & Mac](http://blog.markpearl.co.za/assets/documents/bash-cheatsheet.pdf)    

   ```
   Additional Reading:
   ```  
    
    
   * Book: [Data Science at the Command Line](http://shop.oreilly.com/product/0636920032823.do)
   * Blog: [12 Essential Command Line Tools for Data Scientists](https://www.dataquest.io/blog/top-12-essential-command-line-tools-for-data-scientists/) by Matthew Mayo 

## <a name="Anaconda"></a>Anaconda:
[Anaconda Distribution](https://www.anaconda.com/what-is-anaconda/): With over 6 million users, the open source Anaconda Distribution is the fastest and easiest way to do Python and R data science and machine learning on Linux, Windows, and Mac OS X. It's the industry standard for developing, testing, and training on a single machine.
  
  * [Instalation](https://docs.anaconda.com/anaconda/install/)
  * Blog: [Managing Environments](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#managing-environments) <br>
  * Blog: [Kernels for Different Environments](https://ipython.readthedocs.io/en/stable/install/kernel_install.html#kernels-for-different-environments) <br>
  * [Getting Started with Conda](https://conda.io/docs/user-guide/getting-started.html)
  * [Why You Need Python Environments and How to Manage them with Conda](https://protostar.space/why-you-need-python-environments-and-how-to-manage-them-with-conda) by  Gergely Szerovay
  
   ```
   Additional Reading:
   ```
  * [Stop Installing Tensorflow Using pip for Performance Sake!](https://towardsdatascience.com/stop-installing-tensorflow-using-pip-for-performance-sake-5854f9d9eb0c) by Michael Nguyen <br> 
  * [Using Pip in a Conda Environment](https://www.anaconda.com/using-pip-in-a-conda-environment/) by Jonathan Helmus 
  * [Conda Commands (Create Virtual Environments for Python with Conda)](http://deeplearning.lipingyang.org/2018/12/25/conda-commands-create-virtual-environments-for-python-with-conda/) by LipingY  
  * [Conda Cheat Sheet](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf) 

## <a name="Jupyter-and-IPython"></a>Jupyter and IPython:
The [Jupyter](https://jupyter.org) is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text. Uses include: data cleaning and transformation, numerical simulation, statistical modeling, data visualization, machine learning, and much more. Also, [IPython](https://ipython.org) provides a rich architecture for interactive computing with in multiple programming languages.

   * [Jupyter Notebook for Beginners: A Tutorial](https://www.dataquest.io/blog/jupyter-notebook-tutorial/) by Benjamin Pryke
   * [Advanced Jupyter Notebooks: A Tutorial](https://www.dataquest.io/blog/advanced-jupyter-notebooks-tutorial/) by Benjamin Pryke
   * [28 Jupyter Notebook Tips, Tricks, and Shortcuts](https://www.dataquest.io/blog/jupyter-notebook-tips-tricks-shortcuts/) by Josh Devlin 
   * [Import-Ipynb:](https://pypi.org/project/import-ipynb/) The code within import_ipynb.py defines a “notebook loader” that allows you to “import” other ipynb files into your current ipynb file.   

   ```
   Additional Reading:
   ```
    
   * [Six Easy Ways to Run Your Jupyter Notebook in the Cloud](https://www.dataschool.io/cloud-services-for-jupyter-notebook/)   
   * [IPython and Shell Commands](https://jakevdp.github.io/PythonDataScienceHandbook/01.05-ipython-and-shell-commands.html)
   * [IPython: Beyond Normal Python](https://www.oreilly.com/library/view/python-data-science/9781491912126/ch01.html)
   * [Jupyter/IPython Notebook Quick Start Guide](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/)
   * [Built-in Magic Commands](https://ipython.readthedocs.io/en/stable/interactive/magics.html)
   * [Defining Custom Magics](https://ipython.org/ipython-doc/dev/config/custommagics.html)    * [Introducing IPython:](https://ipython.org/ipython-doc/3/interactive/tutorial.html) Differences between line-oriented and cell-oriented magic functions 
   * Paper: [Ten Simple Rules for Reproducible Research in Jupyter Notebooks](https://arxiv.org/pdf/1810.08055.pdf)
   * Talk: [Jupyter (Formerly IPython Notebook)](http://www2.imm.dtu.dk/pubdb/views/edoc_download.php/6973/pdf/imm6973.pdf) by Finn Arup Nielsen <br>
    
### <a name="JLAB"></a>Jupyter Lab:

   * [Awesome JupyterLab](https://github.com/mauhai/awesome-jupyterlab) by Hai Nguyen Mau
   * [JupyterLab Extension](https://github.com/topics/jupyterlab-extension) 
   
   ```
   Additional Reading:
   ```
    
   * [Jupyter Lab extensions for Data Scientist](https://medium.com/@subpath/jupyter-lab-extensions-for-data-scientist-e0d97d529fc1) by Alexander Osipenko 
   * Install: [The R kernel in Jupyter Lab](https://richpauloo.github.io/2018-05-16-Installing-the-R-kernel-in-Jupyter-Lab/) by Rich Pauloo <br> 
 
### <a name="RNoteBook"></a>R NoteBook:
   * [Advantages of Using R Notebooks For Data Analysis Instead of Jupyter Notebooks](https://minimaxir.com/2017/06/r-notebooks/) 
by Max Woolf <br>
   * [R Notebook](https://bookdown.org/yihui/rmarkdown/notebook.html) by Yihui Xie, J. J. Allaire, and Garrett Grolemund <br> 

## <a name="Markdown"></a>Markdown:
[Markdown](https://www.markdownguide.org/getting-started) is a lightweight markup language that you can use to add formatting elements to plaintext text documents. Created by John Gruber in 2004, Markdown is now one of the world’s most popular markup languages.

   * Blog: [Learn Markdown Online](https://commonmark.org/help/tutorial/) 
   * Cheat Sheet: [Markdown Syntax](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf) 
   * Blog: [Markdown Tables Generator](https://www.tablesgenerator.com/markdown_tables)  

   ```
   Additional Reading:
   ```

   * [Getting Started with R Markdown](https://ourcodingclub.github.io/2016/11/24/rmarkdown-1.html)
   * [Word to Markdown](https://word-to-markdown.herokuapp.com)
   * [Complete List of GitHub Markdown Emoji Markup](https://gist.github.com/rxaviers/7360908) by Rafael Xavier de Souza  

### <a name="RMarkdown"></a>R Markdown:
   * [R Markdown](https://rmarkdown.rstudio.com)
   * [R Markdown: The Definitive Guide](https://bookdown.org/yihui/rmarkdown/) by Yihui Xie, J. J. Allaire, and Garrett Grolemund <br>
   * [R Markdown Cheat Sheet - RStudio](https://rmarkdown.rstudio.com/lesson-15.html)

## <a name="Colaboratory"></a>Colaboratory  
* [Welcome to Colaboratory!](https://colab.research.google.com/notebooks/welcome.ipynb)    
Colaboratory is a free Jupyter notebook environment that requires no setup and runs entirely in the cloud. With Colaboratory you can write and execute code, save and share your analyses, and access powerful computing resources, all for free from your browser.  
  - [Overview of Colaboratory](/notebooks/basic_features_overview.ipynb)
  - [Guide to Markdown](/notebooks/markdown_guide.ipynb)
  - [Unrar, Unzip, Rar, Zip in Gdrive](https://colab.research.google.com/drive/1xinRwhXtlL-9Y0KbPrTmTxNdcN-Hvq4m)  
  - [Importing Libraries and Installing Dependencies](/notebooks/snippets/importing_libraries.ipynb)
  - [Saving and Loading Notebooks in GitHub](https://colab.research.google.com/github/googlecolab/colabtools/blob/master/notebooks/colab-github-demo.ipynb)
  - [Interactive Forms](/notebooks/forms.ipynb)
  - [Interactive Widgets](/notebooks/widgets.ipynb)
  - [TensorFlow 2 in Colab](/notebooks/tensorflow_version.ipynb)
  - [Loading Data: Drive, Sheets, and Google Cloud Storage](/notebooks/io.ipynb) 
  - [Charts: Visualizing Data](/notebooks/charts.ipynb)
  - [Getting Started with BigQuery](/notebooks/bigquery.ipynb)

### Working with Data
- [Loading data: Drive, Sheets, and Google Cloud Storage](/notebooks/io.ipynb) 
- [Charts: visualizing data](/notebooks/charts.ipynb)
- [Getting started with BigQuery](/notebooks/bigquery.ipynb)

## <a name="Git"></a>Git
[Git](https://git-scm.com) is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency. Git is [easy to learn](https://git-scm.com/doc) and has a [tiny footprint with lightning fast performance](https://git-scm.com/about/small-and-fast). 

### <a name="Git-Resources"></a>Git Resources:
   * [Resources to Learn Git](https://try.github.io)
   * [Pro Git](http://git-scm.com/book/en/v2) is an excellent book to learn Git.
   
   ```
   Additional Reading:
   ```
   * [Git Workflow](https://backlog.com/git-tutorial/git-workflow/)  
   * [Git Immersion](http://gitimmersion.com/) looks promising to practice Git.
   * [Git Quick Reference for Beginners](https://www.dataschool.io/git-quick-reference-for-beginners/)
   * Learn Git from [Git Handbook](https://guides.github.com/introduction/git-handbook/)
   * [Practice Git Online](https://learngitbranching.js.org)
   * Learn Git from Scratch in [LabEx](https://labex.io/courses/learn-git-from-scratch)
   * [Git Book](https://git-scm.com/book/en/v2)
   * [Git Tutorial](http://www.cs.columbia.edu/~sedwards/classes/2013/4840/git-tutorial.pdf) by Jae Woo Lee and Stephen A. Edwards  
   * [Git Tools - Reset Demystified](https://git-scm.com/book/en/v2/Git-Tools-Reset-Demystified)

### <a name="Videos"></a>Videos:
   * [Parsclick (Git: In Persian)](https://parsclick.net/course/PL3Y-E4YSE4wYFlcomsBtJy1nCu3jclA8L) 
   * [Parsclick (GitHub: In persian)](https://parsclick.net/course/PL3Y-E4YSE4wa_TUfN7G3rAMIiu6vIeepT) 

### <a name="Git-Cheat-Sheets"></a>Git Cheat Sheets:
   * [Git Cheat Sheet](https://github.com/hhaji/Tools-in-Data-Science/blob/master/Cheat%20Sheets/Git%20Cheat%20Sheet.md) 
   * [GitHub Training](https://services.github.com/on-demand/downloads/github-git-cheat-sheet.pdf) 
   * [Git Lab](https://about.gitlab.com/images/press/git-cheat-sheet.pdf)
   * [GitHub Education](https://education.github.com/git-cheat-sheet-education.pdf)

### <a name="Slides"></a>Slides:
   * [An Introduction to Git](https://elite.polito.it/files/courses/03FYZ/2017/slide/Git-01-intro.pdf) by Politecnico di Torino
   * [GIT for Beginners](https://people.irisa.fr/Anthony.Baire/git/git-for-beginners-handout.pdf) by Anthony Baire
   * [A Quick Guide to Git and Version Control](http://sites.utexas.edu/asa-student-chapter/files/2016/04/Grad_Skills_Seminar_11-17-17_Git_and_Version_Control.pdf) by Jay Johnson

### <a name="GitHub"></a>GitHub:
   * [Tutorial: Introduction to Git and Github](https://www.dataquest.io/blog/tutorial-introduction-learn-git-github/)
   * To understand how to contribute on GitHub, learn first [forks and pull requests](http://www.dataschool.io/simple-guide-to-forks-in-github-and-git/). 

## <a name="Programming-Languages"></a>Programming Languages: 
### <a name="Python"></a>Python:
You can learn python via [SoloLearn](http://www.sololearn.com/) (A great website for getting started with coding. It offers easy to follow lessons, interspersed with quizzes to help you retain what you are learning). Also, we recommend the following references: 

   * Book: [Think Python: How to Think Like a Computer Scientist](http://greenteapress.com/wp/think-python-2e/), Second  Edition, by Allen B. Downey (free PDF book) 

   ```
   Additional Reading:
   ```

   * [Python3 Tutorial:](https://www.python-course.eu/python3_course.php) This online Python course was created and is maintained by Bernd Klein, an experienced Python trainer, giving training classes all over the world. It is an interesting introduction into Python for beginners and intermediate learners with lots of examples and exercises! 
   * [Regular Expressions for Data Scientists](https://www.dataquest.io/blog/regular-expressions-data-scientists/) by Alex Yang 
   * Python Generators](https://www.dataquest.io/blog/python-generators-tutorial/) by Christian Pascual 
   * [Real Python Tutorials](https://realpython.com) 
   * Book: [How to Think Like a Computer Scientist](http://interactivepython.org/courselib/static/thinkcspy/index.html) by Brad Miller and David Ranum
   * Book: [Python for Everybody](https://www.py4e.com/book.php) by Charles R. Severance (free PDF book)
   * Book: [Practical Programming (2nd edition): An Introduction to Computer Science Using Python 3](https://pragprog.com/book/gwpy2/practical-programming) by Paul Gries, Jennifer Campbell, and Jason Montojo, 2013.
   * Book: The Python Tutorial ([available from the Python website](https://docs.python.org/3.6/tutorial/))
   * Learn Python from [LabEx](https://labex.io/courses/intro-to-python-3)
   * [Useful Functions, Tutorials, and Other Python-Related Things](https://github.com/rasbt/python_reference)
   * [Python Debugging with pdb](https://www.machinelearningplus.com/python/python-debugging/)
   * [How to Use the Python Debugger](http://fastml.com/how-to-use-the-python-debugger/) by Zygmunt
   * [Errors and Debugging](https://jakevdp.github.io/PythonDataScienceHandbook/01.06-errors-and-debugging.html) by Jake VanderPlas
   * [Python Data Science Tutorials](https://github.com/ujjwalkarn/DataSciencePython) by Ujjwal Karn
   
   ```
   Useful Tricks in Python:
   ```
   
   * [IF __NAME__ == “__MAIN__”](http://plantbasedprogrammer.com/if-__name__-__main__/) by Peter Lynch   
   
   ```
   Useful Modules in Python:
   ```  
   
   * [Argparse](https://docs.python.org/3/library/argparse.html): The argparse module makes it easy to write user-friendly command-line interfaces.  
      - [How to Build Command Line Interfaces in Python With Argparse](https://realpython.com/command-line-interfaces-python-argparse/) by  Davide Mastromatteo  
      - [Python, Argparse, and Command Line Arguments](https://www.pyimagesearch.com/2018/03/12/python-argparse-command-line-arguments/) Python, argparse, and command line arguments by Adrian Rosebrock   
   * [Warning Control:](http://www.wingware.com/psupport/python-manual/3.1/library/warnings.html) Warning messages are typically issued in situations where it is useful to alert the user of some condition in a program, where that condition (normally) doesn’t warrant raising an exception and terminating the program.  
      - [Warnings in Python](https://www.geeksforgeeks.org/warnings-in-python/) by Rituraj Saha   
      - [How to Use Python Warnings Framework?](https://www.idiotinside.com/2016/12/17/python-warnings-framework/)
   * [PDB Module:](https://docs.python.org/3/library/pdb.html) This module defines an interactive source code debugger for Python programs.  
      - [Debugging Python Applications with the PDB Module](https://stackabuse.com/debugging-python-applications-with-the-pdb-module/) by Muhammad Junaid Khalid  
   * [Pickle Module:](https://docs.python.org/3/library/pickle.html) This module implements binary protocols for serializing and de-serializing a Python object structure. “Pickling” is the process whereby a Python object hierarchy is converted into a byte stream, and “unpickling” is the inverse operation, whereby a byte stream (from a binary file or bytes-like object) is converted back into an object hierarchy.   
      - [The Python pickle Module: How to Persist Objects in Python](https://realpython.com/python-pickle-module/) by Davide Mastromatteo   
   * Methods and Attributes in Python:
      - Blog: [Python's Instance, Class, and Static Methods Demystified](https://realpython.com/instance-class-and-static-methods-demystified/) by Dan Bader   
      - Blog: [Class and Instance Attributes](https://www.python-course.eu/python3_class_and_instance_attributes.php)  
      - Blog: [Python's @classmethod and @staticmethod Explained](https://djangocentral.com/classmethod-and-staticmethod-explained/)  
      - Question: [Module Function vs Staticmethod vs Classmethod vs no Decorators: Which Idiom is More Pythonic?](https://stackoverflow.com/questions/11788195/module-function-vs-staticmethod-vs-classmethod-vs-no-decorators-which-idiom-is)
   
### <a name="R"></a>R: 
   * Online Book: [R for Data Science](https://r4ds.had.co.nz/index.html) <br>
   
   ```
   Additional Reading:
   ```
   
   * Online Book: [YaRrr! The Pirate’s Guide to R](https://bookdown.org/ndphillips/YaRrr/) by Nathaniel D. Phillips <br>
   * Online Book: [Efficient R programming](https://csgillespie.github.io/efficientR/) by Colin Gillespie and Robin Lovelace <br>
   * [R Tutorial for Beginners: Learning R Programming](https://www.guru99.com/r-tutorial.html) <br>
   * [R-Statistics](https://r-statistics.co) by Selva Prabhakaran <br>

### <a name="URS"></a>Useful R Sites:
   * Command Line: [The Workspace](https://www.statmethods.net/interface/workspace.html) <br>
   * Blog: [Awesome R](https://awesome-r.com) <br>
   * Blog: [Quick List of Useful R Packages](https://support.rstudio.com/hc/en-us/articles/201057987-Quick-list-of-useful-R-packages) by Garrett Grolemund <br>
   * [Getting used to R, RStudio, and R Markdown](https://bookdown.org/chesterismay/rbasics/) by Chester Ismay <br>
   * [Formulas in R Tutorial](https://www.datacamp.com/community/tutorials/r-formula-tutorial) by Karlijn Willems <br>
   * [Google's R Style Guide](https://google.github.io/styleguide/Rguide.xml) <br>
   * [R Data Science Tutorials](https://github.com/ujjwalkarn/DataScienceR) by Ujjwal Karn
   * Data Science Wars: [Choosing R or Python for Data Analysis? An Infographic](https://www.datacamp.com/community/tutorials/r-or-python-for-data-analysis) <br>
   * [R Coding Style Guide](https://www.r-bloggers.com/%F0%9F%96%8A-r-coding-style-guide/) by Iegor Rudnytskyi <br>
   * [Base R (Cheat Sheet)](https://www.ethz.ch/content/dam/ethz/special-interest/math/statistics/sfs/Education/Advanced%20Studies%20in%20Applied%20Statistics/course-material-1719/R/base-r-cheat-sheet.pdf)  <br>
   * [R Programming Cheat Sheet](http://www.datasciencefree.com/advancedR.pdf) Arianne Colton and Sean Chen <br>

### <a name="URT"></a>Useful R Tricks:
   * [Simplify Your Code with %>% (Pipes)](https://uc-r.github.io/pipe) by UC Business Analytics R Programming Guide <br>
   * [Pipes](https://r4ds.had.co.nz/pipes.html) by Garrett Grolemund and Hadley Wickham <br>

### <a name="MLR"></a>Machine Learning in R: 
   * Book: [Machine Learning Mastery With R](https://machinelearningmastery.com/machine-learning-with-r/) by Jason Brownlee
   * Blog: [Caret Package](https://topepo.github.io/caret/index.html) by Max Kuhn
   * Blog: [An Introduction to Machine Learning with R](https://lgatto.github.io/IntroMachineLearningWithR/index.html) Laurent Gatto 

### <a name="UMLSR"></a>Useful Machine Learning Sites in R: 
   * Cheat Sheet: [Caret Package](https://ugoproto.github.io/ugo_r_doc/caret.pdf) by Max Kuhn
   * Blog: [Caret Package – A Practical Guide to Machine Learning in R](https://www.machinelearningplus.com/machine-learning/caret-package/)
   * NoteBook: [Principles of Machine Learning R](https://github.com/MicrosoftLearning/Principles-of-Machine-Learning-R) 
   * Blog: [Practical Machine Learning Course Notes](https://sux13.github.io/DataScienceSpCourseNotes/8_PREDMACHLEARN/Practical_Machine_Learning_Course_Notes.html) by Xing Su 

### <a name="Project-Euler"></a>Practice Code:
If you want to solve interesting problems to practice Python or R, then we recommend to solve the following problems:   
   * Blog: [Project Euler](https://projecteuler.net/)! 
   * Blog: [Codeforces](https://codeforces.com/)

### <a name="SQL"></a>SQL:
SQL is a a domain-specific language for managing data in databases.
* [SQL Fundamentals](https://www.dataquest.io/blog/sql-fundamentals/) by Srini Kadamati <br>

## <a name="Python-Libraries-for-Data-Science"></a>Python Libraries for Data Science:
Python continues to take leading positions in solving data science tasks and challenges. [Kdnuggets](https://www.kdnuggets.com/2018/06/top-20-python-libraries-data-science-2018.html) introduced 20 libraries of Python for data science. The following table was adopted from [Applied Machine Learning and Deep Learning](http://people.uncw.edu/chenc/STT592_Deep%20Learning/STT592DeepLearning_Index.html) created by Cuixian Chen. Here are five of the most important of libraries:   

 <table>
  <tr>
    <td><span style="font-weight:bold">Python Overview [</span><a href="http://people.uncw.edu/chenc/STT592_Deep%20Learning/Python/Python%20Overview.docx"><span style="font-weight:bold">Word</span></a><span style="font-weight:bold">]</span><br><br><br><span style="font-weight:bold">Python Tutorial [</span><a href="http://people.uncw.edu/chenc/STT592_Deep%20Learning/Python/python_intro.pdf"><span style="font-weight:bold">PDF</span></a><span style="font-weight:bold">]  [</span><a href="http://people.uncw.edu/chenc/STT592_Deep%20Learning/Python/python_tutorial2.pdf"><span style="font-weight:bold">Code</span></a><span style="font-weight:bold">]</span></td>
    <td><span style="font-weight:bold">Numpy [</span><a href="http://people.uncw.edu/chenc/STT592_Deep%20Learning/Python/python_tutorial2.pdf"><span style="font-weight:bold">PDF</span></a><span style="font-weight:bold">] [</span><a href="http://people.uncw.edu/chenc/STT592_Deep%20Learning/Python/Kling_Python%20Scripts/numpy_tutorial.py"><span style="font-weight:bold">Code</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">User Guide [</span><a href="https://docs.scipy.org/doc/numpy-1.15.0/index.html"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Quickstart [</span><a href="https://docs.scipy.org/doc/numpy-1.15.0/user/quickstart.html"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Reference [</span><a href="https://docs.scipy.org/doc/numpy-1.15.0/reference/index.html"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Practice Numpy in LabEx [</span><a href="https://labex.io/courses/100-numpy-exercises"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Cheatsheet [</span><a href="http://www.utc.fr/~jlaforet/Suppl/python-cheatsheets.pdf"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span></td>
    <td><span style="font-weight:bold">Matplotlib [</span><a href="http://people.uncw.edu/chenc/STT592_Deep%20Learning/Python/python_tutorial2.pdf"><span style="font-weight:bold">PDF</span></a><span style="font-weight:bold">][</span><a href="http://people.uncw.edu/chenc/STT592_Deep%20Learning/Python/Kling_Python%20Scripts/matplotlib_tutorial.py"><span style="font-weight:bold">Code</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Example [</span><a href="https://matplotlib.org/gallery/index.html#"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Tutorials [</span><a href="https://matplotlib.org/tutorials/index.html"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Reference [</span><a href="https://matplotlib.org/api/_as_gen/matplotlib.pyplot.html"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Practice Matplotlib in LabEx [</span><a href="https://labex.io/courses/draw-2d-and-3d-graphics-by-matplotlib"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Cheatsheet [</span><a href="http://www.utc.fr/~jlaforet/Suppl/python-cheatsheets.pdf"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span></td>
  </tr>
  <tr>
    <td><span style="font-weight:bold">Pandas [</span><a href="http://people.uncw.edu/chenc/STT592_Deep%20Learning/Python/Pandas_tutorial.py"><span style="font-weight:bold">Code</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">10 Min to Pandas [</span><a href="https://pandas.pydata.org/pandas-docs/stable/10min.html"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Cookbook [</span><a href="https://pandas.pydata.org/pandas-docs/stable/cookbook.html"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Tutorials [</span><a href="https://pandas.pydata.org/pandas-docs/stable/tutorials.html"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Reference [</span><a href="https://pandas.pydata.org/pandas-docs/stable/"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Practice Pandas in LabEx [</span><a href="https://labex.io/courses/100-pandas-exercises"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Cheatsheet [</span><a href="http://www.utc.fr/~jlaforet/Suppl/python-cheatsheets.pdf"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span></td>
    <td><span style="font-weight:bold">Seaborn: Stat data </span><br><span style="font-weight:bold">Visulization [</span><a href="https://seaborn.pydata.org/"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Example [</span><a href="https://seaborn.pydata.org/examples/index.html"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Tutorials [</span><a href="https://seaborn.pydata.org/tutorial.html"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Reference [</span><a href="https://seaborn.pydata.org/api.html#api-ref"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Cheatsheet [</span><a href="http://www.utc.fr/~jlaforet/Suppl/python-cheatsheets.pdf"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span></td>
    <td><span style="font-weight:bold">Scikit Learn [</span><a href="https://scikit-learn.org/stable/?fbclid=IwAR0DE6Q4LLO48d226SwF8j6TbUoqjBw769bNEcOBF9ohBW8Wgz9WscvgzEw"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">] </span><br><span style="font-weight:bold">Scikit Image [</span><a href="http://scikit-image.org/docs/dev/auto_examples/?fbclid=IwAR3v-V5IlW1Jjz-NcSbGuDFJ71KUFRk5KmPoFRCD8LuuAyTzUF8v0N4nwUU"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Scikit Tutorial #1 [</span><a href="http://people.uncw.edu/chenc/STT592_Deep%20Learning/Python/Kling_Python%20Scripts/scikit_tutorial.py"><span style="font-weight:bold">Code</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Scikit Tutorial #2 [</span><a href="http://people.uncw.edu/chenc/STT592_Deep%20Learning/Python/Kling_Python%20Scripts/scikit_tutorial2.py"><span style="font-weight:bold">Code</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Cheatsheet [</span><a href="https://s3.amazonaws.com/assets.datacamp.com/blog_assets/Scikit_Learn_Cheat_Sheet_Python.pdf"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span></td>
  </tr>
</table>


### <a name="Numpy"></a>Numpy:
[NumPy](http://www.numpy.org) is the fundamental package for scientific computing with Python. Besides its obvious scientific uses, NumPy can also be used as an efficient multi-dimensional container of generic data. Arbitrary data-types can be defined. This allows NumPy to seamlessly and speedily integrate with a wide variety of databases.<br>

   * [Scipy Lecture Notes](http://www.scipy-lectures.org/index.html) <br>
   
   ```
   Additional Reading:
   ```
   
   * [Data Science iPython NoteBooks](https://github.com/donnemartin/data-science-ipython-notebooks#pandas) by Donne Martin     
   * [Python Numpy Tutorial](http://cs231n.github.io/python-numpy-tutorial/) by Justin Johnson    
   * [Python for Data Analysis](https://github.com/ResearchComputing/Meetup-Fall-2013)     
   * Tutorial: [An Essential Guide to Numpy for Machine Learning in Python](http://onlinetutorials.today/numpy/an-essential-guide-to-numpy-for-machine-learning-in-python/) by Siddharth Dikshit    
   * NoteBook: [How Fast are NumPy Operations Compared to Regular Python Math?](https://github.com/tirthajyoti/Machine-Learning-with-Python/blob/master/Pandas%20and%20Numpy/How%20fast%20are%20NumPy%20ops.ipynb) by Tirthajyoti Sarkar    
   * Blog: [Data Science with Python: Turn your Conditional Loops to Numpy Vectors](https://towardsdatascience.com/data-science-with-python-turn-your-conditional-loops-to-numpy-vectors-9484ff9c622e) by Tirthajyoti Sarkar   
   * Blog: [One Simple Trick for Speeding up your Python Code with Numpy](https://towardsdatascience.com/one-simple-trick-for-speeding-up-your-python-code-with-numpy-1afc846db418) by George Seif    

   - **Exercises:** Practice Numpy in [LabEx](https://labex.io/courses/100-numpy-exercises)

### <a name="Pandas"></a>Pandas:
[Pandas](https://pandas.pydata.org) is an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language.<br>

   * [Data Science iPython NoteBooks](https://github.com/donnemartin/data-science-ipython-notebooks#pandas) by Donne Martin  <br>
   * [Using Excel with Pandas](https://www.dataquest.io/blog/excel-and-pandas/) by Harish Garg <br>
   * [Using pandas with Large Data Sets](https://www.dataquest.io/blog/pandas-big-data/) by Josh Devlin     
   * [IO Tools (text, CSV, HDF5, …)](https://pandas.pydata.org/pandas-docs/stable/user_guide/io.html#io-read-csv-table)   
   
   ```
   Additional Reading:
   ```
   
   * [Pandas (Faster Data Science Education by Kaggle)](https://www.kaggle.com/learn/pandas) by Aleksey Bilogur <br>
   * [Python for Data Analysis](https://github.com/ResearchComputing/Meetup-Fall-2013) <br>
   * [10 Minutes to Pandas](http://pandas.pydata.org/pandas-docs/stable/10min.html) <br>

   - Tutorial: [Visualizing Machine Learning One Concept at a Time](http://jalammar.github.io) by Jay Alammar
   - Tutorial: [Best practices with pandas (Video Series)](https://www.dataschool.io/best-practices-with-pandas/)
   - Tutorial: [9 New Pandas Updates That Will Save You Time](https://www.dataschool.io/python-pandas-updates/)
   - Blog: [Difference between Pandas VS NumPy](https://www.geeksforgeeks.org/difference-between-pandas-vs-numpy/) by Vansh Gaur   
   - **Exercises:** Practice Pandas in [LabEx](https://labex.io/courses/100-pandas-exercises)

### <a name="Matplotlib"></a>Matplotlib:
[Matplotlib](https://matplotlib.org) is a Python 2D plotting library which produces publication quality figures in a variety of hardcopy formats and interactive environments across platforms. Matplotlib can be used in Python scripts, the Python and IPython shells, the Jupyter notebook, web application servers, and four graphical user interface toolkits.

   * [Data Science iPython NoteBooks](https://github.com/donnemartin/data-science-ipython-notebooks#pandas) by Donne Martin <br>
      
   ```
   Additional Reading:
   ```
   
   * [Scipy Lecture Notes](http://www.scipy-lectures.org/index.html) <br>
   * [How to Generate FiveThirtyEight Graphs in Python](https://www.dataquest.io/blog/making-538-plots/) by Alex Olteanu <br>
   * [Top 50 Matplotlib Visualizations – The Master Plots (with Full Python Code)](https://www.machinelearningplus.com/plots/top-50-matplotlib-visualizations-the-master-plots-python/) <br>

   - **Exercises:** Practice Matplotlib in [LabEx](https://labex.io/courses/draw-2d-and-3d-graphics-by-matplotlib)

### <a name="Scikit-Learn"></a>Scikit-Learn:
[Scikit-Learn](https://scikit-learn.org) is a simple and efficient tools for data mining and data analysis. It was built on NumPy, SciPy, and Matplotlib. 

   * [Data Science iPython NoteBooks](https://github.com/donnemartin/data-science-ipython-notebooks#pandas) by Donne Martin <br>

### <a name="SciPy"></a>SciPy:
[SciPy](https://github.com/scipy/scipy) (pronounced "Sigh Pie") is open-source software for mathematics, science, and engineering. It includes modules for statistics, optimization, integration, linear algebra, Fourier transforms, signal and image processing, ODE solvers, and more.

   * [Scipy Lecture Notes](http://www.scipy-lectures.org/index.html) <br>
      
   ```
   Additional Reading:
   ```
   
   * [Data Science iPython NoteBooks](https://github.com/donnemartin/data-science-ipython-notebooks#pandas) by Donne Martin <br>

### <a name="PPP"></a>Probabilistic Programming in Python:  
[PyMC3](https://docs.pymc.io) allows you to write down models using an intuitive syntax to describe a data 
generating process.

### <a name="A-Fascinating-Guide-For-Machine-Learning"></a>A Fascinating Guide For Machine Learning:
   * [Technical Notes On Using Data Science & Artificial Intelligence: To Fight For Something That Matters](https://chrisalbon.com) by Chris Albon
