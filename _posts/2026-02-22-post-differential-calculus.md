---
title: "Post: Differential Calculus"
date: 2026-02-22
---

Have you ever thought that the slope of a graph or equation is always a constant? Well, in this case, it isn't. Just like equations, slopes can be functions. The equation $y = 5$ is a constant. The equation $y = 2x + 1$, however, is a function while the slope is constant. This post is about finding the slope of a curved function using differentiation.

## The Concept of Limits
The limit tells you what happens when something approaches something else. The limit of a function tells you where the dependent variable ($y$) approaches as the independent variable ($x$) approaches a value. The standard form, $\lim_{x \to c} f(x) = L$, is said as "the limit as $x$ approaches $c$ of $f(x)$ is $L$". If we take the $\lim_{x \to 2} 2x + 1$, we get 5 (as $x$ approaches 2, $y$ approaches 5). However, we aren't finding the limit *at* $x=2$, we are finding the limit as $x$ *approaches* 2. That means you can't always plug $c$ into the equation.

When you use direct substitution, you might get something where the denominator is zero. That means the function isn't defined at that point. You can graph the function, and determine what the dependent variable approaches. You can also factor out the numerator and cancel out the denominator. Another way is to rationalize the function if it has roots, or if it has trigonometric functions, you can use trigonometric identities. Depending on the function, you can always use a smart trick to cancel out the denominator.

## Tangent Lines
The slope of a linear line is the change in $x$ over the change in $y$. However, curves are not straight - they're curved. On some points on the curve, the slope is steep, or negative. On some points, it's high, or large. On some points it's just zero. Differentiation finds the instantaneous slope at any given point. A tangent line is a line that touches a curve at one point. We're trying to find the slope of $x^2$. We can put tangent lines, which will find the curve at any point.

Now what we have to do is find the slope of the straight line. Let's say the change in $x$ is $h$. However, since we are finding the slope at one single point, we should write this as a limit where $h$ is approaching 0. This could be written as $\lim_{h \to 0} [((x + h)^2 - x^2)/h]$. If we plug 0 into the equation, we get 0/0, which is indeterminate. But with a little bit of algebra, we can simplify the equation to $\lim_{h \to 0} 2x + h$ which when pluging in 0 gets us $2x$.

## The Power Rule
Doing all that work just to find the slope of a curve is overwhelming. In the mid 1600s, Newton discovered something for differentiating power functions known as the power rule. He discovered a law that the derivative of any power function is the power multiplied by the coefficient, raised to the power minus one, or $\frac{d}{dx} x^n = nx^{n-1}$.

&nbsp;&nbsp;&nbsp;<ins>Function</ins>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<ins>Differentiation</ins>\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; $x^2$ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; $2x^1$\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; $x^3$ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; $3x^2$\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; $x^4$ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; $4x^3$\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; $x^5$ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; $5x^4$

If we use it to find the derivative of $x^2$, we get $2x$. Differentiating $x^3$ gives us $3x$. And differentiating $x^4$ is $4x$. This rule works for other power functions as well as this one. There is also a similar rule for integration, but that shall be discussed in the next post.

## Rates in Speeds
Derivatives are used to find the rate of change. In physics, the rate of change, or derivative, of velocity is acceleration. Let's say I am running in a race, with a speed of 2 mph when the race starts. Then, I speed up 3 mph every second. My velocity is then represented as $v(t) = 3t + 2$. To find my acceleration, you would differentiate the equation. According to the power rule, the derivative of $3t$ is 3. The derivative of a constant is always 0, so the derivative of the equation is 3. Therefore, my accerleration was 3mph/s.

## Conclusion
As you can see, if you calculate the slope of a linear equation at *any* two points, you get the same rate of change. That is what makes a linear function unique. However, on a curved line, calculating the slope at two different points could give you different slopes. The slope at one point might be steeper (or larger) than the slope at another point. This is what makes differential calculus fascinating.

*Note: The derivative of a constant is always 0 because it is a straight line, which has a slope of zero*
