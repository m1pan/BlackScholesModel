# BlackScholesModel
Black-Scholes-Merton model for options pricing.
$$ \frac{\partial V}{\partial t} + \frac{1}{2}\sigma^2S^2\frac{\partial^2 V}{\partial S^2} + rS\frac{\partial V}{\partial S} - rV = 0 $$
Black-Scholes equation was first transformed into the form of the heat equation, then solved implicitly using the Crank-Nicolson method. Central difference approximation in stock price and forward difference approximation in time were also used to solve the equation explicitly as a comparison to the implicit method. 
