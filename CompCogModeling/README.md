**Instructors**: [Brenden Lake](https://cims.nyu.edu/~brenden/) and [Todd Gureckis](http://psych.nyu.edu/gureckis/)

**Teaching Assistant**: [Alex Rich](http://www.alexrich.org/)

**Meeting time and location**:  
Tuesdays 6:45 PM - 8:25 PM (lecture)  
Tuesdays 8:25 PM - 9:25 (lab)  
**NOTE ROOM CHANGE: Tisch Hall, 40 West 4th Street, Room LC9 (in Stern business school, lower concourse)**

**Course numbers**:  
PSYCH-GA 3405.002 (Psychology)  
DS-GA 3001.006 (Data Science)

**Contact information and Piazza**:  
We will be using Piazza for questions and class discussion. The system is catered to getting you help fast and efficiently from classmates, the TA, and the instructors. Rather than emailing questions to the teaching staff, we encourage you to post your questions on Piazza.

The signup link for our Piazza page is available here ([https://piazza.com/nyu/spring2018/dsga3001006](https://piazza.com/nyu/spring2018/dsga3001006)).

Once signed up, our class Piazza page is available here ([https://piazza.com/nyu/spring2018/dsga3001006/home](https://piazza.com/nyu/spring2018/dsga3001006/home)).

If there is a need to email the teaching staff directly, please use the following email address: instructors-ccm-spring2018@nyuccl.org.

**Office hours**:  
Todd Gureckis  
todd.gureckis@nyu.edu (Wednesdays 1-2 pm, or by appointment; 6 Washington Place, Meyer, Room 859)  

Brenden Lake  
brenden@nyu.edu (Wednesdays 10-11:00 am, or by appointment; 60 5th Ave., Room 610)  

Alex Rich  
asr443@nyu.edu (Tuesday 12:30-1:30 pm, or by appointment; 6 Washington Place, Meyer, Room 856)  

**Key questions**:
- For cognitive scientists: Can we better understand human learning and thought by developing computational cognitive models?
- For data scientists: Can we better understand behavioral data by developing computational cognitive models?

**Summary**: This course provides a survey of computational approaches to understanding human intelligence and cognition. Both psychologists and data scientists are working with increasingly large quantities of human behavioral data. Computational cognitive modeling is the project of understanding behavioral data (and the mind and brain, more generally) by building computational models of the cognitive processes that produce the data. We will cover the goals, philosophy, and technical concepts behind computational cognitive modeling, including model fitting and evaluation. Readings and lectures will survey various computational approaches, including artificial neural networks / deep learning, Bayesian / structured probabilistic models, symbolic and logical systems, and reinforcement learning. We will cover a broad set of psychological applications of these modeling approaches, including learning, memory, decision making, language, categorization, reasoning, and problem solving. Homework assignments will include implementing some of the modeling ideas surveyed in class. Ideally, students will leave the course with a richer understanding of how computational modeling advances cognitive science, how cognitive science can inform research in machine learning and artificial intelligence, and how to fit and evaluate cognitive models for understanding behavioral data.

Please note that this syllabus is not final and there may be further adjustments.

## Pre-requisites
- Math: If you had linear algebra and calculus as an undergrad, or if you have taken Math Tools in the psychology department, you will be in the best position for approach the material. We will, when needed, review some of the basic technical concepts in lab.
- Programming:For the homework/assignments, we will assume some basic familiarity with programming in Python using the Jupyter Notebook system (http://jupyter.org). We will review some of the programming basics in lab. This is a link to helpful tutorial for learning the basics of Python (http://openbookproject.net/thinkcs/python/english3e/). We recommend Python 3 for use in this course.

## Grading
The final grade is based on homeworks (50%), final project (35%), and attendance/participation (15%).

## Final Project
The final project is due on Tuesday 5/15.

Final project will be done in groups of 2-4 students.  A short paper will be turned in describing the project (approximately 6 pages).  The project will represent either an substantial extension of one of the homeworks (e.g., exploring some new aspect of one of the assignments), implementing and extending an existing cognitive modeling paper, or a written paper discussing one of the core modeling topics.  The final projects will need to be approved by the instructor at least 6 weeks before the end of the semester.

Most write-ups should follow the structure of a standard scientific paper. It should include the following sections: Introduction (with review of related work), Methods/Models, Results, and Discussion/Conclusion. 
A good example would be to follow the structure of this paper from the class readings:
- Peterson, J., Abbott, J., & Griffiths, T. (2016). Adapting Deep Network Features to Capture Psychological Representations. Presented at the 38th Annual Conference of the Cognitive Science Society. [link here](http://cocosci.berkeley.edu/jpeterson/pdf/peterson-cogsci2016-adapting-deep.pdf)

Please submit your final prorject via email to instructors-ccm-spring2018@nyuccl.org with the file name lastname1-lastname2-lastname3-ccm-final.pdf

## Schedule
- 1/23 Introduction/Overview - Welcome, Course Policies, General Overview, Levels of analysis
  - Homework 1 assigned (Due 2/6) (instructions for accessing [here](retrieving_hw.md))
- 1/30 Classification and category learning
- 2/6 Neural networks / Deep learning (part 1)
- 2/13 Neural networks / Deep learning (part 2)
  - Homework 2 assigned (Due 3/6) (instructions for accessing [here](retrieving_hw.md))
- 2/20 Neural networks / Deep learning (part 3)
- 2/27 Reinforcement learning and decision making (part 1)
- 3/6 Reinforcement learning and decision making (part 2)
- 3/13 NO CLASS. Spring Recess
- 3/20 Reinforcement learning and decision making (part 3)
  - Homework 3 assigned (Due 4/6) (instructions for accessing [here](retrieving_hw.md))
- 3/27 Bayesian modeling (part 1) 
- 4/3 Bayesian modeling (part 2) 
  - Homework 4 assigned on 4/6 (Due 4/20) (instructions for accessing [here](retrieving_hw.md))
- 4/10 Rational versus mechanistic modeling approaches
- 4/17 Model comparison and fitting, tricks of trade
- 4/24 Probabilistic graphical models
- 5/1 Program induction and language of thought models
- Final project due (Tuesday 5/15)

## Detailed schedule and readings
Please see below for the assigned readings for each class. We strongly suggest reading the papers before the assigned class. Papers are available for download on NYU Classes in the "Resources" folder.

**1/23 Introduction/Overview - Welcome, Course Policies, General Overview, Levels of analysis** ([slides](slides/1-23-CCM-slides.pdf))
- No assigned readings

**1/30 Classification and category learning** ([slides](slides/1-30-categorization.pdf))
- Marr, D. (1982) “Vision” (Chapter 1)
- Love, B.C., Medin, D.L, & Gureckis, T.M (2004). SUSTAIN: A Network Model of Category Learning. Psychological Review, 111, 309-332.
- Sanborn, A. N., Griffiths, T. L., & Navarro, D. J. (2010). Rational approximations to rational models: Alternative algorithms for category learning. Psychological Review, 117 (4), 1144-1167.

**2/6 Neural networks / Deep learning (part 1)** ([slides](slides/2-6-neural-networks-1.pdf))
- McClelland, J. L., Rumelhart, D. E., & Hinton, G. E. The Appeal of Parallel Distributed Processing. Vol I, Ch 1.
- McClelland, J. L., & Rogers, T. T. (2003). The parallel distributed processing approach to semantic cognition. Nature Reviews Neuroscience, 4(4), 310-322.
- \[optional\] LeCun, Y., Bengio, Y. & Hinton, G. (2015). Deep learning. Nature 521:436–44.

**2/13 Neural networks / Deep learning (part 2)** ([slides](slides/2-6-neural-networks-1.pdf))

**2/20 Neural networks / Deep learning (part 3)** ([slides](slides/2-20-neural-networks-2.pdf))
- Elman, J. L. (1990). Finding structure in time. Cognitive Science, 14(2), 179-211.
- Peterson, J., Abbott, J., & Griffiths, T. (2016). Adapting Deep Network Features to Capture Psychological Representations. Presented at the 38th Annual Conference of the Cognitive Science Society.
- \[optional\] Krizhevsky, A., Sutskever, I., & Hinton, G. E. (2012). Imagenet classification with deep convolutional neural networks. In Advances in Neural Information Processing Systems (pp. 1097-1105).

**2/27 Reinforcement learning and decision making (part 1)** ([slides](slides/lecture5-reinforcementlearning1.pdf))
- Gureckis, T.M. and Love, B.C. (2015) Reinforcement learning: A computational perspective. Oxford Handbook of Computational and Mathematical Psychology, Edited by Busemeyer, J.R., Townsend, J., Zheng, W., and Eidels, A., Oxford University Press, New York, NY.	
- Daw, N.S. (2013) "Advanced Reinforcement Learning" Chapter in Neuroeconomics: Decision making and the brain, 2nd edition

**3/6 Reinforcement learning and decision making (part 2)** ([slides](slides/lecture6-reinforcementlearning2.pdf))
- Niv, Y. and Schoenbaum, G. (2008) “Dialogues on prediction errors” Trends in Cognitive Science, 12(7), 265-72.
- Nathaniel D. Daw, John P. O'Doherty, Peter Dayan, Ben Seymour & Raymond J. Dolan (2006). Cortical substrates for exploratory decisions in humans. Nature, 441, 876-879.

**3/20 Reinforcement learning and decision making (part 3)** ([slides](slides/lecture7-reinforcementlearning3.pdf))

**3/27 Bayesian modeling (part 1)** ([slides](slides/lecture_bayes.pdf))
- Russel, S. J., and Norvig, P. Artificial Intelligence: A Modern Approach. Chapter 13, Uncertainty.
- Tenenbaum, J. B., and Griffiths, T. L. (2001). Generalization, similarity, and Bayesian inference. Behavioral and Brain Sciences, 24(4), 629-640.

**4/3 Bayesian modeling (part 2)** (see link above)
- Tenenbaum, J. B., Kemp, C., Griffiths, T. L., & Goodman, N. D. (2011). How to grow a mind: Statistics, structure, and abstraction. Science, 331(6022), 1279-1285.
- Ghahramani, Z. (2015). Probabilistic machine learning and artificial intelligence. Nature, 521(7553), 452.
- MacKay, D. (2003). Chapter 29: Monte Carlo Methods. In Information Theory, Inference, and Learning Algorithms.

**4/10 Rational versus mechanistic modeling approaches** ([slides](slides/lecture10-bounded-rationality.pdf))
- Jones, M. & Love, B.C. (2011). Bayesian Fundamentalism or Enlightenment? On the Explanatory Status and Theoretical Contributions of Bayesian Models of Cognition. Behavioral and Brain Sciences (target article).
- Griffiths, T.L., Lieder, F., & Goodman, N.D. (2015). Rational use of cognitive resources: Levels of analysis between the computational and the algorithmic. Topics in Cognitive Science, 7(2), 217-229.

**4/17 Model comparison and fitting, tricks of trade** ([slides](slides/lecture11-modelfit.pdf))
- Pitt, M.A. and Myung, J (2002) When a good fit can be bad. Trends in Cognitive Science, 6, 10, 421-425.
- Roberts, S. & Pashler, H. (2000) How persuasive is a good fit? A comment on theory testing. Psychological Review, 107, 358-367.
- \[optional\] Myung, I.J. (2003). Tutorial on maximum likelihood estimation. Journal of Mathematical Psychology, 47, 90-100.

**4/24 Probabilistic graphical models**([slides](slides/lecture_graphical_models.pdf))
- Charniak (1991). Bayesian networks without tears. AI Magazine, 50-63.
- Kemp, C., & Tenenbaum, J. B. (2008). The discovery of structural form. Proceedings of the National Academy of Sciences, 105(31), 10687-10692.
- \[optional\]  Russel, S. J., and Norvig, P. Artificial Intelligence: A Modern Approach. Chapter 14, Probabilistic reasoning systems.

**5/1 Program induction and language of thought models**([slides](slides/lecture_program_induction.pdf))
- Goodman, N. D., Tenenbaum, J. B., & Gerstenberg, T. (2014). Concepts in a probabilistic language of thought. Center for Brains, Minds and Machines (CBMM).
- Lake, B. M., Salakhutdinov, R., & Tenenbaum, J. B. (2015). Human-level concept learning through probabilistic program induction. Science, 350(6266), 1332-1338.
- \[optional\] Ghahramani, Z. (2015). Probabilistic machine learning and artificial intelligence. Nature, 521(7553), 452.

## Course policies

**Auditing**:  
Unfortunately we have no additional spots for auditors due to the large number of previous requests. If we have replied to your request, you may audit pending available seats. Priority goes to registered students and then by date of audit request.

**Collaboration**:  
We encourage you to discuss the homework assignments with your classmates. We expect you to run the simulations and complete the write-ups for the homeworks on your own. Under no circumstance should students look at eachother's write ups. 

**Late work**:  
We will take off 10% for each day a homework or final project is late.

**Extra credit**:  
In the interest of fairness no extra credit will be given.

## Preconfigured cloud environment

Students registered for the course have the option of completing homework assignments on their personal computers, or in a cloud Jupyter environment with all required packages pre-installed. Students can log onto the environment using their github login information [here](http://130.211.189.118/).
