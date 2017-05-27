# Data Science Primer

People approach data science from various angles. Mine was: a major in Sociology, previous exposure to basic statistics and a lot of hobby programming, working with Unix-like systems etc.

Still, having no real technical background, I managed to get an industry job after more than a year of intensive study. Here I list a number of sources which were the most helpful in my professional conversion. This list does not contain everything that I have ever read on the subject, **only the beginner-friendly stuff**.

Due to the data science hype, the Web is full of _become a data scientist over a weekend_ materials. This site promises something else: you'll be provided with studying materials for years to come.

## Mathematics

We start with mathematics, although some of the materials listed later on don't assume much of mathematical flucency. Feel free to move to the more fancy stuff and revisit the basics as needed. For instance, you could start with [Andrew Ng's excellent _Machine learning_ course](https://www.coursera.org/learn/machine-learning/) to develop basic mathematical intuitions, and then return to the materials listed here to solidify your understanding.

#### Calculus

* \[[book](http://www.amazon.com/Pre-calculus-Demystified-Second-Rhonda-Huettenmueller/dp/0071778497)\] **_Pre-calculus Demystified_ by Rhonda Huettenmueller** - the book offers a concise refresher with enough exercies (with answers!) to get you back on track with high-school-level math.
* \[[mooc](https://www.coursera.org/learn/calculus1)\] **_Calculus One_ by Jim Fowler** - a man of passion for calculus, Jim Fowler will guide you through 16-week long calculus course. Together with James Stewart's book mentioned below, this will give you a solid understanding of the topic.
* \[[book](http://www.amazon.com/Calculus-Early-Transcendentals-James-Stewart/dp/0495011665)\] **_Calculus: Early Transcendentals_ by James Stewart** - James Steward became a millionaire by writing calculus books, and there's a good reason for that. This is due to tons of examples and exercises (some briefly explained at the end of the book, the rest [available online](http://resources.rogue.ninja/pdf/Stewart-7E-solutions.pdf)), lots of pictures, tables and charts. Once you're in machine learning field, you don't need to be convinced of the applicability of calculus, but this book brings many engineering applications of calculus and thus builds the appreciation of the topic. The deeper into the text, the more consise the examples (it is assumed that some calculations introduced earlier don't need to be explained in every example that follows), so more effort is expected. In my love-hate relationship with math, there was always more hate than love, but it changed a lot lately, and one of the reasons is the Stewart's book.

#### Linear algebra

* \[[mooc](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)\] **_Essence of linear algebra_ by Grant Sanderson** - The best short series of videos for building basic intuitions behind core concepts of Linear Algebra. Beautifully visualized and explained. Definitely, the number one source for anyone starting with linear algebra, although I believe linear algebra practicioners can also benefit from it.
* \[[book](http://www.amazon.com/Linear-Algebra-Step-Kuldeep-Singh/dp/0199654441)\] **_Linear Algebra: Step by Step_ by Kuldeep Singh** - There are tons of linear algebra books out there but most of them aren't really helpful for people without proper maths/technical background. Kuldeep Singh's book is light enough to get you started, although I strongly advice reading it along with Norman Wildberger's lectures listed below. These two sources will give enough linear algebra skills, unless your aim is to invent some ground breaking calculations. One of the neat feats of this book is [an official on-line repository of full solutions](http://global.oup.com/booksites/content/9780199654444/studentsolutions/) and brief solutions at the end of the book.
* \[[youtube](https://www.youtube.com/playlist?list=PL01A21B9E302D50C1)\] **_WildLinAlg: A geometric course in Linear Algebra_ by Norman J. Wildberger** - I really appreciate the strong geometric focus in Norman Wildberger's lectures. It really helps in grasping the concepts. Also, you should be informed that Norman Wildberger's aim isn't to offer you yet another classical linear algebra course. There's a lot of personal touch in these materials. And I doubt that's a flaw.

#### Probability & Statistics

* \[[book](https://www.amazon.com/Probability-Enthusiastic-Beginner-David-Morin/dp/1523318678)\] **_Probability: For the Enthusiastic Beginner_ by David J. Morin** - a really nice introduction to probability theory. This book excels in the way problems and solutions are covered. There are dozens of problems with fully worked out solutions. Often, the discussion covers the problem from various angles and thus offers a possiblity to fully understand the task at hand. 
* \[[book](https://www.amazon.com/Statistics-4th-David-Freedman/dp/0393929728)\] **_Statistics_ by David Freedman, Robert Pisani and Roger Purves**
* \[[book](http://shop.oreilly.com/product/0636920023074.do)\] **_Statistics in a Nutshell: Desktop Quick Reference_ by Sarah Boslaugh** - this book won't teach you the underlying math behind statistics, but will tell you enough to know how to _use_ statistics. This book is exactly what it states in the title: a good reference.


## Model thinking

In the data science trend there's too much focus on data and not enough on science. Make sure that you're fluent with the building blocks of science, namely: models. The sources below provide a really gentle introduction into these little creatures.

* \[[mooc](https://www.coursera.org/learn/model-thinking/home/welcome)\] **_Model thinking_ by Scott Page** - a really gentle, but broad introduction to various types of models. This course is not specifically targeted at data scientists, but still it builds important intuitions. After all, data scientist often model behavior of individuals. Thus, I find this course an important addition to the following curriculum.
* \[[book](http://www.amazon.com/Modeling-Reality-Computers-Mirror-CD-ROM/dp/0198531001)\] \[[homepage](http://www.modelingreality.net/)\] **_Modeling Reality: How Computers Mirror Life_ by Iwo Białynicki-Birula and Iwona Białynicka-Birula** - this nice little book explains various models (from cellular automata, neural networks and genetic algorithms) through games, examples and computer programs. No expert knowledge or university-level math is required, yet the Authors convey this invaluable feel for models and their computability.




## Data analysis

#### Data wrangling

* \[[book](http://shop.oreilly.com/product/0636920023784.do)\] **_Python for Data Analysis_ by Wes McKinney** - pandas is one of the key tools for efficient data analysis in Python. There are literally tons of pandas tutorials on the Web, but still it's good to read through the book created by the author of the package.

#### Data mining

* \[[book](http://www.amazon.com/Discovering-Knowledge-Data-Introduction-Mining/dp/0471666572)\] **_Discovering Knowledge in Data: An Introduction to Data Mining_ by Daniel T. Larose** - the book offers a gentle introduction to the process of data mining and explains some basic algorithms in a very accessible way.

#### Machine learning

* \[[mooc](https://www.coursera.org/learn/machine-learning/)\] **_Machine learning_ by Andrew Ng** - this is one of the best places to start your adventure with machine learning. Andrew Ng is brilliant in sharing mathematical intuitions behind the most important algorithms. From time to time I find myself re-viewing particular videos of Ng's course and I keep beeing amazed by how capable educator Andrew Ng is. 
* \[[book](http://www-bcf.usc.edu/~gareth/ISL/)\] **_An Introduction to Statistical Learning_ by Gareth James, Daniela Witten, Trevor Hastie and Robert Tibshirani** - this book proves that the basic concepts of machine learning can be introduced without throwing all these calculus and linear algebra equations at first-timers. The authors (real titans are among them) did a big favor to their discipline by publishing this book.

#### Neural networks

* \[[book](http://neuralnetworksanddeeplearning.com/)\] **_Neural networks and deep learning_ by Michael Nielsen** - many authors stop explaining things exactly when questions pop up in my head. Michael Nielsen is not one of them, and that's why I have the most utter respect for him. He anticipates questions and doubts of the reader and rushes with explanations. This is the trait of the greatest educators. To really profit from reading this book you'll need some calculus and linear algebra (especially if you wish to solve the exercises and problems posed), but the prose itself is welcoming for newcomers. You might have noticed that there's a lot of books in paper form on my list. I prefer to read books in paper form since it's less tiring for my eyes, and I regret that Michael Nielsen's book is not available as a proper book. Still, it's definitely worth the effort, and the fatigue of the eyes.
* \[[on-line materials](http://cs231n.github.io/)\] **_CS231n Convolutional Neural Networks for Visual Recognition_ by Andrej Karpathy** - the notes accompanying the Stanford CS class are not far away from becoming a book, and it would be a good book. At the beginning, through simple code snippets in Python Andrej Karpathy compares the neural networks to other machine learning algorithms. Then he dives deep into the neural networks keeping a strong practical approach along the way.
* \[[on-line materials](http://colah.github.io/)\] **Blog of Christopher Olah** - neural networks may be hard to grasp, but Christopher Olah makes them more straightforward with his lovely examples and visualizations. Word embeddings, LSTMs, CNNs - these things (among others) are neatly explained.
* \[[on-line materials](http://playground.tensorflow.org)\] **Tensorflow Playground** - a lovely webapp, which enables playing with basic datasets and architectures by tweaking parameters. Really, a great starting point to get some intuitons on how various configurations impact learning/generalizaing capability of the network.

#### Big data

* \[[mooc](https://www.coursera.org/course/datasci)\] **_Introduction to Data Science_ by Bill Howe** - a nice intro with a well balanced approach to SQL versus NoSQL solutions. Although the course has it's statistical analysis and machine learning parts, I think it's mostly worth watching for databases-related videos.
* \[[book](http://www.mmds.org/)\] \[[mooc](https://www.coursera.org/course/mmds)\] **_Mining of Massive Datasets_ by Jure Leskovec, Anand Rajaraman, Jeff Ullman** - sooner or later you're going to discover problems too big to solve with most traditional approaches. The authors show a wide range of problems where size can get out of control: finding similar items, working with data streams and graphs and many more. I loved the Coursera course, but I found the book a bit too dry. Many of these problems can be well-illustrated but the book lags in terms of visual layer. Still, it is a great resource written in rather accessible manner. It could have been more entertaining, though.

#### Network analysis

* \[[book](https://www.amazon.com/Networks-Introduction-Mark-Newman/dp/0199206651)\] **_Networks. An introduction_ by Mark Newman**

## Databases

#### SQL

* \[[online documentation](https://www.postgresql.org/docs/9.6/static/index.html)\] **PostgreSQL Documentation** - PostgreSQL comes with tons of great documentation, certainly enough to be able to use this database like a pro.

#### NoSQL
* \[[mooc](https://university.mongodb.com/courses/M101P/about)\] **_M101P: MongoDB for Developers_ by Andrew Erlichson** - although MongoDB's [manuals](https://docs.mongodb.com/manual/) are really comprehensive, a nice and gentle intro may help you. The M101P videos are a good start. Make sure you listen/read about the [Aggregation Pipeline](https://docs.mongodb.com/manual/core/aggregation-pipeline/) - as a Data Scientist you may be using it heavily.


## Programming

Given my prior experience in programming (almost 15 years of hobby coding) I am not the best source of recommendations for beginners in this area. If you're starting with programming you should go somewhere else for advice. However, if your aim is to advance from amateur programmer (which often applies to data scientists) to a professional, these links will help you. 

#### Algorithms

* \[[book](http://www.amazon.com/Algorithms-4th-Robert-Sedgewick/dp/032157351X)\] \[[online version](http://algs4.cs.princeton.edu/home/)\] **_Algorithms_ by Robert Sedgewick and Kevin Wayne** - you can get really far without thorough understanding of the algorithimcs. A search engine and a bit of intuition suffices most of the time. But once you get to the point where it's not enough, you'll want to have Sedgewick's and Wayne's book by your side. Sorting, searching, graphs and strings - these four classes of algorithms are thoroughly explained and well illustrated. The book makes for a lovely experience both in terms of contents and aesthetics.

#### Software engineering

* \[[book](http://www.amazon.com/Code-Complete-Practical-Handbook-Construction/dp/0735619670)\] \[[homepage](http://cc2e.com/)\] **_Code complete_ by Steve McConnell** - Apart from a number of debatable points, this book consists of hundreds of obvious remarks. One just can’t read this book for too long, since it’s hard to stand this throng of banalities. But, as experience shows, most of the programmers either are not familiar with basics of software engineering or are having hard time exercising good practices in everyday coding. That’s why this book is important and it’s worth the effort.
* \[[book](http://www.amazon.com/Refactoring-Improving-Design-Existing-Code/dp/0201485672)\] - **_Refactoring: Improving the Design of Existing Code_ by Martin Fowler, Kent Beck, John Brant, William Opdyke, and Don Roberts** - you're going to hit the wall of unreadable code time and time again (your code included). Once you start tracking newest publications and seeking for the original implementations, you'll be suprised how terrible code can be hidden behind a brilliant publication. You need to recognize the bads quickly and be able to respond with a proper refactoring strategy.
* \[[book](https://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882)\] - **_Clean code: A Handbook of Agile Software Craftsmanship_ by Robert Martin**


#### Java

* \[[book](http://www.amazon.com/Core-Java-I-Fundamentals-9th/dp/0137081898)\] \[[homepage](http://horstmann.com/corejava.html)\] **_Core Java_ by Cay S. Horstman and Gary Cornell**

#### Python

## Essential tools

Enough theory. You'll need some tools to apply all that knowledge. I am rather a Python + Java person, so you may need some other resources to start with such tools as R.

#### Code management
* \[[tutorial](https://git-scm.com/book/en/v2)\] **_git_** - you just can't afford not to know git. Even if you're working alone, you iterate, you go back and forth and git is there to remember your steps. Just remember to commit often. Also, take some time and learn how to rebase (including interactive rebase). This job is usually messy, and there's no reason to remember all the dirt once you arrive at the solution. Git, obviously, is even more important if you're collaborating with others. I ensure you, you don't want to be that person who repeatedly breaks the repository due to insufficient command of git.  
* \[[homepage](https://www.docker.com/)\] **_docker_** - at some point in time you will want to share your models with someone else and it won't work on other machines due to dependencies and some unspecified traits of your environment. You can make your (and others) life easier by using containerization, that is: creating a well defined, easily reproducible environment for your software.

#### Data wrangling and analysis

* \[[homepage](http://pandas.pydata.org/)\] **_pandas_** - one of the crucial libraries for data wrangling and data analysis in Python. Paired with [numpy](http://www.numpy.org/) and [scipy](http://scipy.org/), the trio builds a strong environment for doing anything you can imagine with your data. And possibly more.
* \[[homepage](http://matplotlib.org/)\] **_matplotlib_** - a very powerful (and thus quite complex) plotting library for Python. Due to its complexity, a number of wrapping libraries were created. Among them, the [Seaborn](https://stanford.edu/~mwaskom/software/seaborn/) library comes as one of the nicest ones.

#### Machine learning

* \[[homepage](https://scikit-learn.org)\] **_scikit-learn_** - one of the best machine learning suites for Python. Do yourself a favor and make sure that you do unserstand how [pipelines](http://scikit-learn.org/stable/modules/generated/sklearn.pipeline.Pipeline.html) in scikit-learn work.

#### Natural language processing

* \[[homepage](http://www.nltk.org/)\] **_nltk_** - the most comprehensive Python toolkit for playing with human language data. Make sure you won't miss the [_NLTK Book_](http://www.nltk.org/book/).
* \[[homepage](https://radimrehurek.com/gensim/)\] **_gensim_** - a nice tool for playing with word embeddings (among other things that it offers).

#### Deep learning

* \[[homepage](https://http://keras.io/)\] **_keras_** - a (very) high-level library for building the deep learning models. Under the hood Keras uses Theano or Tensorflow as its engine. It won't let you build your own innovative neural network algorithms, but it will surely let you play with most established ones, and build prototypes quickly.


## Alternatives to this document

In case you think your profile does not fit mine, you can try one of the alternative point of views:
