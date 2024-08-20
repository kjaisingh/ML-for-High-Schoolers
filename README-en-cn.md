# A guide for High School students to learning Machine Learning and Artificial Intelligence

# 高中生学习机器学习和人工智能的指南

<a href="./README.md"><img alt="English" src="https://img.shields.io/badge/English-lightgrey"></a>
<a href="./README-en-cn.md"><img alt="中文" src="https://img.shields.io/badge/中文-lightgrey"></a>

Being a high schooler myself and having studied Machine Learning and Artificial Intelligence for a year now, I believe that there fails to exist a learning path in this field **for High School students**. This is my attempt to create one.

作为一名高中生，我已经学习了一年的机器学习和人工智能，我相信在这一领域**没有一个适合高中生的学习途径**。这篇文章是我的一个尝试。

Over the past few months, I've tried to spend a couple of hours every day understanding this field, be it watching Youtube videos or undertaking projects. I've been guided by older peers who've had far more experience than me, and now feel that I have ample experience to share my insights.

在过去的几个月里，我试图每天花几个小时来了解这个领域，无论是看 Youtube 视频还是参与项目。我得到了比我经验多得多的比我大的技术大佬的指导，现在觉得自己有足够的经验来分享我的见解。

All the information that I have compiled in this guide is intended for high schoolers wishing to excel in this up and coming field. It is  intended to be followed chronologically, and unlike most guides/learning paths that I've come across, **doesn't require an understanding** of linear algebra, partial derivatives and other complex mathemathical concepts which one cannot find in their high school syllabuses. However, it does have a course which gives the fundamentals of essential math for Machine Learning which you can find in your Senior Year Math books.

我在本指南中汇集的所有信息都是为希望在这一新兴领域取得优异成绩的高中生准备的。与我遇到的大多数指南/学习路径不同的是，**不要求理解线性代数、偏导数和其他复杂的数学概念**，这在高中教学大纲中是找不到的。然而，它确实有一门课程提供了机器学习的基本数学知识，你可以在高三的数学书中找到。

If you work through this path on a regular basis, I believe that you could get to a pretty high level in about three months. However, this learning path does provide content that can keep you learning for the rest of your high school stay.

如果你经常通过这个途径学习，我相信你可以在三个月左右达到相当高的水平。然而，这个学习路径确实提供了可以让你在高中剩余时间里继续学习的内容。

So, lets get to it.

所以，让我们开始吧。

### 1. Learning Python, which you will code your algorithms in.

### 1. 学习 Python，你将用它来编码你的算法。

I strongly suggest Python for this - not only is it extremely easy to learn, it supports pretty much any good library used in Machine Learning. While R is useful, I just find that Python in general is far more suitable for high school students. Besides basic programming, for Machine Learning in particular, the libraries that are most useful are Numpy, Pandas and Matplotlib. 

我强烈建议使用 Python，它不仅非常容易学习，而且支持机器学习中使用的几乎所有好的库。虽然 R 很有用，但我只是发现一般来说 Python 更适合高中生使用。除了基本的编程，特别是对于机器学习，最有用的库是 Numpy、Pandas 和 Matplotlib。

- For those of you who have never coded before, I suggest going to a course provided by the University of Toronto (one of the best universities for ML/AI right now). It will take you a few weeks, but its well worth your time - most of the knowledge you gain through this course can be applied to any other programming language, the only difference being the syntax. The course is free, and can be found [here](https://www.coursera.org/learn/learn-to-program?siteID=SAyYsTvLiGQ-rs4V8qoewjp3oL7Nr.r_Fw&utm_content=10&utm_medium=partners&utm_source=linkshare&utm_campaign=SAyYsTvLiGQ#).

- 对于那些从来没有编过代码的人，我建议去参加多伦多大学（目前在 ML/AI 方面最好的大学之一）提供的一个课程。它将花费你几周的时间，但它非常值得你花时间 —— 你通过这个课程获得的大部分知识可以应用于任何其他编程语言，唯一的区别是语法。该课程是免费的，可以在[这里](https://www.coursera.org/learn/learn-to-program?siteID=SAyYsTvLiGQ-rs4V8qoewjp3oL7Nr.r_Fw&utm_content=10&utm_medium=partners&utm_source=linkshare&utm_campaign=SAyYsTvLiGQ#)找到。

- For those of you who have coding experience in a language besides Python, just skim through [this tutorial](https://www.tutorialspoint.com/python/python_basic_syntax.htm) for syntax - it won't take you more than a day.

- 对于那些除了 Python 之外还有其他语言编码经验的人来说，只要略过[本教程](https://www.tutorialspoint.com/python/python_basic_syntax.htm)的语法就可以了 —— 不会超过一天的时间。

- Machine learning and AI are built on mathematical principles like Calculus, Linear Algebra, Probability, Statistics, and Optimization; and many would-be AI practitioners find this daunting. The course on edX [Essential Math for Machine Learning: Python Edition](https://www.edx.org/course/essential-math-for-machine-learning-python-edition-2) by Microsoft is not designed to make you a mathematician. Rather, it aims to help you learn some essential foundational concepts and the notation used to express them. The course provides a hands-on approach to working with data and applying the techniques you’ve learned, and financial aid is available for those who need it.

- 机器学习和人工智能是建立在微积分、线性代数、概率、统计和优化等数学原理之上的；而许多想成为人工智能从业者的人都觉得这令人生畏。微软在 edX 上的课程 [Essential Math for Machine Learning: Python Edition](https://www.edx.org/course/essential-math-for-machine-learning-python-edition-2) 。这门课不是为了让你成为一名数学家，相反，它旨在帮助你学习一些基本的基础概念和用于表达这些概念的符号。该课程提供了一种实践的方法来处理数据和应用你所学到的技术，有需要的人可以获得经济援助。

- Now, after you've learnt the basics of Python, you need to understand the first two libraries I was talking about (Matplotlib  can come later). Numpy arrays and Pandas are used for moving around and modifying  the data you use, while Matplotlib is used to visualize this data through graphs and diagrams. The following courses together shouldn't take more than a couple of days:

- 现在，在你学习了 Python 的基础知识之后，你需要了解我所说的前两个库（Matplotlib 可以在后面）。Numpy 数组和 Pandas 用于移动和修改你使用的数据，而 Matplotlib 则用于通过图形和图表将这些数据可视化。下面的课程加起来不应该超过几天时间。

  - [Numpy](http://cs231n.github.io/python-numpy-tutorial/)
  - [Pandas](https://pandas.pydata.org/pandas-docs/stable/10min.html)
  
  
Great! Now you should be set in the core programming needed to learn Machine Learning and Artificial Intelligence.

很好!现在你应该已经掌握了学习机器学习和人工智能所需的核心编程。
 
### 2. Getting into the basics of Machine Learning.

### 2. 进入机器学习的基础知识。

If there's one universal course for Machine Learning, it has to be Andrew Ng's course. This course is nothing short of brilliant, though for high school students, it may seem slightly challenging at times, as it refers to concepts such as partial derivatives (though these aren't required to understand the course). I found it beneficial to re-watch some lectures in Weeks 3 to 5 - it may be a bit fast the first time around. Don't be too worried if you can't grasp some of the derivations - these require high university-level math knowledge. Being able to follow the thought process and gain an understanding of the operations should be enough for now.

如果有一门机器学习的通用课程，那一定是安德鲁·吴的课程。这门课程不可谓不精彩，尽管对于高中生来说，有时可能会显得稍有挑战性，因为它提到了偏导数等概念（尽管这些并不是理解该课程的必要条件）。我发现在第 3 至第 5 周重新观看一些讲座是有好处的 —— 第一次看可能会有点快。如果你不能掌握一些推导，也不要太担心 —— 这些需要很高的大学水平的数学知识。目前，能够遵循思维过程并理解运算，就已经足够了。

I encourage everyone to go through this and take notes, though doing the programming-related tutorials and exercises is not needed, as its done in Matlab, which (in my experience) is often too tough for high schoolers to grasp. But don't worry, we will be doing the very same (and far more advanced) algorithms in Python in just a short amount of time.

我鼓励大家仔细阅读并做笔记，尽管不需要做与编程有关的教程和练习，因为它是在 Matlab 中完成的，（根据我的经验）对于高中生来说，Matlab 往往太难掌握。但是不要担心，我们将在很短的时间内用 Python 做同样的（而且更高级的）算法。

This free course can be found [here](https://www.coursera.org/learn/machine-learning).

这一免费课程可在[这里](https://www.coursera.org/learn/machine-learning)找到。 

 
### 3. Learning an assortment of machine learning algorithms and understand how to implement them in real-world scenarios.

### 3. 学习各种各样的机器学习算法，并了解如何在现实世界的场景中实现这些算法。 

Now, understanding machine learning algorithms without the knowledge of university-level maths - this should be hard in theory, however, a team from Australia resolved this issue.

现在，在没有大学数学知识的情况下理解机器学习算法 —— 这在理论上应该很难，然而，来自澳大利亚的一个团队解决了这个问题。

Kirill Eremenko and Hadelin de Ponteves - a pair from the SuperDataScience team - are absolutely fantastic at finding relevant ways to apply simple algorithms in real life. Furthermore, they go into a suitable amount of depth to understand the functionality of the algorithm, but without the complex maths that a high school would not be able to understand.

Kirill Eremenko 和 Hadelin de Ponteves —— 这对来自 SuperDataScience 团队的组合 —— 在寻找相关方法在现实生活中应用简单算法方面绝对是非常出色的。此外，他们还对算法的功能进行了适当的深入了解，但没有高中生无法理解的复杂数学知识。

Their course covers both Python and R, though you don't have to worry about R - simply go through the Python tutorials. Also, if you find that they are going a bit too slow, play this course at 1.25x speed (I did that and found it much better).

他们的课程包括 Python 和 R，尽管你不必担心 R —— 只需通过 Python 教程。另外，如果你发现他们的速度有点太慢，可以用 1.25 倍的速度播放这个课程（我这样做了，发现效果好多了）。

Their course is on Udemy, and is paid, though Udemy regularly has discounts of 90% or more on their courses. It can be found [here](https://www.udemy.com/machinelearning/learn/v4/overview), and is usually around $10. 

他们的课程在 Udemy 上，而且是付费的，不过 Udemy 的课程经常有 90% 以上的折扣。它可以在[这里](https://www.udemy.com/machinelearning/learn/v4/overview)找到，通常在 10 美元左右。

It covers everything from basic regression algorithms to deep and convolutional neural networks. If you wish to explore even more advanced areas, their Deep Learning course is offered at the end of the Machine Learning for a 90% discount. However, concepts in this second course may be a little advanced and lack proper documentation, since they are so new.

它涵盖了从基本回归算法到深度和卷积神经网络的所有内容。如果你想探索更高级的领域，他们的深度学习课程是在机器学习的最后提供的，有 90% 的折扣。然而，这第二门课程中的概念可能有点高级，而且缺乏适当的文档支持，因为它们较新。

If you're unwilling to pay for this course, you can check out Google's free Deep Learning course [here](https://www.udacity.com/course/deep-learning--ud730) or University of Michigan's free course [here](https://www.coursera.org/learn/python-machine-learning). However, these are far from as well-rounded as the SuperDataScience team's courses.

如果你不愿意为这个课程付费，你可以看看谷歌的免费深度学习课程[这里](https://www.udacity.com/course/deep-learning--ud730)或密歇根大学的免费课程[这里](https://www.coursera.org/learn/python-machine-learning)。然而，这些课程远不如 SuperDataScience 团队的课程全面。

For these courses, taking notes aren't a necessity - there are tons of 'algorithm cheat sheets' online, which offer a quick intution on how they work. [This website](https://www.analyticsvidhya.com/blog/2017/02/top-28-cheat-sheets-for-machine-learning-data-science-probability-sql-big-data/) lists a few.


对于这些课程，做笔记并不是必须的 —— 网上有大量的 “算法小抄”，可以快速了解它们的工作原理。[这个网站](https://www.analyticsvidhya.com/blog/2017/02/top-28-cheat-sheets-for-machine-learning-data-science-probability-sql-big-data/)列出了一些。

### 4. Explore, explore and explore.

### 4. 探索，探索，再探索。

Now, you've covered a wide range of machine learning concepts, and have learnt a vast amount of skills. Its time for you to independently use these on basic projects. I'd suggest going to [Kaggle](https://www.kaggle.com/) or the [UCI Machine Learning repository](http://archive.ics.uci.edu/ml/datasets.html), finding a dataset you have an interest in, and simply modelling some solutions to these. Play around with different algorithms, and try to optimize performance.

现在，你已经涵盖了广泛的机器学习概念，并学会了大量的技能。是时候让你在基本项目上独立使用这些技能了。我建议你去 [Kaggle](https://www.kaggle.com/) 或 [UCI 机器学习库](http://archive.ics.uci.edu/ml/datasets.html)，找到你感兴趣的数据集，并简单地模拟一些解决方案。玩一玩不同的算法，并尝试优化性能。

Ensure that the datasets you use are simple and clean in nature - they shouldn't require too much pre-processing or modifying. Some easy datasets (off the top of my head) are the Iris, Wine, Breast Cancer Wisconsin, Autism Screening, Congress Voting, Handwritten Digits MNIST and Fashion MNIST ones.

确保你使用的数据集在本质上是简单和干净的 —— 它们不应该需要太多的预处理或修改。一些简单的数据集（在我的脑海中）是鸢尾花、葡萄酒、乳腺癌威斯康星州、自闭症筛查、国会投票、手写数字 MNIST 和时尚 MNIST 等。

If you ever come across a road block, [Stack Overflow](https://stackoverflow.com/) is your best friend - they have an answer to almost any question that you'd have. If it doesn't, just post one - you should get replies within a couple of hours!

如果你遇到了障碍，[Stack Overflow](https://stackoverflow.com/) 是你最好的朋友 —— 他们几乎对你的任何问题都有答案。如果没有，就发一个 —— 你应该在几个小时内得到答复！

There's nothing much more I need to say here - when you find that you've become comfortable with the whole modelling process, feel free to move on!

我在这里已经没有什么需要说的了 —— 当你发现你已经对整个建模过程感到舒服时，就可以自由地继续前进了。

### 5. Find an area of particular interest, and dive deeper.

### 5. 找到一个特别感兴趣的领域，并深入研究。

Now you've got a great and broad understanding of all the basics. However, there's only a limit to what you can do with this. Thus, I suggest you find an area of interest in the broad field of Machine Learning, and look deeper into it. You probably won't have time to become experts in all of these in your high school tenure, but try and conquer one, if not two.

现在你已经对所有的基础知识有了一个很好的、广泛的了解。然而，你能做的事情是有限的。因此，我建议你在机器学习的广泛领域中找到一个感兴趣的领域，并深入研究它。你可能没有时间在你的高中任期内成为所有这些方面的专家，但尝试征服一个，如果不是两个。

I'll list some possible areas, but before you begin one of these, understand what it is you're getting into. A simple Youtube search for a high-level explanation will give you all you need.

我将列出一些可能的领域，但在你开始其中一个领域之前，请了解你要进入的是什么领域。在 Youtube 上简单地搜索一下高层次的解释就可以满足你的所有需要。

- Computer Vision: Probably the hottest field in Machine Learning/AI right now - making computers see and understand things using a special type of neural network. Stanford publishes their course in this online [here](http://cs231n.stanford.edu/), with lectures, course notes and assignments available online. Go through this, though if the math is too complicated, don't worry - the course is simply to deepen your knowledge. Alternatively, you could look to OpenCV, a computer vision library that does a lot of the complex stuff for you. A great tutorial can be found [here](https://www.youtube.com/watch?v=Z78zbnLlPUA&list=PLQVvvaa0QuDdttJXlLtAJxJetJcqmqlQq). Once you're done with these, look at more advanced image datasets on Kaggle and UCI, or even enter Kaggle Competitions.

- 计算机视觉。可能是目前机器学习/人工智能中最热门的领域 —— 使用一种特殊类型的神经网络使计算机看到并理解事物。斯坦福大学在[这里](http://cs231n.stanford.edu/)公布了他们的课程，网上有讲座、课程笔记和作业。通过这个，尽管如果数学太复杂，不要担心 —— 课程只是为了加深你的知识。另外，你也可以看看 OpenCV，这是一个计算机视觉库，可以为你做很多复杂的事情。[这里](https://www.youtube.com/watch?v=Z78zbnLlPUA&list=PLQVvvaa0QuDdttJXlLtAJxJetJcqmqlQq)可以找到一个很好的教程。一旦你完成了这些，可以看看 Kaggle 和 UCI 上更高级的图像数据集，甚至可以参加 Kaggle 竞赛。

- Natural Language Processing: Understanding how computers learn to speak is also a prominent topic today. Once again, Stanford offers a great course thats online and can be found [here](http://web.stanford.edu/class/cs224n/). If you don't understand some of the Math concepts, don't worry, just gain an understanding of how this field works. For implementations, you could undertake [this Udemy course](https://www.udemy.com/data-science-natural-language-processing-in-python/). However, you could alternatively go through some of well-known Machine Learner [Siraj Raval's videos](https://www.youtube.com/watch?v=9zhrxE5PQgY). One you've done these, try undertaking simple, well-known projects like building a chatbot, sentiment analysis or creating lyrics to a song - simple Youtube searches should help you out.

- 自然语言处理。了解计算机如何学习说话也是当今一个突出的话题。斯坦福大学再次提供了一个很好的课程，可以在[这里](http://web.stanford.edu/class/cs224n/)找到。如果你不理解一些数学概念，不用担心，只要了解这个领域的工作原理就可以了。对于实施，你可以学习[这个Udemy课程](https://www.udemy.com/data-science-natural-language-processing-in-python/)。然而，你也可以通过一些著名的机器学习者 [Siraj Raval的视频](https://www.youtube.com/watch?v=9zhrxE5PQgY)。当你做完这些之后，可以尝试进行一些简单的、著名的项目，比如建立一个聊天机器人、情感分析或者为一首歌创作歌词 —— 在 Youtube 上简单的搜索就可以帮助你了。

- Reinforcement Learning: This domain focuses on how machines learn to act in a particular way, and its most popular application is in the field of video games. Siraj Raval again has a pretty good playlist on this, which can be found [here](https://www.youtube.com/watch?v=i_McNBDP9Qs&list=PL2-dafEMk2A5FZ-MnPMpp3PBtZcINKwLA). If you are looking for implementation-based tutorials specifically using a high-level package like Tensorflow, Denny Britz has a solid set of tutorials which can be found [here](https://github.com/dennybritz/reinforcement-learning). David Silver's UCL course is also great, though beginners may find it a bit tricky - it can be found [here](http://www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching.html). Once you're done with these, its pretty logical to just start downloading base projects or games from online, and adding an element of Artificial Intelligence to modify how the agents they act. Simple walkthroughs can again be found via a simple Youtube search.

- 强化学习。这个领域主要是研究机器如何学习以特定的方式行事，其最流行的应用是在视频游戏领域。Siraj Raval 在这方面又有一个相当不错的播放列表，可以到[这里](https://www.youtube.com/watch?v=i_McNBDP9Qs&list=PL2-dafEMk2A5FZ-MnPMpp3PBtZcINKwLA)。如果你正在寻找基于实施的教程，特别是使用像 Tensorflow 这样的高级软件包，Denny Britz 有一套扎实的教程，可以到[这里](https://github.com/dennybritz/reinforcement-learning)。David Silver 的 UCL 课程也很不错，尽管初学者可能会发现它有点棘手 —— 可以到[这里](http://www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching.html)。一旦你完成了这些课程，就可以顺理成章地开始从网上下载基础项目或游戏，并添加人工智能元素来修改代理的行为方式。通过简单的Youtube搜索，可以再次找到简单的演练。

- Data Science: This field is a budding domain with tons of exciting job oppurtunities. I suggest undertaking either SuperDataScience's paid [course](https://www.udemy.com/datascience/) or UC San Diego's Python-based free [course](https://www.edx.org/course/python-data-science-uc-san-diegox-dse200x), though you should find a specific learning path for data science with a simple Google search. You can also use the following links to learn [SQL](https://www.khanacademy.org/computing/computer-programming/sql) and [Matplotlib](https://www.youtube.com/watch?v=q7Bo_J8x_dw). The advantage in learning this at a student level is employability - I have friends in high school who've been offered data science internships, as the data gained from their work can instantly be monetized by companies. Its easy for companies to find a way to use a data scientist.

- 数据科学。这个领域是一个刚刚起步的领域，有大量令人兴奋的工作机会。我建议学习SuperDataScience 的付费[课程](https://www.udemy.com/datascience/)或加州大学圣地亚哥分校基于 Python 的免费[课程](https://www.edx.org/course/python-data-science-uc-san-diegox-dse200x)，尽管你应该通过简单的谷歌搜索来找到数据科学的具体学习途径。你也可以使用以下链接来学习 [SQL](https://www.khanacademy.org/computing/computer-programming/sql) 和 [Matplotlib](https://www.youtube.com/watch?v=q7Bo_J8x_dw)。在学生阶段学习这个的好处是就业能力 —— 我有朋友在高中就得到了数据科学的实习机会，因为从他们的工作中获得的数据可以立即被公司货币化。公司很容易找到使用数据科学家的方法。

- There are also areas like Boltzmann Machines (used for recommendation systems), Adversial Networks (AI improving AI) and Genetic Algorithms (improving a solution to a problem in a way similar to natural evolution), but in my opinion, these are a stretch for most high school students. Do feel free to explore these if you have a particular passion for one of them, though they aren't as well covered as the other domains, largely due to the fact that they aren't currently monetized as much as the other fields.

- 还有一些领域，如玻尔兹曼机（用于推荐系统）、逆向网络（人工智能改进人工智能）和遗传算法（以类似于自然进化的方式改进问题的解决方案），但在我看来，这些对大多数高中生来说是一个延伸。如果你对其中一个领域有特别的热情，请随时探索这些领域，尽管它们没有像其他领域那样得到很好的覆盖，这主要是由于它们目前没有像其他领域那样被货币化的事实。

 ### BONUS (extremely important). Truly understand the field of Artificial Intelligence.

## BONUS（极其重要）。真正了解人工智能领域。 

If you want to work in this field in the long run, its crucial to understand what it is about, groundbreaking discoveries and its implications on society. You should start doing things listed in this section as soon as you have the necessary understanding of how the technology works - I believe that this is after Section 4 of this learning path (as you start delving into an area of interest). This kind of information may not particularly help you when implementing algorithms, but its an impressive sign for universities or companies when their prospects are so knowledgeable in the field itself, rather than just the code.

如果你想在这个领域长期工作，关键是要了解它的内容，突破性的发现及其对社会的影响。一旦你对该技术的工作原理有了必要的了解，你就应该开始做这一节中列出的事情 —— 我认为这是在本学习路径的第 4 节之后（因为你开始深入研究一个感兴趣的领域）。这种信息在实现算法时可能对你没有特别大的帮助，但对于大学或公司来说，当他们的前景在这个领域本身，而不仅仅是代码方面有如此丰富的知识时，这是一个令人印象深刻的迹象。

There's a few things that a high schooler should do to deepen their general understanding of the field and make them more knowledgeable, which I'll list here:

有几件事是高中生应该做的，以加深他们对这个领域的一般理解，使他们更有知识，我将在这里列出这些：

1. Start reading research papers: They really aren't as challenging as they sound. A good portion of them can be almost completely comprehended with a high school Math level. If you ever come across one you don't understand, just put it down - theres more than enough alternatives. This [link](https://www.kdnuggets.com/2017/04/top-20-papers-machine-learning.html) offers a host of great papers, though after you finish those, [this](http://www.jmlr.org/papers/) offers the most up-to-date list - simply read ones you're interested in or related to your area of 'expertise' from section 5. It's helpful to keep a small diary of learnings from each paper. If you are unable to truly understand many of these reserach papers, try going through another Github guide I wrote on research papers, which provides a breakdown of some recent revelations.

1.开始阅读研究论文。它们真的不像听起来那样具有挑战性。它们中的很大一部分几乎可以被高中数学水平的人完全理解。如果你遇到不懂的，就把它放下 —— 有足够多的替代品。这个[链接](https://www.kdnuggets.com/2017/04/top-20-papers-machine-learning.html)提供了大量的优秀论文，尽管在你完成这些论文后，[这个网站](http://www.jmlr.org/papers/)提供了最新的列表 —— 只需阅读你感兴趣的或与你的 “专业领域” 有关的第 5 节。将每篇论文的学习内容写成小日记是很有帮助的。如果你无法真正理解这些研究论文中的许多内容，可以尝试通过我写的另一个关于研究论文的 Github 指南，其中提供了一些近期启示的细目。

2. Listen to the pioneers: People like Andrew Ng, Ian Goodfellow and Yann LeCunn are regularly interviewed, and give the perspective of engineers of this field on the subject of AI. This [Youtube channel](https://www.youtube.com/user/Maaaarth/videos) gathers the best of these talks, and compiles them into a central resource - watch one a night, and I guarantee that you'll feel like an expert within weeks.

2.听听先驱者的意见。像 Andrew Ng、Ian Goodfellow 和 Yann LeCunn 这样的人经常接受采访，并就人工智能的主题给出这个领域的工程师的观点。这个 [Youtube 频道](https://www.youtube.com/user/Maaaarth/videos)收集了这些讲座的精华，并将它们汇编成一个中央资源 —— 每晚看一次，我保证你会在几周内感觉自己是个专家。

3. Stay up-to-date with the field: Wired is one of the best platforms for anyone interested in tech. It publishes multiple AI-related stories every day, which can be found [here](https://www.wired.com/tag/artificial-intelligence/). Its simply a great way to understand the trends of the time. Alternatively, subsribe to TechCrunch's Facebook Messenger bot - it often has interested AI-related articles, and prompts you with information every day.

3.保持与该领域的最新进展。《连线》是对科技感兴趣的人的最佳平台之一。它每天都会发布多个与人工智能相关的故事，可以在[这里](https://www.wired.com/tag/artificial-intelligence/)找到。这简直是了解时代趋势的一个好方法。或者，订阅 TechCrunch 的 Facebook Messenger 机器人 —— 它经常有感兴趣的人工智能相关文章，并且每天都会提示你相关信息。

4. Understand the implications: There's no better way to do this than listening to TED talks. Their speakers are extremely knowledgeable in the field, and there is an increasing emphasis on AI in their speeches. A host of videos can be found [here](https://www.youtube.com/user/TEDtalksDirector/videos).

4.理解其中的含义。没有比听 TED 讲座更好的方法了。他们的演讲者在该领域的知识非常丰富，而且在他们的演讲中越来越强调人工智能。在[这里](https://www.youtube.com/user/TEDtalksDirector/videos)可以找到大量的视频。

5. The Philosophy: AI has its supporters and its opposers. The philosophy behind it, however, is intriguing. My favourite books that explore this area, and are suitable for High School students, include 'How to Create a Mind' by Ray Kurzweil and ['Life 3.0'](http://s3.amazonaws.com/arena-attachments/1446178/cffa5ebc74cee2b1edf58fa9a5bbcb1c.pdf?1511265314) by Max Tegmark - do try and read these. 

5.哲学。人工智能有其支持者，也有其反对者。然而，它背后的哲学是耐人寻味的。我最喜欢的探索这一领域的书籍，而且适合高中生阅读，包括雷·库兹韦尔（Ray Kurzweil）的《如何创造思想》和马克斯·泰格马克（Max Tegmark）的[《生命 3.0》](http://s3.amazonaws.com/arena-attachments/1446178/cffa5ebc74cee2b1edf58fa9a5bbcb1c.pdf?1511265314)—— 请尝试阅读这些书籍。

6. Contributing: If you‘re the kind of person who likes to learn from others experience, check out the Artificial Intelligence & Deep Learning Facebook group. Alternatively, if you prefer conversations, check out Reddit’s thread on AI here（https://www.reddit.com/r/artificial/）. 

6.贡献。如果你是那种喜欢从别人的经验中学习的人，可以去看看人工智能和深度学习的 Facebook 小组。另外，如果你喜欢谈话，可以在这里查看 Reddit [关于人工智能的主题](https://www.reddit.com/r/artificial/)。

7. Delve into the math: Yes, you do need university level math skills, but if you're an extremeley strong math student, there's nothing stopping you from taking some online courses. Microsoft has a free [course](https://www.edx.org/course/essential-math-for-machine-learning-python-edition-2) that I've heard good things about, and requires just High School-level maths. This [Quora thread](https://www.quora.com/How-do-I-learn-mathematics-for-machine-learning) also has some great resources that you should check out. [3Blue1Brown](https://www.youtube.com/channel/UCYO_jab_esuFRV4b17AJtAw/playlists) is a famous name in the community too, as his Youtube videos are fantastic for learning the maths (primarily linear algebra and calculus) behind some of these more complicated concepts.

7.深入研究数学。是的，你确实需要大学水平的数学技能，但如果你是一个极强的数学学生，没有什么可以阻止你参加一些在线课程。微软有一个免费的[课程](https://www.edx.org/course/essential-math-for-machine-learning-python-edition-2)，我听说它很不错，只需要高中水平的数学知识。这个 [Quora 线程](https://www.quora.com/How-do-I-learn-mathematics-for-machine-learning)也有一些很棒的资源，你应该去看看。[3Blue1Brown](https://www.youtube.com/channel/UCYO_jab_esuFRV4b17AJtAw/playlists)在社区中也是一个有名的名字，因为他的 Youtube 视频对于学习这些更复杂的概念背后的数学（主要是线性代数和微积分）是非常棒的。

## Conclusion

## 结论

I wish everyone the best of luck in undertaking this learning path. I've heard too many people say Machine Learning and Artificial Intelligence is too complicated to learn as a high school student to not write this - with a well-paved learning path, it can be done by anyone. Its just that due to the field being so new and generally thought of as a graduate field of study, theres a lack of one for high school students.

我祝愿大家在进行这条学习道路上取得好成绩。我听过太多的人说机器学习和人工智能太复杂了，作为一个高中生不可能不写这个 —— 只要有一个良好的学习路径，任何人都可以做到。只是，由于该领域是如此之新，而且一般被认为是研究生的研究领域，所以缺乏一个适合高中生的研究。

If anyone has additions, suggestions, queries or feedback, feel free to write to me@kj.jaisingh@gmail.com. 

如果有人有补充、建议、疑问或反馈，请随时写信给 me@kj.jaisingh@gmail.com。 

<h2>Guide Contributors</h2>

<a href="https://github.com/kjaisingh/ML-for-High-Schoolers/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=kjaisingh/ML-for-High-Schoolers" />
</a>

<br>
