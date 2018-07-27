---
layout: post
title: this.is.data.science
subtitle: It's about running things
category: data
tags: [data science, culture]
author: Bastian Kronenbitter
header-img: "images/home-bg.jpg"
---

*Hello world*

This is an introductory post into our culture of building and running things.
If you are looking for details of our technical inftrastructure, this is not the post you are looking for. Please come back later. There will be enough in store for you.

But as Holger [already pointed out](https://adello.github.io/Hello-World/), culture is a necessary requirement for achieving our goals, although not a sufficient one. And this is not restricted to the culture of a productive office environment, the culture of leadership, or the culture of sharing and caring. It also includes the culture of building and running things. And this is what I want to write about.

You might be surprised to find this kind of post under the tag of data science. Often enough data science is restricted to the task of generating nice graphs or producing the best machine learning models possible. But this is not how we understand data science at Adello.
We are also doing that, but in the end it is only a certain fraction of our day to day work. The best models in the world don't have any value if they end up on a shelf.

To illustrate our approach, let me show you the life cycle of a data science project:
1. *Discussion and value estimation*: We sit down together with all other departements of the company and discuss the potential of any potential project. And that is the end of a lot of ideas. From our experience, there are actually not too much applications for machine learning or even deep learning methods with a clear value. They are out there. But it is hard work to identify them.
2. *Planning and feasability*: The data science team sits together and discusses the feasability of a project. What do we need to know to estimate the potential? Where might be pitfalls? What are the right methods to use? How do we measure success?
3. *Study and algorithmic development*: We sit down in front of our Zeppelin notebook/Jupyter notebook/IDE/tool of your choice and start digging into the data. We learn about the data, test and develop algorithms, and optimize for a specific outcome.
4. *Engineering*: We take our data science hat off and put on the engineering hat. We take the outcome of the upper step and produce and actual piece of software out of it. In our days, we often use (py)Spark for that. But it could also be a Hive script, a Java program, or something else. In that stage we are working with the tools of software engineering, thus automated testing, version control, continous delivery...
5. *Running*: We deploy. We run. We monitor. We eat our own dog food. Often this is annoying and time-consuming. But nothing motivates you more to care about software quality than knowing you will be the one suffering from bad software. This is nothing revolutionary. Everybody knows this principle as DevOps. For us it works, even if that means spending a significant amount of time running things. It's time well invested.

Well, that's it. Nothing spectacular. But I think, living the spirit of DevOps and understanding data science as an integral part of engineering instead of an add-on is worth mentioning (ask our latest hires...).

Over the next couple of weeks and months, we plan to give you insights into some of our components and projects. Some of them will be machine learning applications, some of them will be methods of running things. We only see value in the combination of both.