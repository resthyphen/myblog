---
layout: post
title: "How to install package for python"
published: true
github_comments_issueid: "3"
tags:
---

Python is easy to use and extend.There are a varities of package available for python that can be very versatile.It make python became so powerful.

You can go to <a href="https://pypi.org">pypi(Python Package Index)</a> to Find, install and publish Python packages which you like.
There are two ways mostly often be used to install the package for python: 

## 1. setup.py
go to the dicrectory where the package(format: .zip, .tar, ...etc) in, extract it, after  you will see the file is setup.py that use it to 
install. command as follow:
```python
python setup.py install
```

## 2. Using the pip
pip is already installed if you are using <span style = "color:rgb(128, 128, 255)">Python 2 >=2.7.9</span> or <span style = "color:rgb(128, 128, 255)">Python 3 >=3.4</span> downloaded from python.org. If not you need to download it: <a href="https://pypi.org/project/pip/">link</a> first you need to install the <a href="https://pip.pypa.io/en/stable/installing/">get-pip.py</a>
after go to path: <span style = "color: #ffcc00">cd ./python\*/scritps/</span> or you can add the path to your environment, then run as following:
### install: 
```python
pip install ./yourpackage
(e.g.  pip install ./Hello.zip)
```
### uninstall:
```python
pip uninstall ./yourpackage
(e.g. pip uninstall hello)
```
Using the pip you don't need to extract the file and install as <span style = "color: #ffcc00">1</span>. Install directly that is more convenient.

