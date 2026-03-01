---
title: "Post: Integral Calculus"
date: 2026-02-22
---

Curves have been a mystery for mathematicians for about 2,000 years - especially areas of curves. Integration changed our world and helps us to solve difficult problems in physics, engineering, and medical science. Most of the things in our universe have a curvy problem which is difficult to solve with just algebra and geometry. This is how we send rockets to space, invent medicine to cure diseases, and make electronic gaming-systems.

## Integrating Equations
According to the fundamental theorem of calculus, differentiation and integration are inverse operations, which means that if you know how to differentiate, you can reverse it to integrate. Just like derivatives, integration has a power rule. To integrate an equation using the power rule, you add one to the exponent and divide by the new exponent. It is also written as $\int x^n dx = \frac{x^{n+1}}{n+1} + C$. If we find the derivative of $x^4$, we get $4x^3$. If we integrate that, we come back to $x^4$. If you try it with any power function, you will see that integration reverses differentiation.

## Area Under the Curve
The main part of integral calculus is finding the area under a curve. This problem stuck as a mystery for about two millenia. Without integral calculus, you can only estimate the area by filling the curved shape with rectangles. To find the area of a rectangle, you multiply the width and the height together. You can add the areas of rectangles to find the estimated area. The more rectangles you make and the smaller you make them, the better the approximation becomes.

To find the *exact* area, we would have to make infinite rectangles - each infinitesimally small, and add them together. To do that, you would integrate the function. If we are trying to find the area from point a to point b, you would replace the $x$ variable by b. Then, you would do the same thing with a, and subtract them. This is written by the equation

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; $A(x) = \int_{a}^{b} f(x) dx = F(a) - F(b)$

where $F(x)$ is the integration of $f(x)$. The integration symbol is a stretched-out S to denote that it's summing up the areas of infinite rectangles. $f(x)$ is the height of each rectangle, while $dx$ is the width of each rectangle. The term $dx$ is known as a **differential**. It represents the infinitesimal change in $x$. We use $\frac{dy}{dx}$ to find the instantaneous rate of change instead of $\frac{\Delta y}{\Delta x}$.

## Integration in Races
Integration can also be used in modern physics. Let's say I'm running at a speed, for example, 10 mph for half an hour. If distance equals rate times time, I ran 5 miles in that half hour. If we put this on a graph, it will show a straight line at $y=10$. We are basically finding the area under the graph from 0 to one half. However, this formula only works for constant speeds. If the speed is $v(t) = 3t$, we would have to find the area under the graph from 0 to one half, instead of using the formula. But speeds are usually represented as curves, not straight lines.

Sarah is running in a race. Her speed is represented by the curve $y = 4\sqrt{t}$ (in meters per minute). She finishes the race in five minutes. We are asked to find the length of the race track. What we can do is find the area from 0 to 5. That requires integration. The function can we rewritten as $4t^\frac{1}{2}$. Using the power rule and a little bit of algebra, we find that the integration of the curve is $\frac{8}{3}\sqrt{t^3}$. If we replace $t$ with 5, we get approximately 29.81 meters. Replacing $t$ with 0 results in 0, so the length of the track is about 29.81m.

## Conclusion
Now you can see that integration and differentiation are inverse operations, and they undo each other. You can also see how calculus unravels the mysteries of curves - which is what most of our world today is made of. Differentiation breaks apart the graph into infinitely many tangent lines to find rates of change, whereas integration adds up infinitely many thin rectangles to find the area under the curve. These two fundamentals of calculus are what shape the world we live in today.

*Note: When integrating a function, you must add C at the end of the answer; the derivative of any constant is zero, so differentiating the answer with any constant added will get to that same function*
