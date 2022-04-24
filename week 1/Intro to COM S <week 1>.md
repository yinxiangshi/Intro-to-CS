## Intro to COM S: Week 1

> Programming is like sex: one mistake, a lifetime of maintenance – Michael Sinz

#### Preface

This series of articles is a learning path guide notes, and will not go into the specific knowledge content, please read the provided materials carefully in order, all you need to learn is in the materials. Hope you enjoy :)

#### Reading suggestions

You don’t have to learn all the tools below, just look back when you available.

#### <Section one, tools that you need to know at beginning>

##### VPN:

As we all know, China has magic to keep us from accessing some contents, so we need to learn to defeat magic with magic.

So what is VPN? In short, a VPN is a tool that allows us to break network blockages, in terms of terminology, A **virtual private network** (**VPN**) extends a [private network](https://en.wikipedia.org/wiki/Private_network) across a public network and enables users to send and receive data across shared or public networks as if their computing devices were directly connected to the private network.[https://en.wikipedia.org/wiki/Virtual_private_network] From this definition, Chinese internet is a huge **PRIVATE NETWORK**.

###### Suggestion tools:

**Clash**: this a famous tool to cross the GFW(Great Fire Wall), it support almost all the devices, and easy to use. Here is the download link below:

[Github Repo](https://github.com/Dreamacro/clash/releases), [Mac version of clash](https://github.com/yichengchen/clashX/releases), [Windows version of clash](https://github.com/Fndroid/clash_for_windows_pkg/releases), [Android version of clash](https://play.google.com/store/apps/details?id=com.github.kr328.clash&hl=zh&gl=US)

If you are ios users, I suggest to use [shadowrocket](https://apps.apple.com/us/app/shadowrocket/id932747118). 

I highly recommend reading the readme file of the repo to learn how to use it, but of course, considering the knowledge level of beginners, there is also a Chinese tutorial here: [for clash](https://mitsea.medium.com/clash-%E5%B8%B8%E7%94%A8%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B-%E7%AE%80%E6%98%93%E7%89%88-c77aeb2a10c), [for shdowroacket](https://lihaixin.gitbooks.io/shadowsocks/content/4-ios-settings.html).

However, only tool is not enough, you also need a server to connect in order to cross the GFW.

If you want to buy a vpn service, probably you could look at [Gacloud](https://www.gacloudltd.org/), [BoomCloud](https://www.boomssv.com/), [泡芙云](https://www.paofu.cloud/auth/register).

**Please pay attention to identify the authenticity of these service providers, or ask friends to recommend a reliable one, all VPN service providers have the risk of debt escape.**

###### Git

Git is the most powerful tool for version control, while version control is important to SDE work. So at the beginning, it is needed to learn how to use Git.

Here is the [simple guide of Git.](https://rogerdudler.github.io/git-guide/)

You are required to submit summary by pull request on [Github](github.com), I suggest to use command line to commit.

##### Linux

Linux is the most normal operating system for COM S students. However, learning how to use Linux is not that easy. So I don’t think you have to use Linux at beginning. However, Linux is more convenient than Windows. **Window is the worst system ever.** 

Here is some [basic Linux knowledge](https://ubuntu.com/tutorials/command-line-for-beginners#1-overview). I suggest you use Linux as your main operating system if you can. Terminal is better than GUI(Graph user interface). 

Suggest Linux system: [Ubuntu](https://ubuntu.com/), [Manjaro](https://manjaro.org/)， [WSL(Windows Subsystem for Linux)](https://segmentfault.com/a/1190000022987318)

Install guide: Official guide of [Ubuntu](https://ubuntu.com/tutorials/install-ubuntu-desktop#1-overview), [WSL](https://segmentfault.com/a/1190000022987318), [Ubuntu parallel install guide on Windows](https://zhuanlan.zhihu.com/p/101307629), [Manjaro](https://zhuanlan.zhihu.com/p/376787855)

##### IDE

An **integrated development environment** (**IDE**) is a [software application](https://en.wikipedia.org/wiki/Application_software) that provides comprehensive facilities to [computer programmers](https://en.wikipedia.org/wiki/Computer_programmer) for [software development](https://en.wikipedia.org/wiki/Software_development). An IDE normally consists of at least a [source code editor](https://en.wikipedia.org/wiki/Source_code_editor), [build automation](https://en.wikipedia.org/wiki/Build_automation) tools and a [debugger](https://en.wikipedia.org/wiki/Debugger). Some IDEs, such as [NetBeans](https://en.wikipedia.org/wiki/NetBeans) and [Eclipse](https://en.wikipedia.org/wiki/Eclipse_(software)), contain the necessary [compiler](https://en.wikipedia.org/wiki/Compiler), [interpreter](https://en.wikipedia.org/wiki/Interpreter_(computing)), or both; others, such as [SharpDevelop](https://en.wikipedia.org/wiki/SharpDevelop) and [Lazarus](https://en.wikipedia.org/wiki/Lazarus_(IDE)), do not. 

The boundary between an IDE and other parts of the broader software development environment is not well-defined; sometimes a [version control system](https://en.wikipedia.org/wiki/Version_control_system) or various tools to simplify the construction of a [graphical user interface](https://en.wikipedia.org/wiki/Graphical_user_interface) (GUI) are integrated. Many modern IDEs also have a [class browser](https://en.wikipedia.org/wiki/Class_browser), an [object browser](https://en.wikipedia.org/wiki/Object_browser), and a [class hierarchy diagram](https://en.wikipedia.org/wiki/Class_diagram) for use in [object-oriented software development](https://en.wikipedia.org/wiki/Object-oriented_programming).

IDE suggestions:

For Java: [IntellJ IDEA](https://www.jetbrains.com/zh-cn/idea/)

For C/C++: [CLion](https://www.jetbrains.com/zh-cn/clion/), [DevCpp](https://www.bloodshed.net/)(Why DevCpp? I think DevCpp is beginner friendly (At least I used this for about 3 years))

However, I have to admit that VScode is the most convenient and powerful IDE for every language. But in my prespective, to configure VScode is complex for beginners. I just like Jetbrains’ IDE :)

Here is some resources that might helpful for you to handle on an IDE:

[Official IDEA guide](https://www.jetbrains.com/help/idea/getting-started.html), [Third party IDEA guide](https://guobinhit.github.io/intellij-idea-tutorial/), [Official CLion guide](https://www.jetbrains.com/help/clion/clion-quick-start-guide.html), [Third party CLion guide](https://www.cnblogs.com/bluestorm/p/12316676.html), [DevCpp guide](https://www.cplusplus.com/doc/tutorial/introduction/devcpp/)

Also, [Simple VScode guide](https://blog.csdn.net/qq_36556893/article/details/90021433)

Tips: Jetbrians IDE are free for students. If you have an edu mail, just reg [here](https://www.jetbrains.com/zh-cn/community/education/#students) and then you can get ALL FREE IDE!

If you don’t have tho, just use community version is ok.

#### Learn the principles of CS

At the beginning, I want to share some self-experience about learning principles.

**Search ability:** There is a famous joke that said most programmers are face to GOOGLE coding, that’s true tho. So develop the ability of how to search useful info is important. As you can see, although I provide many guides for you to read and learn,  there are still amount of unknown info that need you to search and know. The first step to develop the search ability is that **make your question a question**. Check this [repo](https://github.com/ryanhanwu/How-To-Ask-Questions-The-Smart-Way/blob/main/README-zh_CN.md) to learn how to ask a question. Second step is that use English to search, it is important that English resources are more abundant than Chinese resources. **Don’t believe that English is useless for learning program, that’s bullshit.** Thrid step is that read official docs in a first order, don’t always trust the knowledge from others’ mouth instead of Official docs.

**Do more:** Always start trying than just thinking. Some students told me that they are worried about whether they can learn CS well. However, how can you know that even if you havn’t started to do that? So always remeber that try it yourself and then ask.

**Develop yourself:** I think this is the most important principle for CS. Here I want to share my own story. I was started learning CS for about 7 years ago. At that time, I also don’t know how to do well like your guys, then I found that the special ability of myself is that develop myself. I learned Android by developing lua apps on Android, flash my devices quiet often to try different systems. Everytime when I meet a problem, I will try to solve it myself at first, no matter use resources from google, from other docs. Aftter solve the problems, I will think the reason of this problem, that is,  **develop yourself from problems**.

**So please stay curious to explore what you don't know**.

#### <Section two, beginning courses>

We will begin at UCB CS61B, I suggest that no matter how far you have studied about CS, it is also useful to re-learn data structure. Please stay humble.

For first week, we will learn some basic java knowledge and finish the labs. The lecture you have to read is below:

[Intro, Hello World Java](https://inst.eecs.berkeley.edu/~cs61b/sp22/materials/lectures/lect1.pdf)

[A Little Programming](https://en.wikipedia.org/wiki/Integrated_development_environment)

[Values and Containers](https://inst.eecs.berkeley.edu/~cs61b/sp22/materials/lectures/lect3.pdf)

[Simple Pointer Manipulation](https://inst.eecs.berkeley.edu/~cs61b/sp22/materials/lectures/lect4.pdf)

[Arrays](https://inst.eecs.berkeley.edu/~cs61b/sp22/materials/lectures/lect4.pdf)

Labs:

[Lab 1: Intro to Java & Git](https://inst.eecs.berkeley.edu/~cs61b/sp22/materials/lab/lab1/index.html)

Homeworks:

[HW0](https://inst.eecs.berkeley.edu/~cs61b/sp22/materials/hw/hw0/index.html)

[HW1](https://inst.eecs.berkeley.edu/~cs61b/sp22/materials/hw/hw1/index.html)

Tips: you don’t need to submit your hw on github, just write a simple summary.

Please remeber to finish the summary at the end of this week:)

