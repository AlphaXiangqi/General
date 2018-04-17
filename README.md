# General

# Content
- [Major TODO](#major-todo)
- [Software Stack](#software-stack)
    - [Download](#download)
    - [Structure](#structure)
- [Softwares](#softwares)
    - [Docker](#docker)
- [Onilne Resources](#online-resources)
    - [Background Reading](#background-reading)
    - [Open-source Projects](#open-source-projects)
    - [Online Tutorials](#online-tutorials)
    - [Paper](#paper)
    - [Q & A](#question-and-answer)
    - [Coding Style](#coding-style)

## Major TODO
- [ ] Basic system --> [System](https://github.com/AlphaXiangqi/System)
- [ ] Literature review --> [Planning](https://github.com/AlphaXiangqi/Planning)
    - algorithm research
    - open-source code review
- [ ] Evaluate the performance of `AlphaXiangqi` with other open-source Xiangqi AI
- [ ] UI of the system --> [System](https://github.com/AlphaXiangqi/System)
- [ ] Home page

## Software Stack

### Download

#### Linux

```
$ cd ~ && mkdir AlphaXiangqi
$ cd AlphaXiangqi
$ git clone git@github.com:AlphaXiangqi/General.git
$ git clone git@github.com:AlphaXiangqi/System.git
$ git clone git@github.com:AlphaXiangqi/Planning.git
```

### Structure
As of April 16th, 2018

```
AlphaXiangqi
├── General
│   └── src
│       └── images
├── Planning
└── System
    └── GUI
```

- __General__: some "general" stuff
- __Planning__: focus on algorithm development
- __System__: focus on software development

## Softwares 

### Docker
- [Docker Docs](https://docs.docker.com/)

#### Arch Linux
```
# Docker installation
$ sudo pacman -S docker

# Run
$ systemctl start docker

# Check if works
$ sudo docker info
```

## Online Resources

### Background Reading

#### Basic Rules of Xiangqi
- [Xiangqi English Wiki](https://en.wikipedia.org/wiki/Xiangqi)
- [Chess Programming Wiki](https://chessprogramming.wikispaces.com/Chinese+Chess)

#### Common Algorithms
- _Artificial Intelligence A Modern Approach_, Chap. 5 - Adversarial Search
    - Min-Max Search
- Principal Variation Search
- Alpha-Beta Pruning

### Open-source projects
- [象棋巫师](https://github.com/xqbase)

### Online Tutorials
- [计算机博弈](http://www.xqbase.com/computer.htm)
- [博弈与算法实现](https://blog.csdn.net/fsdev/article/category/1085675)

### Paper
_To find interesting papers_

### Question and Answer
- [知乎：用Python写一个中国象棋AI?](https://www.zhihu.com/question/29472711/answer/45436565)
- [知乎：中国象棋AI实现](https://www.zhihu.com/question/28068014)

### Coding Style
- [Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html)
- [Python - PEP 8 Style Guide](https://www.python.org/dev/peps/pep-0008/)

