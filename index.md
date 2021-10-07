This is an introductory course in the theory of statistics, inference, and machine learning, with an emphasis on theoretical understanding & practical exercises. The course will combine, and alternate, between mathematical theoretical foundations and practical computational aspects in python.

**Professor:** Florent Krzakala

**Teaching Assistants:** Davide Ghio, Ortiz Jimenez Guillermo,  Dimitriadis Nikolaos, Luca Pesce

### Content
The topics will be chosen from the following basic outline:

- Statistical inference: Estimators, Bias-Variance, Consistency, Efficiency, Maximum likelihood, Fisher Information.
- Bayesian inference, Priors, A posteriori estimation, Expectation-Minimization.
- Supervised learning : Linear Regression, Ridge, Lasso, Sparse problems, high-dimensional Data, Kernel methods, Boosting, Bagging. K-NN, Support Vector Machines, logistic regression, Optimal Margin Classifier
- Statistical learning theory: VC Bounds and Uniform convergence, Implicit regularisation, Double-descent
- Unsupervised learning : Mixture Models, PCA & Kernel PCA, k-means
- Deep learning: multi-layer nets, convnets, auto-encoder, Gradient-descent algorithms
- Basics of Generative models & Reinforcement learning


For students: [Moodle Link](https://moodle.epfl.ch/course/view.php?id=16783) & videos of the course on [TubeSwitch](https://tube.switch.ch/channels/P21dFjFlzG)

Discussions: You can discuss and ask questions on the course. We use slack, which is a great platform for this, here is the invitation to join the forum [forum on slack](https://join.slack.com/t/lecturee411-2021/shared_invite/zt-wctokqj5-Gsk8mp790JmMjDakedJArA) which is valid until the end of october.


### Lecture List:

Short video on [introduction and course information](https://tube.switch.ch/videos/OtMpZ1csbC)

* **21/9: (i) All of probability** [video part-a](https://tube.switch.ch/videos/O5cTqs2NT7),[video part-b](https://tube.switch.ch/videos/9GNFirFjRw) [video part-c](https://tube.switch.ch/videos/hg4GoRppXj); [lecture notes](https://www.overleaf.com/1222519813bdjmdjmjjpbx)
 
This first class is a recap on probability theory that will serve us well in this class. A good reference, and an absolutly recommended reading, for this lecture is Chap. 1-5 in [All of statistics](http://egrcc.github.io/docs/math/all-of-statistics.pdf) by Wasserman. 

* **28/9: (ii) All of statistics** [video part-a](https://tube.switch.ch/videos/B3r56XLIvj),[video part-b](https://tube.switch.ch/videos/BpUsMuh7p3). Notes in preparation. [Manuscripts notes](https://github.com/IdePHICS/FundamentalLearningEPFL2021/blob/main/WrittenNotes/Lec2.pdf)

This second class is focused on the theory of [maximum likelihood estimation](https://en.wikipedia.org/wiki/Maximum_likelihood_estimation). There are many good references on the topic, including for instance chap. 9 in [All of statistics](http://egrcc.github.io/docs/math/all-of-statistics.pdf), or for the Bayesian point of view, [MacKay](http://www.inference.org.uk/itprnn/book.pdf) chap 2 and 3.

* **5/10: (iii) Supervised learning and KNN** [video part-a](https://tube.switch.ch/videos/y0T46zQ8Uz),[video part-b](https://tube.switch.ch/videos/WPxmNebck8). Notes in preparation. 

A good read on supervised statistical learning is chapter 2 in [An Introduction to Statistical Learning](https://www.statlearning.com/) by James, Witten, Hastie and Tibshirani. They also discuss in detail K-neareast neighbors.


### Lab classes:

* Before the classes: [A short intro to python](TP0/Intro%20to%20Python.ipynb) and to vizualization and making plots with [Matplotlib](TP0/Visualization.ipynb)).

* Week 1 (22/9): Introduction to statistics with python [EXO1](TP1/FoIL_ex1_public.ipynb);[Solution](TP1/solution/FoIL_ex1_solved.ipynb)

* Week 2 (29/9): Estimation with maximum likelihood [EXO2](TP2/FoIL_ex2_public.ipynb);[Solution](TP2/solution/FoIL_ex2_solved.ipynb)

* Week 3 (6/10): Supervised learning with kNN [EXO3](TP3/TP3_FoIL_public.ipynb)

### Homeworks: 

* HW1 (Due october 19, on moodle) [Maximum likelihood and Probability](https://github.com/IdePHICS/FundamentalLearningEPFL2021/blob/main/HW/Homework1_EE411.pdf)

### Projects: TBD

### A list of references

* A good book for probability and statistics, accessible to students, is Larry A. Wasserman 's <a href="https://www.ic.unicamp.br/~wainer/cursos/1s2013/ml/livro.pdf">All of Statistics</a>. 
* An accessible introduction to statistical learning is given in <a href="https://web.stanford.edu/~hastie/ElemStatLearn/">Elements of Statistical Learning </a> by Jerome H. Friedman, Robert Tibshirani, and Trevor Hastie. 
* Another great reference is <a href="https://www.amazon.com/Machine-Learning-Probabilistic-Perspective-Computation/dp/0262018020">Machine Learning:A Probabilistic Perspective<a/> by Kevin P. Murphy. MacKay's <a href="https://www.amazon.com/Machine-Learning-Probabilistic-Perspective-Computation/dp/0262018020">Machine Learning:A Probabilistic Perspective <a href="https://www.inference.org.uk/itprnn/book.pdf">Information Theory, Inference and Learning Algorithms</a> is also a very useful ressource.
* Modern Deep learning is well covered in this recent book:
<a href="http://d2l.ai/">Dive into Deep Learning<a/> by A. Zhang, Z. Lipton, M. Li, A.J. Smola. 
* Un recent, et excellent, livre de reference en Francais: <a href="https://www.amazon.fr/Introduction-Machine-Learning-Chloé-Agathe-Azencott/dp/2100780808">Introduction au Machine Learning </a> par Chloé-Agathe Azencott. 
  
  
### Course Policies

* Homeworks: There will be three homework assignments, each worth 15% of the final grade. 
* Scribing: Each students is expected to provide scribing for at least one lecture. Scribing will also count for 15% of the final grade.
  Student must write their name on the list of scribes and claim lectures on [the scribing list](https://docs.google.com/document/d/13N8_0I5Waz566e3IlQPDKKMZNXvGN5vQYaYAh0Dl6kk/edit?usp=sharing) together with ready-to-se overleaf links (see latex section below).   
* Projects: Project will account for 40% of the final grade. You may work in teams of 2-4 people. There will be a limited number of project to choose from, and you will not be able to chose other projects. Each team member's contribution should be highlighted. You should use the project as an opportunity to "learn by doing".
* Exam: There will be no written exam.
* Videos: videos of the lecture will be posted on the [SwichTube channel](https://tube.switch.ch/channels/P21dFjFlzG) of the course.
* Academic Integrity: Collaboration among students is allowed, and encouraged, but is intended to help you learn. In other words, you may work on solving assignments together, but you should always write up your solutions separately. You should always implement code alone as well. Whenever collaboration happens, it should be reported by all parties involved in the relevant homework problem.
 
### FAQ
* How can I use python on my computer? 
 
Two good options to run python online are EPFL Noto & Google Colab. [Noto](https://www.epfl.ch/education/educational-initiatives/cede/digitaltools/jupyter-notebooks-for-education/) is EPFL’s JupyterLab centralized platform. It allows teachers and students to use notebooks without having to install python on their computer. [Google colab](https://research.google.com/colaboratory/) provides a similar solution, with the added avantage that it gives access to GPUs. For instnace, you can open the jupyter notebook corresponding to the first exercice by a) opening google colab in your browser) b) selecting github, and  c) writing the path `https://github.com/IdePHICS/FundamentalLearningEPFL2021/blob/main/TP1/FoIL_ex1_public.ipynb`

* I do not know any python! What should I do? 

[TP0](https://github.com/IdePHICS/FundamentalLearningEPFL2021/tree/main/TP0) provides a short introduction. If you need more and really need to study python, here is a a good [Python and NumPy Tutorial](https://github.com/kuleshov/cs228-material/blob/master/tutorials/python/cs228-python-tutorial.ipynb).
 
* What is overleaf? 
 
 If you cannot compile LaTeX on your own computer (and even if you can, this is often a good strategy anyway), EPFL is providing Overleaf Professional accounts for all students: [Overleaf EPFL](https://www.overleaf.com/edu/epfl#overview) . With Overleaf you can write and compile LaTeX directly from your web browser. 
