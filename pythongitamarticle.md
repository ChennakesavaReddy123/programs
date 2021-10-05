# What is Python?

Python is an interpreted, object-oriented, high-level programming language with dynamic semantics. Its high-level built in data structures, combined with dynamic typing and dynamic binding, make it very attractive for Rapid Application Development, as well as for use as a scripting or glue language to connect existing components together. Python's simple, easy to learn syntax emphasizes readability and therefore reduces the cost of program maintenance. Python supports modules and packages, which encourages program modularity and code reuse. The Python interpreter and the extensive standard library are available in source or binary form without charge for all major platforms, and can be freely distributed.

![Alt text](https://s3.ap-southeast-1.amazonaws.com/images.deccanchronicle.com/dc-Cover-t10vpud7168ntjlqq6bmgo9440-20190125232807.Medi.jpeg "a title")

Often, programmers fall in love with Python because of the increased productivity it provides. Since there is no compilation step, the edit-test-debug cycle is incredibly fast. Debugging Python programs is easy: a bug or bad input will never cause a segmentation fault. Instead, when the interpreter discovers an error, it raises an exception. When the program doesn't catch the exception, the interpreter prints a stack trace. A source level debugger allows inspection of local and global variables, evaluation of arbitrary expressions, setting breakpoints, stepping through the code a line at a time, and so on. The debugger is written in Python itself, testifying to Python's introspective power. On the other hand, often the quickest way to debug a program is to add a few print statements to the source: the fast edit-test-debug cycle makes this simple approach very effective.


![Alt text]( https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSrn9YOGMV84gfRCa8nzd4Aw4PLcUk367QKvw&usqp=CAU "a title")





## Introduction

***A package is basically a directory with Python files and a file with the name __init__.py. This means that every directory inside of the Python path, which contains a file named __init__.py, will be treated as a package by Python. It's possible to put several modules into a Package.***

***Packages are a way of structuring Python’s module namespace by using "dotted module names". A.B stands for a submodule named B in a package named A. Two different packages like P1 and P2 can both have modules with the same name, let's say A, for example. The submodule A of the package P1 and the submodule A of the package P2 can be totally different. A package is imported like a "normal" module.***
![Alt text](https://www.python-course.eu/images/packages_300w.webp "a title")

## What are Packages and how are they useful?
***In python, we can define packages to structure different module namespaces, and then import them by using ‘dot module name’.
packages help a user to make the code divide into neat and efficient modules. Suppose we have a module named as school.period, it elects a submodule named period in a package named school.***
![Alt text](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSxnaok0ww5dLKnZUbSvIiO6XssjQW_UYtAjg&usqp=CAU "a title")


***Note: This is just one possible structure and it will vary from project to project and also depends on the requirement of the particular problem.When we import a package, Python searches through the sys.path directory to find the package subdirectory. Every directory must have a _init_.py named file or else python will not consider it as a package.***
![Alt text](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT4MEqchRm8lyzAEMvdFfo_Jmv51tRAx6Ey7g&usqp=CAU "a title")