---
layout: essay
type: essay
title: Our Savior Configuration Management
date: 2017-01-29
labels:
  - Software Engineering
  - Learning
  - Git
  - GitHub
  - Version Control
  - Unity
---
## The Saving Grace for Software Engineers
---
<img class="ui centered large image" src="../images/github.jpg">


After using Git for the past 2 years, I view configuration management as one of the most valuable tools in software development. I’ve used it for a wide range of projects in my undergraduate computer science career, ranging from web applications to virtual reality games for the HTC Vive. For any software engineer, the ability to allow easy collaboration amongst teams through configuration management tools like Git proves valuable as it dramatically increases the workflow for modern software development. 

## "Git and Unity is a nightmare!" ...well it could be...
---
<img class="ui centered image" src="../images/gitmeme.jpg">


Despite being one of the most effective tools for modern software development, I’ve had a problem with configuration management before, but it might have been a result of a lack of knowledge of the software. When using Git for group projects in the [Unity game engine](https://unity3d.com/), I was unaware of the complex setup required to have Git functioning smoothly. For example, I wasn't aware that I needed to update my .gitignore file with certain file extensions to help with Unity’s biggest collaboration problems of large binary files and scene merging.

When Git is not setup correctly as a version control for Unity, merging files when working on group project in Unity is unnecessarily difficult. This is a known problem in Unity due to the large amount of library and meta files that come with each Unity project and most developers advise others to use a different form of version control like Plastic SCM (another form of Distributed Version Control) or Perforce, another common form of version control used by notorious companies like Blizzard Entertainment. However, as described in [this guide](http://www.gamasutra.com/blogs/TimPettersen/20161206/286981/The_complete_guide_to_Unity__Git.php#Unity_settings_Git), Unity tries to address these issues by incorporating different options for the output of .meta files in the form of text instead of a binary format. This has helped with the problem of working with large binary files on Unity projects. I think the problems with Unity and Git will eventually subside due to the increasing popularity of the engine for teams. I think it’s great that Unity Technologies has started to invest in a more “noob friendly” form of version control through [Unity Collaborate.](https://unity3d.com/services/collaborate)

## Git and GitHub
---
Git and GitHub have proven to be the most popular form of version control today, but I think this is the result of the ease of use of a Distributed Version Control System (DVCS) compared to any other form of configuration management. GitHub is popular, but I prefer using git through command line because it’s more convenient as opposed to using a GUI like GitHub. Most programmers prefer the efficiency and precision of using git through command line and GUI's are sometimes difficult to use since they perform some git commands automatically without your authorization. 

In the end, configuration management is one of the most important tools for developing software. Without it, the efficiency and the rate in which software engineers will be able to collaborate in finding solutions will decrease. For future software engineers like me, I’m grateful to be living in the age in which version control is an easily accessible tool to use.
