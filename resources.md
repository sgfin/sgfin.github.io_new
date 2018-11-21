---
layout: page
title: ML Resources
permalink: /learning-resources/
---

<style>
table {
  border-collapse: collapse;
}
th, td {
    border: 1px solid #999;
}
table a:link, table a:visited, table a:active{
    color: blue;
}
</style>


This is a not-particularly-systematic attempt to curate a handful of my favorite resources for learning statistics and machine learning.  This isn't meant to be comprehensive, and in fact is still missing the vast majority of my favorite explainers.  Rather, it's just a smattering of resources I've found myself turning to multiple times and thus would like to have in one place.  The organizatiion is as follows:

- [_Open Courses and Textbooks_](#courses):  Cover a fairly *broad* topic reasonably *comprehensively*, and would take *weeks to months* to work through start-to-finish.

- [_Tutorials, Overviews, and (Individual) Lecture Notes_](#tutorials): Explain a *specific* topic extremely *clearly*, and take *minutes to hours* (or a few days tops) to work through from start-to-finish.

- [_Cheatsheets_](#cheatsheets): Provide structured access to useful bits of information on the order of *seconds*.

Finally, I've added a section with links to [a few miscellanous websites](#misc) that often produce great content.

Of the above, the second section is both the most incomplete and the one that I am most excited about.  I hope to use it to capture the best explanations of tricky topics that I have read online, to make it easier to re-learn them later when I inevitably forget.  (In a perfect world, [Chris Olah](http://colah.github.io/) and/or [distill.pub](https://distill.pub) would just write an article on everything, but in the meantime I have to gather scraps from everywhere else.)

If you stumble upon this list and have suggestions for me to add (especially for the middle section!), please feel free to reach out!  But I'm only trying to post things on here that I've read, so it may be caught in my to-read list for a while before it makes it on here.  Of course, the source for this webpage is [on github](https://github.com/sgfin/sgfin.github.io/blob/master/resources.md), so you can also just take it.


## <a name="courses"></a> Open Courses and Textbooks

I'm trying to limit to this list to things that are legally accessible online, for free.

### Foundation

| File | Description   |
| :-----------: |:-------------:|
|  [Math for ML Book](/files/notes/mml-book.pdf)  |  Math for machine learning book by Faisal and Ong, available on [github](https://mml-book.github.io/). |
|  [Boyd Applied Linear Algebra](http://vmls-book.stanford.edu/vmls.pdf)  |  Freely available book from Boyd and Vandenberghe on Applied LA ([website](http://vmls-book.stanford.edu/)). |
| [Fast.ai Computational Linear Algebra](https://github.com/fastai/numerical-linear-algebra/blob/master/README.md) | Rachel Thomas has put together this great online textbook for computational linear algebra with accompanying [youtube videos](https://www.youtube.com/playlist?list=PLtmWHNX-gukIc92m1K0P6bIOnZb-mg0hY). |
| [MIT 6.041 Intro Probability](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-041-probabilistic-systems-analysis-and-applied-probability-fall-2010/) | John Tsitsiklis et al have put together some great resources. Their classic MIT intro to probability has been archived on [OCW](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-041-probabilistic-systems-analysis-and-applied-probability-fall-2010/) and also offered on Edx ([Part 1](https://www.edx.org/course/introduction-probability-part-1-mitx-6-041-1x), [Part 2](https://www.edx.org/course/introduction-to-probability-part-2-inference-processes)). The [textbook](https://www.amazon.com/Introduction-Probability-2nd-Dimitri-Bertsekas/dp/188652923X) is also excellent. |
| [Joe Blitzstein's Stat110](https://projects.iq.harvard.edu/stat110/about) | Joe Blitzstein's undergrad probability course has a high overlap in content with 6.041. Like 6.041, it also has a great [textbook](https://www.amazon.com/Introduction-Probability-Chapman-Statistical-Science/dp/1466575573/ref=sr_1_1?s=books&ie=UTF8&qid=1541876707&sr=1-1&keywords=blitzstein), [youtube](https://projects.iq.harvard.edu/stat110/youtube) videos, and an [edx](https://www.edx.org/course/introduction-to-probability-0) offering. It's a bit more playful, as well.|
|[MathematicalMonk](https://www.youtube.com/user/mathematicalmonk)| This guy is amazing. Some 250 youtube tutorials on ML, Probability, and Information Theory.  What's great about these playlists is any individual video could go into section 2!|


### Statistics

| File | Description   |
| :-----------: |:-------------:|
|  [Doug Sparks' Stats 200](/files/notes/Stat200_2014_Merged_Sparks.pdf)  |  Nice course notes on Statistical Inference from Doug Sparks 2014 offering of [stats 200](http://stats200.stanford.edu/) |
|  [Modern Statistics for Modern Biology](https://www-huber.embl.de/msmb/)  |  This online textbook is from Susan Holmes and Wolfgang Huber, and provides a nice and accessible intro to the parts of modern data science revelant to computational biologists.  It also happens to be a piece of typographic *art*, created with [bookdown](https://bookdown.org/yihui/bookdown/).  |
|  [Statistical Rethinking](https://xcelab.net/rm/statistical-rethinking/)  |  Lecture Videos on [youtube](https://www.youtube.com/playlist?list=PLDcUM9US4XdM9_N6XUUFrhghGJ4K25bFc) accompany this very well-reviewed introductory textbook. |
|  [Hernan and Robbins Causal Inference Book](https://www.hsph.harvard.edu/miguel-hernan/causal-inference-book/)  |  Long-upcoming textbook on causal inference (from the epidemiology perspective), with drafts fairly frequently updated on the web page. |


### Classic Machine Learning 

| File | Description   |
| :-----------: |:-------------:|
|  [CS 229 Lecture Notes](/files/notes/CS229_Lecture_Notes.pdf)  |  Classic note set from Andrew Ng's amazing grad-level intro to ML: [CS229](http://cs229.stanford.edu/syllabus.html). |
|  [ESL](https://web.stanford.edu/~hastie/ElemStatLearn/printings/ESLII_print12.pdf) and [ISL](http://www-bcf.usc.edu/~gareth/ISL/ISLR%20Seventh%20Printing.pdf) from Hastie et al |  Beginner (ISL) and Advanced (ESL) presentation to classic machine learning from world-class stats professors. Slides and video for a MOOC on ISL is available [here](https://www.dataschool.io/15-hours-of-expert-machine-learning-videos/). |
|  [CS 228 PGM Notes](https://ermongroup.github.io/cs228-notes/)  |  Really great course notes on Probabilistic Graphical Models from at Stanford. PDF export wasn't ideal so linking only to website.|
|  [Blei Foundations of Graphical Models Course](http://www.cs.columbia.edu/~blei/fogm/2016F/index.html)  |  2016 course notes on Foundations of Graphical Models from David Blei 2016 website|


### Deep Learning

| File | Description   |
| :-----------: |:-------------:|
| [Roger Grosse's CSC231 Notes](/files/notes/CS229_Linear_Algebra.pdf)  |  Notes from Roger Grosse's CSC 231 [full website here](http://www.cs.toronto.edu/~rgrosse/courses/csc321_2018/). Probably the single best intro to DL course I've found from any university. Notes and slides are gorgeous.|
|  [Fast.Ai](https://www.fast.ai/)  |  Wonderful set of intro lectures + notebooks from Jeremy Howard and Rachel Thomas. In addition, Hiromi Suenaga has released excellent and self-contained notes of the whole series with timestamp links back to videos: [FastAI DL Part 1](https://www.kdnuggets.com/2018/07/fast-ai-deep-learning-part-1-notes.html), [FastAI DL Part 2](https://www.kdnuggets.com/2018/07/fast-ai-deep-learning-part-2-notes.html), and [FastAI ML](https://www.kdnuggets.com/2018/07/suenaga-fast-ai-machine-learning-notes.html). |
|  [CS231N DL for Vision](http://cs231n.github.io/)  |  Amazing notes from Andrej Karapthy, with lectures on Youtube as well. |
|  [CS224 Deep Learning for NLP 2017](/files/notes/CS229_Linear_Algebra.pdf)  |  Fantastic course notes on Deep Learning for NLP from Stanford's [CS224](http://web.stanford.edu/class/cs224n/). Github repo [here](https://github.com/stanfordnlp/cs224n-winter17-notes/blob/master/notes1.pdf) |
|  [CMU CS 11-747](http://www.phontron.com/class/nn4nlp2018/schedule.html)  |  Fantastic course  on Deep Learning for NLP from CMU's Graham Neubig. Really great lecture videos on Youtube [here](https://www.youtube.com/playlist?list=PLbdKUKMAnh9Qqs5uwEBDfRb_L3YaLbRKq) |
| [Deep Learning Book](https://www.deeplearningbook.org) | This textbook by Ian Goodfellow, Yoshua Bengio, and Aaron Courville is probably the closest we have to a de facto standard textbook for DL. |


### Reinforcement Learning

| File | Description   |
| :-----------: |:-------------:|
|[Sutton and Barto Open RL Book](http://incompleteideas.net/book/the-book-2nd.html)| De-facto standard intro to RL, even though the textbook is only now about to be published!|
|[Berkeley Deep Reinforcement Learning](http://rll.berkeley.edu/deeprlcourse/)| RL class from Berkely taught by top dogs in the field, lectures posted to Youtube.|


### Optimization

| File | Description   |
| :-----------: |:-------------:|
|[Boyd Convex Optimization Book](http://web.stanford.edu/~boyd/cvxbook/bv_cvxbook.pdf)| Famous and freely available textbook from Boyd and Vandenberghe, accompanied by [slides](https://web.stanford.edu/class/ee364a/lectures.html) and Youtube videos. More advanced follow-up class [here](https://web.stanford.edu/class/ee364b/lectures.html)|
|  NYU Optimization-based Data Analysis [2016](/files/notes/NYU_Optimization_2016.pdf) and [2017](/files/notes/NYU_Optimization_2017.pdf) |  Fantastic course notes on Optimization-based data analysis from NYU [2016 website](https://cims.nyu.edu/~cfgranda/pages/OBDA_spring16/notes.html) and [2017 website](https://cims.nyu.edu/~cfgranda/pages/OBDA_fall17/schedule.html). |



## <a name="tutorials"></a> Tutorials, Overviews, and (Individual) Lecture Notes

This section is fledgling at best, but was my real motivation in making this page. Archetypes include basically anything on distill.pub, good blog or medium posts, etc.  Depth-first learning looks like a great access point here, but I haven't gotten to do more than skim any of those, yet.


### Fundamentals

| File | Description   |
| :-----------: |:-------------:|
|  [CS 229 Linear Algebra Notes](/files/notes/CS229_Linear_Algebra.pdf)  |  Linear algebra reference from Stanford's Machine Learning [Course](http://cs229.stanford.edu/materials.html). |
|  [Matrix Calc for DL](https://explained.ai/matrix-calculus/index.html) [(pdf here)](/files/notes/Matrix_Calc_for_DL.pdf)  |  Really nice overview of matrix calculus for deep learning from Parr/Howard.  Citable on on [arxiv](https://arxiv.org/abs/1802.01528). |


### Probability and Statistics

| File | Description   |
| :-----------: |:-------------:|
|  [Hernan Selection Bias](/files/notes/structured_approach_selection_bias_Hernan.pdf)  |  Nice summary of selection bias via DAGs by Hernan et al. |


### Classic Machine Learning/Data Science NOS

| File | Description   |
| :-----------: |:-------------:|
|  [Roughgarden SVD Notes](/files/notes/CS168_Roughgarden_SVD.pdf)  |  Really great presentation of SVD from [Tim Rougharden's CS168](https://web.stanford.edu/class/cs168/index.html) at Stanford. |
|  [Roughgarden PCA Notes](/files/notes/CS168_Roughgarden_PCA.pdf)  |  Really great presentaiton of PCA from [Tim Rougharden's CS168](https://web.stanford.edu/class/cs168/index.html) at Stanford. |


### Bayesian Machine Learning

| File | Description   |
| :-----------: |:-------------:|
[Blei Exponential Familes/Variational Inference](/files/notes/blei_exponFam_varInf.pdf)| A couple of the course notes I particularly like from Blei's [2011 Probabilistic Modeling Course](https://www.cs.princeton.edu/courses/archive/fall11/cos597C/) )
|  [Blei Variational Inference Review](/files/notes/blei_variational_review.pdf) |  Overview on Variational Inference from David Blei available on [arxiv](https://arxiv.org/abs/1601.00670)|


### Deep Learning 

| File | Description   |
| :-----------: |:-------------:|
|Adversarial Examples/Robust ML [Part 1](http://people.csail.mit.edu/madry/lab/blog/adversarial/2018/07/06/adversarial_intro/), [Part 2](http://people.csail.mit.edu/madry/lab/blog/adversarial/2018/07/11/robust_optimization_part1/), and [Part 3](http://people.csail.mit.edu/madry/lab/blog/adversarial/2018/08/10/robust_optimization_part2/) | The [Madry lab](https://people.csail.mit.edu/madry/lab/) is one of the top research groups in robust deep learning research. They put together a fantastic intro to these topics on their blog. I hope they keep making posts... |
|[Distill Attention](https://distill.pub/2016/augmented-rnns/)| Amazingly clear presentation of the attention mechanism and its (early) variants |
|[Distill Building Interpretability](https://distill.pub/2018/building-blocks/)| Coolest visualizations of NN internals I've ever seen|
|[Distill Feature Visualization](https://distill.pub/2017/feature-visualization/)| Running theme: If it's only distill.pub, read it. |
|[Chris Olah Understanding LSTMs](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)| Chris Olah is a master of his craft, and here offers a fantastic overview of LSTMs and GRUs.|


### Natural Language Processing

| File | Description   |
| :-----------: |:-------------:|
|[Chris Olah on Word Embeddings](http://colah.github.io/posts/2014-07-NLP-RNNs-Representations/)| Chris Olah explaining world embeddings and the like.|
|[The Annotated Transformer](http://nlp.seas.harvard.edu/2018/04/03/attention.html)| Harvard's Sasha Rush created a line-by-line annotation of "Attention is All You Need" that also serves as a working notebook. Pedagogical brilliance, and it would be awesome to do this for a couple papers per year.|
|  [Goldberg's Primer on NNs for NLP](/files/notes/Goldber_Primer_Neural_Nets_NLP.pdf)  |  Overview of Deep Learning for NLP from Yoav Goldberg [downloaded from here](http://u.cs.biu.ac.il/~yogo/nnlp.pdf). |
|  [Neubig's Tutorial on NNs for NLP](/files/notes/neubig_nmt_seq2seq.pdf)  |  Overview of Deep Learning for NLP from Graham Neubig. Downloaded from [arxiv](https://arxiv.org/pdf/1703.01619.pdf) and pairs nicely with his course and videos. |


### Reinforcement Learning 

| File | Description   |
| :-----------: |:-------------:|
|[Karpathy's Pong From Pixels](http://karpathy.github.io/2016/05/31/rl/)| Andrej Karpathy has a real gift for didactics. This is a self-contained explanation of deep reinforcement learning sufficient to understand a basic atari agent. |
|[Weng's A (Long) Peek into RL](https://lilianweng.github.io/lil-log/2018/02/19/a-long-peek-into-reinforcement-learning.html)| A nice blog post covering the foundations of reinforcement learning|
|[OpenAI's Intro to RL](https://spinningup.openai.com/en/latest/spinningup/rl_intro.html)| The introductory tutorial for OpenAIs new ["Spinning Up in Deep RL" website](https://blog.openai.com/spinning-up-in-deep-rl/) |

### Information Theory

| File | Description   |
| :-----------: |:-------------:|
|[Chris Olah Visual Information Theory](http://colah.github.io/posts/2015-09-Visual-Information/)| As always, Chris Olah creates an amazing presentation both in words and images.  Goal is to visualize key information theory concepts.|
|[Cover and Thomas Ch2 - Entropy and Information](/files/notes/Cover_and_Thomas_ch2_entropy.pdf)| The extremely well-written introductory chapter from the classic information theory textbook.|
|[Cover and Thomas Ch11 - Info Theory and Statistics](/files/notes/Cover_and_Thomas_ch11_info_and_stats.pdf)| The information theory and statistics chapter from the classic information theory textbook.|
|[Deriving Probability Distributions from Maximum Entropy Principle](https://sgfin.github.io/2017/03/16/Deriving-probability-distributions-using-the-Principle-of-Maximum-Entropy/)| It feels slimey and self-serving to include this, but I wrote this post to better understand how information theory can be used to understand/derive common probability distributions from first principles.|
|[Deriving the information entropy of the multivariate gaussian](https://sgfin.github.io/2017/03/11/Deriving-the-information-entropy-of-the-multivariate-gaussian/)| Another blog post I wrote to try to understand information theory + statistics.|


### Optimization

| File | Description   |
| :-----------: |:-------------:|
| [Ruder Gradient Descent Overview](http://ruder.io/optimizing-gradient-descent/index.html) [(PDF here)](/files/notes/ruder_gradient.pdf) |  Great overview of gradient descent algorithms. |
|  [Bottou Large-Scale Optimization](/files/notes/bottou_optimization.pdf) |  Notes on Optimization from Bottou, Curtis, and Nocedal. Downloaded from [arxiv](https://arxiv.org/abs/1606.04838). |


## <a name="cheatsheets"></a> Cheatsheets

### Math

| File | Description   |
| :-----------: |:-------------:|
|  [Probability Cheatsheet](/files/cheatsheets/probability_cheatsheet_blackwhite.pdf) |  Probability cheat sheet, from William Chen's [github](https://github.com/wzchen/probability_cheatsheet)|
|  [CS 229 TA Cheatsheet 2018](/files/cheatsheets/cs229_2018_cheatsheet.pdf)  |  TA cheatsheet from the 2018 offering of Stanford's Machine Learning [Course](http://cs229.stanford.edu/materials.html), Github repo [here](https://github.com/afshinea/stanford-cs-229-machine-learning). |
|  [CS Theory Cheatsheet](/files/cheatsheets/CS_theory_cheat_sheet.pdf)  |  CS theory cheat sheet, originally accessed [here](https://www.tug.org/texshowcase/cheat.pdf)|

### Programming

| File | Description   |
| :-----------: |:-------------:|
|  [R dplyr cheatsheet](/files/cheatsheets/R_cheatsheet_dplyr.pdf)  |  Cheatsheet for Hadley's amazing data wrangling package, dplyr. One of many from [RStudio](https://www.rstudio.com/resources/cheatsheets/) |
|  [R ggplot2 cheatsheet](/files/cheatsheets/R_cheatsheet_ggplot2.pdf)  |  Cheatsheet for Hadley's amazing plotting package, ggplot2. One of many from [RStudio](https://www.rstudio.com/resources/cheatsheets/)|
|  [SQL Joins cheatsheet](/files/cheatsheets/SQL_joins.png)  |  Graphical description of classic SQL joins w/ toy code  |
|  [Python pandas cheatsheet](/files/cheatsheets/Python_cheatsheet_pandas.pdf)  |  Cheatsheet for python's data wrangling package, pandas. Downloaded from [here](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf)|
|  [Python numpy cheatsheet](/files/cheatsheets/Python_cheatsheet_numpy.pdf)  |  Cheatsheet for python's numerical package, numpy. Downloaded from [Datacamp](https://www.datacamp.com)|
|  [Python keras cheatsheet](/files/cheatsheets/Python_Keras_Cheat_Sheet.pdf)  |  Cheatsheet for python's NN package, keras. Downloaded from [Datacamp](https://www.datacamp.com).|
|  [Python scikit-learn cheatsheet](/files/cheatsheets/Python_cheatsheet_scikit.pdf)  |  Cheatsheet for python's ML package, scikit-learn. Downloaded from [Datacamp](https://www.datacamp.com).|
|  [Python seaborn tutorial](https://seaborn.pydata.org/tutorial.html)  |  Tutorial for python's plotting system, seaborn. Haven't found a great one yet for matplotlib. |
|  [Graphic Design cheatsheet](/files/cheatsheets/graphic_design.pdf)  |  Cute little graphic design cheatsheet downloaded from [here](https://www.psiweb.org/docs/default-source/2018-psi-conference-posters/48-julie-jones.pdf) |



## <a name="misc"></a> Miscellaneous websites

| File | Description   |
| :-----------: |:-------------:|
| [Chris Olah's Blog](http://colah.github.io/) | Essentially everything on here is gold. I am so grateful for the hours he must put into these posts.|
|[distill.pub](https://distill.pub)| Distill navigates a really interesting gap between super-blog and research journal. I wish that we had more publications like this. |
|[Pytorch Tutorials](https://pytorch.org/tutorials/) | The tutorials put out by the pytorch developers are really fantastic. Easy to see why the community is growing so fast. |
| [Sebastian Ruder's blog](http://ruder.io/) | Sebastian has produced a lot of really great explanations, like the one on gradient descent methods I linked to above. He also maintains a [website tracking progress on NLP benchmarks](https://nlpprogress.com/)| 
| [ShortScience](http://www.shortscience.org/) | This website contains public summaries/discussions of machine learning, CS, and biology papers. |
| [Berkeley AI Research (BAIR) Blog](https://bair.berkeley.edu/blog/) | BAIR produces a lot of great research, and uses this blog to release more accessible presentations of their papers. | 
| [Off the Convex Path](https://www.offconvex.org/) | Nice blog on machine learning and optimization. | 
| [Ferenc Huszár's blog](https://www.inference.vc/) | Pretty popular blog that has a lot of explorations/musings on ML from an author with a rigorous mathematical perspective | 
|  [Thibaut Lienart's Blog](https://tlienart.github.io/pub/csml.html)  |  This website has some notes on math and optimization that seem interesting.  |



