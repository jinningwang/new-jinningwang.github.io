---
layout: post
title: Novelty in Science
date: 2024-12-12 15:20:00
description: A guide for reviewers
tags: [repost, opinion, research, novelty, CHN Available]
categories: blog
thumbnail:
featured: false
toc:
  sidebar: false
---

By Michael J. Black \| Published January 30, 2022

Reviewers have strong ideas about what makes a paper acceptable in top conferences like CVPR. They know that getting into such conferences is hard and that getting a paper in is prestigious. So, the papers that get in must be really special. This is true, but what makes a paper special? A key focus of many reviewers is novelty. But what is novelty in science?

I see reviewers regularly mistake complexity, difficulty, and technicality for novelty. In science reviewing, novelty seems to imply these things. We might be better served by removing the word "novelty" from the review instructions and replacing it with beauty.

Beauty removes the notions of "technical" and "complex" and gets more to the heart of scientific novelty.  A painting can be beautiful even if it is simple and the technical complexity is low. So can a paper. A little squiggle of paint by Picasso can be as beautiful as an intricate painting by Rembrandt.

Keeping beauty in mind, let's look at some common reviewer misunderstandings about novelty.

## Novelty as complexity

The simplicity of an idea is often confused with a lack of novelty when exactly the opposite is often true. A common review critique is

> The idea is very simple. It just changes one term in the loss and everything else is the same as prior work.

If nobody thought to change that one term, then it is ipso facto novel. The inventive insight is to realize that a small change could have a big effect and to formulate the new loss.

Such reviews lead my students to say that we should make an idea appear more complex so that reviewers will find it of higher value. I value simplicity over unnecessary complexity; the simpler the better. Taking an existing network and replacing one thing is better science than concocting a whole new network just to make it look more complex.

## Novelty as difficulty

It's hard to get a paper into a top conference, therefore reviewers often feel that the ideas and technical details must be difficult. The authors have to shed blood, sweat, and tears to deserve a paper. Inexperienced reviewers, in particular, like to see that the authors have really worked hard.

Formulating a simple idea means stripping away the unnecessary to reveal the core of something. This is one of the most useful things that a scientist can do.

A simple idea can be important. But it can also be trivial. This is where reviewers struggle. A trivial idea is an unimportant idea. If a paper has a simple idea that works better than the state of the art, then it is most likely not trivial. The authors are onto something and the field will be interested.

## Novelty as surprise

Novelty and surprise are closely related. A novel idea is a surprising one by definition -- it's one that nobody in the field thought of. But there is a flip side to this as surprise is a fleeting emotion. If you hear a good idea, there is a moment of surprise and then, the better it is, the more obvious it may seem. A common review:

> The idea is obvious because the authors just combined two well known ideas.

Obvious is the opposite of novelty. So, if an idea is obvious after you've heard it, reviewers quickly assume it isn't novel. The novelty, however, must be evaluated **_before_** the idea existed. The inventive novelty was to have the idea in the first place. If it is easy to explain and obvious in hindsight, this in no way diminishes the creativity (and novelty) of the idea.

## Novelty as technical novelty

The most common misconception of reviewers is that novelty pertains to technical details. Novelty (and value) come in many forms in papers. A new dataset can be novel if it does something no other dataset has done, even if all the methods used to generate the dataset are well known. A new use of an old method can be novel if nobody ever thought to use it this way. Replacing a complex algorithm with a simple one provides insight.

Novelty reveals itself in as many ways as beauty. Before critiquing a paper for a lack to technical novelty ask yourself if the true novelty lies elsewhere.

# Novelty as usefulness or value

Not all novel ideas are useful. Just the property of being new does not connote value. We want new ideas that lead us somewhere. Here, reviewers need to be very careful. It's very hard to know where a new idea will take the field because any predictions that we make are based on the field as it is today.

A common review I get is

> The authors describe a new method but I don't know why anyone needs this.

Lack of utility is indeed an issue but it is very hard to assess with a new idea. Reviewers should be careful here and aware that we all have limited imagination.

# A personal note

My early career was built on seeing and formalizing connections between two established fields: robust statistics and Markov random fields. The novelty arose from the fact that nobody had put these ideas together before. It turned out to be a fertile space with many surprising connections that led to new theory. Fortunately, these connections also turned out to be valuable, resulting in practical algorithms that were state of the art.

With hindsight, the connection between robust statistics and outliers in computer vision seems obvious. Today, the use of robust estimators in vision is the norm and seems no more novel than breathing air. But to see the connections for the first time, before others saw them, was like breathing for the first time.

There is little in life more exciting than that spark of realization in science when you glimpse a new way of seeing. You feel as if you were the first to stand on a mountain peak. You are seeing the world for a moment the way nobody before you has ever seen it. This is novelty and it happens in an instant but is enabled by all of one's experience.

The resulting paper embodies the translation of the idea into code, experiments, and text. In this translation, the beauty of the spark may be only dimly glimpsed. My request of reviewers is to try to imagine the darkness before the spark.

---

**Original Post: [Novelty in Science][link]**

**_Copyright belongs to the original author._**

<hr style="border: 2px solid;">

# 科学中的创新性

Michael J. Black \| Published 2022年1月30日

审稿人对顶级会议（如CVPR）接收论文的标准有着强烈的看法。他们知道，进入这样的会议非常困难，能够发表论文是一件很有声望的事情。因此，被接收的论文必须非常特别。这是事实，但究竟是什么让一篇论文显得特别呢？许多审稿人的一个核心关注点是“创新性”。但科学中的“创新性”到底是什么？

我经常看到审稿人把复杂性、难度和技术性误认为是创新性。在科学评审中，创新性似乎隐含着这些特质。或许我们应该从评审指南中移除“创新性”这个词，并用“美妙”替代。

美感排除了‘技术性’和‘复杂性’的概念，直击科学创新的核心。一幅画，即使简单且技术复杂性低，也可以很美。同样地，一篇论文也可以如此。毕加索的一小条涂鸦可以和伦勃朗的一幅复杂画作一样美。

以美感为出发点，让我们来看看审稿人对创新性的常见误解。

## 将创新性等同于复杂性

人们常常将一个想法的简单性误认为缺乏创新性，而事实恰恰相反。一条常见的评审意见是：

> 这个想法非常简单。它只是改变了损失函数中的一个项，其余部分和已有工作一样。

如果没人想到要改变这个项，那它本身就具有创新性。创新性的洞察力在于认识到一个小的改变可能带来大的影响，并能将其转化为新的损失函数。

这样的评审会导致我的学生认为，必须让想法显得更复杂，审稿人才会觉得更有价值。但我认为，简单比不必要的复杂更有价值；越简单越好。基于现有网络并替换某些部分，比为了显得复杂而设计一个全新网络更符合科学精神。

## 将创新性等同于难度

由于很难在顶级会议上发表论文，审稿人通常认为想法和技术细节必须是困难的。作者需要付出“鲜血、汗水和泪水”才能配得上一篇论文。特别是缺乏经验的审稿人，更希望看到作者经历了艰苦的努力。

提出一个简单的想法意味着剔除不必要的部分以揭示核心。这是科学家最有用的能力之一。

一个简单的想法可能是重要的，但也可能是琐碎的。审稿人在这里会感到挣扎。琐碎的想法是不重要的想法。如果一篇论文提出了一个简单但优于现有技术的想法，那它很可能并不琐碎。作者触及了一些有意义的东西，同领域的人会感兴趣。

## 将创新性等同于惊喜

创新性和惊喜密切相关。一个创新的想法定义上是令人惊讶的——它是领域中没人想到的。然而，惊喜是一种短暂的情绪。如果你听到一个好点子，最初可能会感到惊讶，但越是好的点子，可能越显得显而易见。常见的评审意见是：

> 这个想法显而易见，因为作者只是结合了两个已知的想法。

显而易见是创新性的对立面。因此，如果一个想法在你**听到后**显得显而易见，审稿人很快会认为它不具创新性。然而，创新性应该在想法出现之前被评估。创新的关键是首先提出这个想法。如果一个想法很容易解释，且事后看起来显而易见，这丝毫不会减弱其创造性（和创新性）。

## 将创新性等同于技术创新

审稿人最常见的误解是认为创新性与技术细节相关。一篇论文的创新性（及价值）可能以多种形式展现。例如，一个新数据集如果完成了其他数据集未能实现的目标，即便其生成方法是众所周知的，也可以是创新的。一个旧方法的新用途，如果以前从未有人这样使用，也可以是创新的。用简单算法替代复杂算法，能够提供新的见解。

创新性可以以各种方式展现，就像美感一样。在批评一篇论文缺乏技术创新之前，问问自己真正的创新性是否体现在其他地方。

## 将创新性等同于实用性或价值

并非所有的创新想法都是有用的。仅仅是新颖本身并不意味着有价值。我们需要能带来新方向的新想法。在这里，审稿人需要非常小心。判断一个新想法会将领域带向何处非常困难，因为我们所有的预测都是基于当前领域的状态。

我常收到的一条评审意见是：

> 作者提出了一种新方法，但我不知道为什么需要这个。

缺乏实用性确实是个问题，但很难对一个新想法进行评估。审稿人在这里需要小心并意识到，我们的想象力是有限的。

## 个人感悟

我的早期职业生涯是基于查看并形式化两个既有领域之间的联系：稳健统计和马尔可夫随机场。这种创新性来源于之前没有人将这些想法结合起来的事实。这是一个充满意外联系的肥沃领域，最终带来了新的理论。这些联系最终也证明是有价值的，产生了实用的、达到业界领先水平的算法。

回头看，稳健统计与计算机视觉中离群值之间的联系似乎显而易见。今天，在视觉领域中使用稳健估计器已是常态，看起来与呼吸空气一样普通。然而，最初看到这些联系的时候，是在别人看到之前，就像第一次呼吸新鲜空气。

科学中，没有什么比新发现的那一刻更激动人心了。当你发现一种新的视角时，你仿佛是第一个站在山顶上俯瞰世界的人。那一刻，你看到的世界与以往从未被人见过的视角相同。这就是创新性，它发生在一瞬间，但是由所有的经验所促成。

最终的论文体现了将这一想法转化为代码、实验和文字的过程。在这个转化过程中，灵感的美感可能只能隐约可见。我对审稿人的请求是：试着想象火花出现前的黑暗。

---

**原文链接: [Novelty in Science][link]**

**_版权属于原作者，本翻译仅供学习用途。_**

[link]: https://perceiving-systems.blog/en/news/novelty-in-science
