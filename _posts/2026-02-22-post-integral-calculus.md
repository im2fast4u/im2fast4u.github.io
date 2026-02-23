---
title: "Post: Integral Calculus"
date: 2026-02-22
---

Curves have been a mystery for mathematicians for 2,000 years - especially areas of curves. Integration changed our world and helps us solve difficult problems in physics, engineering, and medical science. Most of the things in our universe have a curvy problem which is difficult to solve with just algebra and geometry. This is how we send rockets to space, create medicine to sicknesses, and make electronic gaming-systems.

## Integrating Equations
According to the fundamental theorem of calculus, differentiation and integration are inverse operations, which means that if you know how to differentiate, you can reverse it to integrate. Just like derivatives, integration has a power rule. To integrate an equation using the power rule, you add one to the exponent and divide by the new exponent. It is also written as $\int x^n dx = \frac{x^{n+1}}{n+1} + C$. If we find the derivative of $x^4$, we get $4x^3$. If we integrate that, we come back to $x^4$. If you try it with any power function, you will see that integration reverses differentiation.

## Area Under the Curve
The main part of integral calculus is finding the area under a curve. This area problem stuck as a mystery for two millenia. Let's first look at *how* to solve it. When it came to the area of a curvy shape, people estimated the area by making rectangles and filling the shape with them. We know how to find the area of rectangles: width times height. For example, if we were asked to find the area under the curve $2x^2 - 4$ from $x=3$ to $x=4$, we could make two rectangles and find the area of each one. Then, we could add them together.

However, that is only an approximation. To find the *exact* area, we would have to make infinite rectangles - each infinitesimally small, and add them together. To do that, you would integrate the function. If we are trying to find the area from point a to point b, you would replace the $x$ variable by b. Then, you would do the same thing with a, and subtract them. For example, if we want to find the area below the curve $x^2$ from 0 to 3, we would first integrate the function. That would get us $x^3/3$. Then we would solve $3^3/3 - 0^3/3$ which gives us 9 square units.

## Integration in Races
Integration can also be used in modern physics. Let's say I'm running at a speed, for example, 10 mph for half an hour. If distance equals rate times time, I ran 5 miles in that half hour. If we put this on a graph, it will show a straight line at $y=10$. We are basically finding the area under the graph from 0 to one half. However, this formula only works for constant speeds. If the speed is $v(t) = 3t$, we would have to find the area under the graph from 0 to one half, instead of the formula. But speeds are usually represented as curves, not straight lines.

Sarah is running in a race. Her speed is represented by the curve $y = 4\sqrt{t}$ (in meters per minute). She finishes the race in five minutes. We are asked to find the length of the race track. What we can do is find the area from 0 to 5. That requires integration. The function can we rewritten as $4t^\frac{1}{2}$. Using the power rule and a little bit of algebra, we find that the integration of the curve is $\frac{8}{3}\sqrt{t^3}$. If we replace $t$ with 5, we get approximately 29.81 meters. Replacing $t$ with 0 results in 0, so the length of the track is about 29.81m.

## Conclusion
Now you can see that integration and differentiation are inverse operations, and they undo each other. You can also see how calculus unravels the mysteries of curves - which is what most of our world today is made of. Differentiation breaks apart the graph into infinitely many tangent lines to find rates of change, whereas integration adds up infinitely many thin rectangles to find the area under the curve. These two fundamentals of calculus are what shape the world we live in today.

*Note: When integrating a function, you must add C at the end of the answer; the derivative of any constant is zero, so differentiating the answer with any constant added will get to that same function*
