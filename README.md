# Monte-Carlo-Simulation
The research paper explores the application of Monte Carlo simulation, a computational method employed for the evaluation or approximation of definite integrals that challenge direct integration. It entails the generation of random points within the interval bounds, applying the function *f*, and computing the area of the integral as *f*(*x*) × (*b* − *a*). Subsequently, the average of these computed areas is calculated to yield an approximation of the integral value. The research’s theoretical foundation is based on an examination of Chapter 24.2 in Larry Wasserman's ``All of Statistics". Practical implementation is demonstrated using Python supplemented with NumPy to illustrate examples drawn from the textbook. Furthermore, the simulation is applied to estimate the value of π by evaluating the integral of the function $`\sqrt{x^2-1}`$ over the interval 0 to 1, representing the area of a semicircle with a 1-unit radius, and subsequently multiplying this computed area by 4.

