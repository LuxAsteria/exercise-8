# exercise-8
***
###Abstract

In former exercise, I'v actualized visualizing python program, in this assignment, based on the former exercise, I obtained the success of visualizing the movement of double pendulum, what’s more, I also found another way—pygame, to make things visible. Beside this, I'v finished problem *3.20* and *3.21*.
***
###Background

*problem 3.20*
>Calculate the bifurcation diagram for the pendulum in the vicinity of F<sub>D</sub>=1.35 to 1.5.Make a magnified plot of the diagram and obtain an estimate of the Feigenbaum <img src="http://latex.codecogs.com/gif.latex?\delta" alt="" title="" /> parameter.

*problem 3.21*
>Investigate the bifurcation diagrams found for the pendulum with other values of the drive frequency and damping parameter. 
***
###Exercise

####level 1: Visualization

##First, the movement of double pendulum


![doublependulum](https://github.com/LuxAsteria/test3/blob/master/doublep.gif)



####level 2: Poincaré section:

![img poin](https://github.com/LuxAsteria/test3/blob/master/pongalai.png)


####level 3: bifurcation picture and estimation of <img src="http://latex.codecogs.com/gif.latex?\delta_{n}" alt="" title="" />
First are the bifurcations with different parameter.(The original one is with the same parameters in textbook<sup>1</sup>)

![img](https://github.com/LuxAsteria/test3/blob/master/origin.png)
![img](https://github.com/LuxAsteria/test3/blob/master/屏幕快照%202016-11-11%20下午4.46.28.png)
![img](https://github.com/LuxAsteria/test3/blob/master/屏幕快照%202016-11-11%20下午5.24.24.png)
![img](https://github.com/LuxAsteria/test3/blob/master/屏幕快照%202016-11-11%20下午5.31.41.png)
![img](https://github.com/LuxAsteria/test3/blob/master/屏幕快照%202016-11-11%20下午5.35.47.png)

According to the picture, it’s easy to find the points where the division happens. Thus, us  the fuction:

<img src="http://latex.codecogs.com/gif.latex?\delta_{n}=\frac{F_{n+1}-F_{n}}{F_{n}-F_{n-1}}" alt="" title="" />

The result is 4.32, and when it approaches to infinite, it will be 4.66——— 
Which is the Feigenbaum constant.
***
###Conclusion

In this assignment, I complete the task of visualization, and progress several steps, in other words, calculate the movement of double pendulum and make them visible, as well as finding another method to actualize 3d animation.
I also drew the bifurcation pictures as is required in the questions. The only problem I met is how do precisely define the bifurcation point, which still needs to be improved.
***
###Acknowledge

[1]Nicolas J. Giordano,Hisao Nkanishi,Computational Physics, second edition.
[2]Harrison Kinsley,Python tutorial
***

##Ps:Any form of *plagiarism* is unwelcomed. All Rights are Reserved.
