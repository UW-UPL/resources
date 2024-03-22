# Resources
Various resources for everything you'd want to learn about software development!

## Class resources
- [Operating Systems: Three Easy Pieces (OSTEP)](https://pages.cs.wisc.edu/~remzi/OSTEP/): The OS textbook, freely available online, written by Remzi and Andrea Arpaci-Dusseau, two professors at the University of Wisconsin-Madison. This website also includes the homework assignments that correspond with each chapter of the book, as well as other books they recommend.

## Articles

### Programming advice

- [Why learning to code is so damn hard](https://web.archive.org/web/20150207060837/http://www.vikingcodeschool.com/posts/why-learning-to-code-is-so-damn-hard): One of the best blog posts that details the process of learning programming.
- [The Best of edw519](http://static.v25media.com/edw519_mod.html#chapter_255): A collection of comments by a very experienced software developer, covering a wide range of topics.
- [Development is Inherently Wicked](https://blog.codinghorror.com/development-is-inherently-wicked/): An article talking about software development metholodogy through the lens of "Wicked Problems".
- [Reflections on a decade of coding](https://www.scattered-thoughts.net/writing/reflections-on-a-decade-of-coding/): An interesting series of posts by a guy reflecting on his learnings after a decade of programming professionally.
- [Why I find it hard to learn with AI](https://andresc.substack.com/p/why-i-find-it-hard-to-learn-with): A blog post about how products like ChatGPT and GitHub Copilot can disrupt the natural processes of learning (especially important to consider for early-career developers).
- [TigerStyle](https://github.com/tigerbeetle/tigerbeetle/blob/main/docs/TIGER_STYLE.md): A phenomenal document outlining the design principles and goals of TigerBeetle, a high-performance, distributed, in-memory database.
- [Becoming a Better Programmer by Tightening Feedback Loops](https://siboehm.com/articles/22/tight-feedback-loops): An article detailing an approach to becoming a better developer.

### Projects

- [Challenging projects every programmer should try](https://austinhenley.com/blog/challengingprojects.html): Unsure what to build? Here's a list of projects that will challenge you and help you grow as a developer.
- [Coding Challenges](https://codingchallenges.fyi/challenges/intro): A series of backend coding challenges that test your knowledge as a developer, all of which involve recreating commonly used software tools.
- [Flappy Bird Implemented in Typescript types](https://zackoverflow.dev/writing/flappy-bird-in-type-level-typescript/): Seriously.
- [Vanilla Todo](https://github.com/morris/vanilla-todo): A github repository in which the developer details his approach to creating a Todo app (basic exercise for people learning frontend development and React) using vanilla JavaScript, HTML, and CSS. If you are interested in the engineering underlying frontend development, this will make you drool.
- [JavaScript xv6](https://nullpo-head.github.io/emcc-gaia-simu/xv6.html): An implementation of xv6 (the operating system we hack on in CS 537) in JavaScript, which is crazy. It even has a game of 2048 built in.
- [Writing a C compiler in 500 lines of Python](https://vgel.me/posts/c500/): A blog post on someone's approach to writing a simple C compiler in 500 lines of Python. The author holds your hand and walks you through the process of compiler development.

### General Blogs and posts

- [Every Vim Binding Lucas Knows](https://scharenbroch.dev/blog/vim-bindings/): A list of well-known and less-known Vim bindings.
- [How to Optimize a CUDA Matmul Kernel for cuBLAS-like Performance: a Worklog](https://siboehm.com/articles/22/CUDA-MMM): A very in-depth article about optimizing a matrix multiplication operatin in CUDA.
- [How Lisp became God's own programming language](https://twobithistory.org/2018/10/14/lisp.html): A blog post describing the origins and history of Lisp and it's lasting impact on the field of software development.
- [Venture Capital and the Internet's Impact](https://stratechery.com/): A 2015 blog post that talks about how AWS disrupted traditional venture capital in tech and the emergence of angel investors, Silicon Valley engineers and veterans of the startup scene. I (Rudy) believe this article is slightly outdated, considering the waves of new engineers and the 2022 tech market contractions, but it still provides an interesting look at underlying investment forces with startups.
- [Computational Photography](https://vas3k.com/blog/computational_photography/): A very detailed blog post about the evolution of computational photography and the algorithms behind modern camera system innovations.
- [Socket Programming overview in Python](https://docs.python.org/3/howto/sockets.html): An overview of sockets programming with Python code snippets. Sockets are a fundamental abstraction for programs sending and receiving data across the internet using the IP protocol.
- [Why Type Hinting Sucks!](https://old.reddit.com/r/Python/comments/10zdidm/why_type_hinting_sucks/): An entertaining reddit post describing why Python type hinting sucks from the perspective of evolving project requirements and code maintanence over time.
- [Learning about distributed systems: where to start?](https://muratbuffalo.blogspot.com/2020/06/learning-about-distributed-systems.html): A blog post about how to get more in-depth experience with distributed systems. Personally I (Rudy) think this is bad advice for early career developers, and instead I'd recommend building basic full-stack applications that have a frontend, backend, database, authentication, etc for getting more hands-on experience with distributed systems. I personally tried avoiding JavaScript as much as possible, but it is a futile effort.
- [Portable EPUBs](https://willcrichton.net/notes/portable-epubs/): A blog post that provides commentary on various file formats and proposes a new file format standard that takes the best of all worlds (according to the author of course).
- [Rust won't save us, but it's ideas will](https://glitchbyte.io/posts/rust-wont-save-us/): A blog post that organizes some of the commentary about the Rust programming language from a security perspective.
- [A friendly introduction to machine learning compilers and optimizers](https://huyenchip.com/2021/09/07/a-friendly-introduction-to-machine-learning-compilers-and-optimizers.html): A blog post that provides an overview of machine learning compilers and optimizers. Overall a very good article, but the author included a meme about writing models in JavaScript so they can run natively on the browser, which I (Rudy) am ideologically opposed to.
- [The engineering behind Figma's vector networks](https://alexharri.com/blog/vector-networks): A blog post detailing the graphics math behind vector networks.
- [Just paying figma 15 dollars a month because nothing else fucking works](https://fasterthanli.me/articles/just-paying-figma-15-dollars): A blog post that talks about the dilemmas of Free and Open Source Software (FOSS), and what makes Figma a world-class product.
- [From 1s to 4ms](https://registerspill.thorstenball.com/p/from-1s-to-4ms): A walkthrough about how a developer managed to target and solve a huge performance bottleneck in a text editor.
- [Files are fraught with peril](https://danluu.com/deconstruct-files/): An article that goes into depth about how writing to files works at the system call level, and how the simple act of writing to a file can go wrong.

### Papers
- [A Unified Theory of Garbage Collection](https://www.cs.cornell.edu/courses/cs6120/2019fa/blog/unified-theory-gc/): A summary of a research paper proposing fundamental laws about garbage collection based on observations of different types of garbage collectors and trends of object allocation and object lifetimes in different programs. Understanding garbage collection can have interesting performance implications.
- [Modern B-Tree Techniques](https://w6113.github.io/files/papers/btreesurvey-graefe.pdf): A long document that talks about B-trees and performance techniques that people use for implementing them in modern database systems.
- [The NumPy array: a structure for efficient numerical computation](https://arxiv.org/pdf/1102.1523.pdf): A paper detailing how the NumPy array works under the hood for efficient computation.

## Talks
- [Systems Distrubted](https://www.youtube.com/playlist?list=PL9eL-xg48OM09LwyjF_cXwoJHHngXMPxJ): A conference by TigerBeetle about various programming and database/systems design techniques and considerations, by a variety of very smart and eloquent people doing cutting-edge work.
- [Containers: Reflections after the first decade](https://youtu.be/xXWaECk9XqM): An entertaining talk about some of the origins and motivations for developing containers. Good advice for any software developer.
- [Why Static Typing Came Back](https://youtu.be/Tml94je2edk): A talk about the history of Static vs Dynamic languages, motivations for using both types, and a glimpse into the frontier of language design.
- [Python India Keynote - David Beazley](https://youtube.com/watch?v=VUT386_GKI8): David Beazley writes an entire WebAssembly interpreter in a live-demo.
- [Applicative: The Forgotten C++ Functional Pattern - Ben Deane](https://www.youtube.com/watch?v=KDn28TZdKb4): A C++ (!) talk motivating the practical use of functional patterns.
- [Simple Made Easy - Rich Hickey](https://youtube.com/watch?v=LKtk3HCgTa8): The famous talk in which Rich Hickey defines the terms "simple" and "easy".
- [Growing a Language - Guy Steele](https://www.youtube.com/watch?v=_ahvzDzKdB0): A programming-languages talk with an unusual constraint.
- [Four Solutions to a Trivial Problem - Guy Steele](https://www.youtube.com/watch?v=ftcIcn8AmSY): Kind of like a leetcode-solution video, but with more commentary on parallelism.
- [Expert to Expert: Rich Hickey and Brian Beckman - Inside Clojure](https://www.youtube.com/watch?v=wASCH_gPnDw): A discussion about the novel ideas used by data structures Clojure.
- [Learning Rust the wrong way - Ólafur Waage](https://youtube.com/watch?v=DL9LANLg5EA): A non-technical talk about various ideas surrounding learning.
- [It's not what you read, it's what you ignore - Scott Hanselman](https://youtube.com/watch?v=IWPgUn8tL8s): A talk about workflow-optimization as a full-time dev.
- [Why are distributed systems so hard?](https://www.youtube.com/watch?v=Q4p-2WIS0nQ): A good overview of the challenges faced with distributed programming.

## Free Lecture-Series
- [MIT 6.006: Intro to Algorithms (Fall 2011)](https://www.youtube.com/watch?v=HtSuA80QTyo&list=PL-K_ib5mxHXkBD_3_79TPS8xvcw49pVcc): Covers most of the DSA ideas in CS 300, 400, 240, and 577, with way less nonsense and a lot of great examples and insights.
- [MIT 6.001: Structure and Interpretation of Computer Programs (SICP) (1986)](https://www.youtube.com/playlist?list=PLE18841CABEA24090): The legendary lecture videos accompanying the [classic (now free) textbook](https://web.mit.edu/6.001/6.037/sicp.pdf) of the same name.
- [MIT 6.5940: TinyML and Efficient Deep Learning Computing](https://www.youtube.com/playlist?list=PL80kAHvQbh-pT4lCkDT53zT8DKmhE0idB): This course covers strategies and theory for getting efficient model inference, optimizations for transformers, and efficient model training. The official course website is [here](https://hanlab.mit.edu/courses/2023-fall-65940).
- [David Beazley - Advanced Python Mastery](https://github.com/dabeaz-course/python-mastery/tree/main): A github repository containing code exercises and slides from an Advanced Python Mastery course. If you are interested at learning about Python at an advanced level, feel free to skim the exercises in the repository and try completing some of them if they look interesting enough.

## Extra
- [Windows Drama](https://news.ycombinator.com/item?id=30019307): Some rumors about internal engineer vs designer beef within the Windows teams. Those who are frustrated by the directions Windows is going might be interested in how organizational drama can affect the development of a product, even one as big and widely used as Windows.
- [First version of Redis written in TCL](https://gist.github.com/antirez/6ca04dd191bdb82aad9fb241013e88a8): A copy of the code used in the first version of Redis. If you ignore the fact that nobody actually knows TCL anymore, this is an interesting read, especially for trying to guess how the code works in a language you've never seen before. Plus some commentary from the original author and others in the comments.
- [Secret React Internals](https://github.com/facebook/react/blob/main/packages/shared/ReactSharedInternals.js): Secret react internals. Originally brought up in [this](https://stackoverflow.com/questions/68930011/react-accessing-internal-operation-queue-of-react) stackoverflow post and again in [this](https://github.com/reactjs/react.dev/issues/3896) github issue.
