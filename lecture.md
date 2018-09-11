# Fall 2018 228A Lecture notes 

Recommended Textbook (you DO NOT need to buy them)

**[Lev]** R. J. LeVeque, Finite difference methods for ordinary and partial differential equations, steady state and time dependent problems, SIAM, 2007.

**[Ise]** A. Iserles, A first course in the numerical analysis of differential equations, Second Edition, Cambridge Univ. Press, 2009

**[Hai]** E. Hairer, S. P. Norsett and G. Wanner, Solving ordinary differential equations, Second Edition (2 vols.), Springer, 2008.

**[Saa]** Y. Saad, Iterative methods for sparse linear systems, SIAM, 2003

 Related materials

**[Gu]** M. Gu, Lecture notes Math 228A Fall 2014 [(web)](http://math.berkeley.edu/~mgu/MA228A)

**[Per]** P. Persson, Lecture notes Math 228A Fall 2013
[(web)](http://persson.berkeley.edu/228A)

**[Wil]** J. Wilkening, Lecture notes Math 228A Fall 2007 [(pdf)](https://math.berkeley.edu/~linlin/2015Fall_228A/wilkening_228A_notes.pdf)

## Lecture 1 (8/22)

General discussion on ordinary differential equations.

Introducing Julia. 

**Reading**: [LeV] 5.1, 5.2 [Hai] I.7,I.8

[Handout slides](https://github.com/lin-lin/2018Fall_228A/blob/master/others/228A_Note_general.pdf)


**Note**: v0.7 and v1.0 released on 8/8/2018 introduces many breaking
changes. So there is a bit learning curve if you are somewhat familiar
with previous versions of Julia before. I compiled a few things below I
noticed when migrating my old code snippets and notebooks used in the
lecture in this [pdf file](https://github.com/lin-lin/2018Fall_228A/blob/master/others/JuliaChange_v0.7.pdf).

Here is a notebook introducing some basic features of Julia.

[Notebook: Julia tutorial](http://nbviewer.jupyter.org/github/lin-lin/2018Fall_228A/blob/master/notebooks/Basics.ipynb), v0.7 compatible

Here are a few other online documents (some information may be
out-of-date).

[Learn X in Y minutes](https://learnxinyminutes.com/docs/julia/)

[The Julia Express](http://bogumilkaminski.pl/files/julia_express.pdf)

[Steven Johnson's Julia-intro](https://github.com/lin-lin/2018Fall_228A/blob/master/others/Julia-intro.pdf) 

[MATLAB–Python–Julia cheatsheet](https://cheatsheets.quantecon.org/)

[Julia manual](https://docs.julialang.org/en/stable/)


## Lecture 2 (8/24)

Lipschitz continuity; Euler's method

[Notebook: Forward Euler method](http://nbviewer.jupyter.org/github/lin-lin/2018Fall_228A/blob/master/notebooks/ForwardEuler.ipynb)

**Reading**: [Wil] pp 26-30, 41-44 


## Lecture 3 (8/27)

Convergence of Euler's method


[Lecture Note 1 (pdf)](lectures/228A_Lec1.pdf)

**Reading**: [LeV] 6.1-6.3


## Lecture 4 (8/29)

Adams-Bashforth method and Adams-Moulton method

**Reading**: [LeV] 5.3-5.6 [Ise] 1.2-1.4


## Lecture 5 (8/31)

Convergence of trapezoidal rule; Fixed point problem and fixed point iteration

**Reading**: [Ise] 2.1; [Hai] III.1

[Tobias von Petersdorff's notes on contraction mapping (with some numerics)](https://github.com/lin-lin/2018Fall_228A/blob/master/others/ContractionMapping.pdf)

## Lecture 6 (9/5)

Consistency of linear multistep method.  

[Lecture Note 2 (pdf)](lectures/228A_Lec2.pdf)

**Reading**: [Ise] 2.2; 6.1-6.2

## Lecture 7 (9/7)


[Notebook: Zero stability of LMM](http://nbviewer.jupyter.org/github/lin-lin/2018Fall_228A/blob/master/notebooks/LMM.ipynb)

Adaptive time stepping. Zero stability of LMM

**Reading**: [LeV] 6.1-6.4; [Hai] III.3-4

## Lecture 8 (9/10)

[Lecture Note 3 (pdf)](lectures/228A_Lec3.pdf)

[Details of the proof of general convergence theory of LMM (pdf)](lectures/LMMConvergence.pdf)

Zero stability of LMM; Convergence of general LMM

**Reading**: [Wil] pp 61-77


## Lecture 9 (9/12)

Runge-Kutta method. 

**Reading**: [Ise] 3.1-3.3. [Hai] II.2


## Lecture 10 (9/14)

Consistency of Runge-Kutta method. 

**Reading**: [Wil] pp 95-107
