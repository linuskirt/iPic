# [BitTC_*help*](https://github.com/linuskirt/BitTC)
A Help files repository for BitTC Program.

[![Author](https://img.shields.io/badge/Power%20by-BITHydro-orange.svg?style=flat&amp;amp;colorA=E1523D&amp;amp;colorB=007D8A)](https://github.com/linuskirt)
[![Version](https://img.shields.io/badge/release-v0.1-blue&style=plastic)](https://github.com/linuskirt/BitTC/releases/tag/tcAtorusV0.1)
[![Copyright](https://img.shields.io/badge/Copyright-BIT-red.svg?style=flat&amp;amp;colorA=E1523D&amp;amp;colorB=007D8A)](https://github.com/orgs/BITHydro/teams/bittc)
[![Support](https://img.shields.io/badge/Support-VRC&ROMAC-success?logo=BIT&style=?style=for-the-badge&logo=appveyor)](https://www.bit.edu.cn/)

## **<font color=blue size=5>Ⅰ</font>** Overview

  BitTC is an Intargeted Design Platform and Tool Package for design, simulation and optimization for Hydodynamic Turbomachinery. It is codeed by [BitHydro](https://github.com/BITHydro), a research team from School of Mechanical Engineering, Beijing Institute of Technolgoy(BIT), and it's mainly powered via [MATLAB](https://www.mathworks.com).

<div align=center><img src="_Help/help/img/HydroLogo.jpg" width="400" alt="Logo of BitHydro Team."/>
</div>

## **<font color=blue size=5>Ⅱ</font>** What's BitTC?

BitTC consists of 6 parts of function modulars/packages, including:

 - [1. tcADrawTool](https://central.github.com/deployments/desktop/desktop/latest/darwin): a tiny tool to transfer the blade shape into Unfolder blade view in 2D Drwding form, also for data for tcATorus and tcBlading input.
 - [2. tcATorus](https://github.com/linuskirt/BitTC/tree/tcATorus): a helpful tool to design the circle/torus of torque converter, including round type, line-shape type, curved-shape, narrowed-circle shape type and also costomed shape type. Also, it would creat both the shround profile and hub profile of pump, turbine and stator.
 - [3. tcBladingCa](https://central.github.com/deployments/desktop/desktop/latest/win32?format=msi): a powerful tool to creat the 3D shaped and casting/stamping type blade for pump, turbine and stator based on Bezier Curve.
 - [4. tcBladingSt](https://central.github.com/deployments/desktop/desktop/latest/darwin): a powerful tool to creat the 3D shaped and stamping type blade for pump, turbine and stator based on Bezier Surface.
 - [5. tcBLDTool](https://central.github.com/deployments/desktop/desktop/latest/win32): a useful tool to design the blade load distribution(BLD) result, and it can also be helpful to transfer the performance character into the BLD results.
 - [6. tcIDMTool](https://central.github.com/deployments/desktop/desktop/latest/win32?format=msi): a stamping blade design tool based on Inverse design method(IDM), it's also an optimal-blade fast design tool.

**By using those tools, we can easy build up the blade/cascade system of hydrodynamic turbomachinery**.

**NOTE**: This Softwares Package is still developing.

## **<font color=blue size=5>Ⅲ</font>** Program Developing Info  

Here is the basic program file info.  

**Program code basic info(English Verison):**
| Type：      | Documents     | Doc ID：            | BitTC             |
| ----------- | :------------ | ------------------- | ----------------- |
| Doc Status: | [√] Draft     | Current Version：   | V0.1              |
|             | [ ] Published | Author：            | Cheng Liu & Linus |
|             | [ ] Revised   | Reviewer：          | Wei Wei           |
| Start Date: | 2020-02-02    | Pridicted End Date: | 2020-12-27        |

**Code/Software Version & History:**
| Version： | Author/Reviser | Date         | Reviewer  | checker |
| --------- | -------------- | ------------ | --------- | ------- |
| V0.1      | Linus          | 2020-02-02   | Cheng Liu | Wei Wei |
|           | Linus          | *2020-04-02* |           |         |
|           |                |              |           |         |

## **<font color=blue size=5>Ⅳ</font>** Collaborate with *BitTC* Program

Note that this program is a private program which only BitHydro member can get access to. After recieve approval by [Linus](mailto:linuskirt@live.cn), You can get access to [BitTC](https://github.com/linuskirt/BitTC), and clone it to your own computer or repository, since the Matlab code rely on the file path, you'd better set the *BitTC* reponsity to your filepath: `c:\BitTC`to run it proporbly.
*To get start, you should read the following document first to understand the running/coding process of this program code:*
    
### **<font color=blue>4.1</font>** Start to  learn & use Git

[Git](https://en.wikipedia.org/wiki/Git) is a distributed version-control system for tracking changes in source code during software development, it helps to control the order and development for different function models and variety of versions of BitTC program code. To start with, a basic tutor should be read first:

--- 
- [Git Tutorial](https://git-scm.com/docs/gittutorial): A tutorial introduction to Git;
- [Git Pro *2nd Edition (2014)*](https://git-scm.com/book/en/v2): an official document to learn Git;
- [一个小时学会Git](https://www.cnblogs.com/best/p/7474442.html): a fast turtial for Git learning.
---
Practice makes perfect. Search Online if meet the problem. Also, we use Git Client to aided to use Git much more convenient after we finish reading the basic knowledge of Git from above documents.

### **<font color=blue>4.2</font>** GitHub help us to accelerate the ordered process

This project push all the code to a GitHub repository of Linus priviate account at present, after being finished, we would put it into the [BITHydro group](https://github.com/BITHydro/BitTC). As a result, we had to know the basic knowledge for [GitHub](https://github.com/desktop/desktop/blob/development/CODE_OF_CONDUCT.md) interactions relating to the Git project.

[GitHub](https://en.wikipedia.org/wiki/GitHub) is a global company that provides hosting for software development version control using Git.  It offers all of the distributed version control and source code management(SCM) functionality of Git as well as adding its own features such as free unlimited repositories, bug tracking, feature requests, task management, and wikis for every project. As for the desktop clicent for Git, we have many choices such as [SoruceTree](https://www.sourcetreeapp.com/), [GitHub Desktop](https://desktop.github.com/) and so on, here we recommond the SourceTree since it is very easy to use and quitely interication-friendly. As for the tutorial for the software operation, here are some for looking through, but my suggestion is to use it, solve the problems once upon you meet them:

--- 
- [SourceTree 使用教程*](https://confluence.atlassian.com/get-started-with-sourcetree/get-started-with-sourcetree-847359026.html): an official but simple document to start SourceTree.
- [SourceTree 使用教程*](https://www.jianshu.com/p/6b5ed581b158): a fast turtial for Git learning via SourceTree.  
---
*Practice makes perfect. Search Online if meet the problem.*

## **<font color=blue size=5>Ⅴ</font>** The known issues/bug but haven't fixed yet:

If nobody has responded to your issue in a few days, you're welcome to respond to it with a friendly ping in the issue. Please do not respond more than a second time if nobody has responded. The GitHub Desktop maintainers are constrained in time and resources, and diagnosing individual configurations can be difficult and time consuming. While we'll try to at least get you pointed in the right direction, we can't guarantee we'll be able to dig too deeply into any one person's issue.


## **<font color=blue size=5>Ⅵ</font>** More Resources

### **<font color=blue size=4>* License *</font>** 

*[BIT](LICENSE)* : The BIT license grant is not for GitHub's trademarks, which include the logo
designs. GitHub reserves all trademark and copyright rights in and to all GitHub® trademarks.

### **<font color=blue size=4>* Ohter *</font>** 

TBD...# tcpic
