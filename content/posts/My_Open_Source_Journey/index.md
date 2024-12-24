---
title: "First Steps in Open Source"
date: 2022-11-15T14:39:56+05:30
draft: false
summary: "My Open Source Adventure: Challenges, Triumphs, and Lessons Learned"
description: ""
toc: true
readTime: true
autonumber: false
math: true
tags: []
showTags: false
hideBackToTop: false
---


**So how did I start Open-Source and how it changed my development journey? This post mentions my reasons to start contributing to OSS repos and learn more about different ML Open Source communities in the world! Also this post contains some advice for people wanting to undertake this journey as well.**

<br><br>


## How it Started... 
Somewhere in December last year, I was bored. I was tired of giving hackathons, not because of coding but because of similar repetitive tasks, like making an app or website or some other consumer-facing tech, which I will never bring to production. Also, I wanted to learn something new apart from the same boilerplate stuff.

So the next step was to transition from the usual hackathons to something new, like having more problems to solve but also having some flexibility regarding the projects and the type of task I wanted to work on. I also started to see some great videos about open source on YouTube, which inspired me to build and study open-source maintained projects; I want to learn more about development and how to be a better programmer. This led me to read some interesting open source codebases, initially something like Hugo, as I built my last blog website with it(now scrapped for this theme). So it could be easy, or so I thought. But I was wrong. 

To begin with, I needed to be more comfortable working with the programming language. Thus, Python was the obvious choice to start with Open Source instead of Go, where I needed more experience. So I quickly shifted to python based projects. This does not mean you can begin OSS with only Python or contribute to projects with only the language you know. Still, it's just to make the beginning in small steps that you can take without much fatigue instead of adding a lot of complexity and not being able to achieve anything later.

Having used Python for most of the development in my life (i.e., one year at a time), I felt really comfortable around PyTorch framework libraries like torch-vision, PyTorch-tutorials, and PyTorch-Ignite. I had some knowledge of the API because of the projects that I built. This led to work and contributed to the issues (precisely `good first issues`) related to the CI and tutorials at first in PyTorch-Ignite.


## Completing My First Issues and Features 
So my first PR in `PyTorch-Ignite` is [this](https://github.com/pytorch/ignite/pull/2786), a CI issue that took me about a day to understand and solve. Before then, I was unaware of GitHub Actions or how the action variables work. To understand what I did there, read the original issue. Now, the best thing is that if I look at this issue, it's probably something I can solve in about 10 minutes. This is the power of Open Source. At first, you don't know anything about software and how to make any changes, but little by little, you learn a lot of stuff that can be applied in different ways as you contribute more. 

The best way to start Open Source is to begin with a well-maintained project you use frequently and can rely upon in the long run. This will help you appreciate the API and the features and ask and answer questions in the community through the IRC channel.


## Moving Beyond Simple Contributions 
This part is tricky. While it's easy to solve minor bug fixes and issues, it's only sometimes precious to the project. It may hinder your learning in the long run. There are ways to help you keep learning after a certain point.

You can start moving to more advanced issues after doing something simple like adding a feature (which can be difficult for non-web dev projects) or some UI or other elements that can be better. This constructively helps the projects and helps the community appreciate the value of your contribution. The cons of the approach is that you may need to learn a lot before solving any 'advanced' issues as development takes a good number of hit-and-trials and experience to remember. 

I believe the better approach would be to build your own project over the top of the project you are contributing to. It can be a simple tutorial, a blog post, or something like your own package. This will force you to learn a lot quickly, and you can also pitch ideas to the community and take their help with your own ideas. By completing something like this, you have advanced your resume and built some excellent skills along the way. This will help you stay relevant in the project and gain some 'recognition' among the community members. Overall, it will be a much better learning experience for you and the community.


## A Side Note 
While I appreciate you reading this article, please follow some dos and don'ts while contributing to open-source projects and the project policies. First, don't disrespect anyone in the community, including the project maintainers. Open-source is challenging and requires immense time commitments from the maintainers and the community members' busy schedules. So, you must remain invested in the project and act friendly towards new contributors. Do not try to work condescending to anyone just because they don't understand something straightforward. The critical thing to note is that they are trying to spend some time learning something and building it for the benefit of others instead of wasting it on dozens of things that people do from time to time.

Also, I would advise you to start working on an OSS project by reading the `CONTRIBUTING.md` file and following the project guidelines correctly to save everyone's time. You should also read and understand each change you make (instead of simply copying it from Stackoverflow or chatGPT) in the codebase, and you should be able to justify it if asked. Most community members and maintainers want this from you, making the codebase easy to understand and maintain a standard. Also, avoid repeating mistakes and ask questions more often to understand the changes and the codebase.


## In the end 
Contributing to and maintaining open-source software projects can be a very fulfilling and beneficial activity and can lead to much more growth for the individual and community than what people expect. I believe that open source is the most helpful way of creating and distributing software to society.


## References to Read 
1. https://pytorch-ignite.ai
2. https://pytorch.org/
3. https://gohugo.io


***[Edited 23 December 2024]***
