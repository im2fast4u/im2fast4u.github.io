---
title: "Post: Differential Calculus"
date: 2026-02-22
---

Have you ever thought that the slope of a graph or equation is always a constant? Well, in this case, it isn't. Just like equations, slopes can be functions. The equation $y = 5$ is a constant. The equation $y = 2x + 1$, however, is a function while the slope is constant. In this post you will also encounter limits and how to find the slope of a curve.

## The Concept of Limits
The limit tells you what happens when something approaches something else. The limit of a function tells you where the dependent variable ($y$) approaches as the independent variable ($x$) approaches a value. The standard form, $\lim_{x \to c} f(x) = L$, is said as "the limit as $x$ approaches $c$ of $f(x)$ is $L$". If we take the $\lim_{x \to 2} 2x + 1$, we get 5 (as $x$ approaches 2, $y$ approaches 5). However, we aren't finding the limit *at* $x=2$, we are finding the limit as $x$ *approaches* 2. That way, you can't always plug $c$ into the equation.

## Tangent Lines
Now, we will get into finding the slope of curves. Let's take the curve $x^2$. If we want to find the slope, we will have to zoom in until the curve is straight. The more we zoom in, the straighter the curve gets, and the smaller the length of the line gets. As you can see, we are creating infinitely many infinitely small straight lines. To find the slope of a straight line, you simply take the change in the the dependent variable and divide it by the change in the independent variable.

We could write this as a limit. Let's say distance between the two points is $h$. As we zoom in, the length of the line approaches 0. The equation would be the limit as $h$ approaches zero of the change in $y$ over the change in $x$, or $\lim_{h \to 0} [((x + h)^2 - x^2)/h]$. If we plug 0 into the equation, we get 0/0, which is indeterminate. But with a little bit of algebra, we can simplify the equation to $\lim_{h \to 0} 2x + h$ which gives us $2x$ when we plug in 0.

## The Power Rule
Instead of doing all that work, what if I tell you there's a simpler way. The power rule of differentiation is a quicker way to do that mess. To find the derivative of a function, you multiply the coefficient by the exponent, and then subtract one from the exponent. It is written as $\frac{d}{dx} x^n = nx^{n-1}$. If we use it to find the derivative of $x^2$, we get $2x$. This rule works for other power functions as well as this one. There is also a similar rule for integration, but that shall be discussed in the next post.

## Rates in Speeds
Derivatives are used to find the rate of change. In physics, the rate of change, or derivative, of velocity (a fancy term for speed) is acceleration. I am running in a race, with a speed of 2 mph when the race starts. Then, I speed up 3 mph every second. My velocity is then represented as $v(t) = 3t + 2$. To find my acceleration, you would differentiate the equation. According to the power rule, the derivative of $3t$ is 3. The derivative of a constant is always 0, so the derivative of the equation is 3. Therefore, my accerleration was 3mph/s.

## Conclusion
As you can see, the slope of a line can be a function just like an equation. The rate of change of $x^3$ is $3x^2$ whereas the rate of change of $x^4$ is $4x^3$. Differentiation breaks apart a graph into infinitely many infinitely small tangent lines (a line that touches a curve at one point), whereas integration adds up the area of infinitely thin rectangles together as you will see in the next post.

*Note: The derivative of a constant is always 0 because it is a straight line, which has a slope of zero*
