Here is the combined Markdown file for all the documents you provided:

```markdown
# Core Concepts in Agricultural and Applied Economics (ECON4002)

---

## Week 1: Introduction to Unit & Review of Economic Concepts

### Introduction

- **Purpose of Unit**: Focus on formal economic analysis of consumer and producer behavior, markets, and policy effects.
- **Formal Economic Analysis**: Uses mathematics for precision, explicit assumptions, and ease of generalization.
- **Economic Model**: Simplified analytical framework representing economic reality.

### Topics Covered

- **Consumer/Demand**: Consumer behavior, utility maximization, cost/expenditure, indirect utility functions, demand (Hicksian and Marshallian), consumer welfare.
- **Producer/Supply**: Producer behavior, production functions, economies of scale, cost, profit, revenue functions, input demand, supply, and producer welfare.
- **Market Analysis**: Market equilibrium, competition, market power, economic efficiency, Pareto optimality, policy intervention, and welfare loss.
- **Trade**: Theory of comparative advantage, benefits of free trade, trade restraints, and welfare impacts.
- **Uncertainty**: Risk and uncertainty, expected utility theory, measures of risk aversion, risk premium, and insurance.
- **Game Theory**: Behavior of agents considering actions of other agents, strategizing.

### Methods

- Linear algebra and matrices
- Calculus and optimization (constrained and unconstrained)
- Mathematical programming (LP)
- Expected utility maximization

### Assessment

- Ongoing assessments: 65%
  - 3 assignments (written): 55%
  - Participation (including homework and quizzes): 10%
- Final test (written): 35%

### Textbooks

- Various microeconomics and mathematical economics textbooks are available.
- No single text covers all topics, but some come close.
- Use electronically available texts when possible.

### Homework and Other Activities

- Homework will be issued to encourage reading and participation.
- Prior preparation (reading, listening to lectures) is essential.

---

## Week 2 & 3: Review of Mathematical Concepts

### Outline

- Basic Maths: Logarithms, logs, and growth rates
- Linear Equation Systems and Matrices: Relevance in economics, demand and supply example, matrix operations, determinants, singularity, inversion, and solutions
- Functions: Function types, example notation, Cobb-Douglas
- Functions in Economics: Marginal functions
- Sets and Optimization

### Basic Maths

- **Logarithms**: Useful for percentage growth rates and elasticity calculations.
- **Logs and Growth Rates**: Convenient for calculating growth rates when changes are small.

### Linear Equation Systems and Matrices

- **Relevance in Economics**: Linear equations represent simple relationships or approximations.
- **Demand and Supply Example**: Solve linear equation systems graphically or algebraically.
- **Matrix Operations**: Addition, subtraction, scalar multiplication, matrix multiplication, inverse, and determinants.

### Functions

- **Function Types**: Algebraic and transcendental functions.
- **Cobb-Douglas Function**: Commonly used in production, cost, or profit analysis.
- **Translog Function**: Quadratic in logs, used for production, cost, or profit analysis.

### Functions in Economics

- **Marginal Functions**: Useful for optimization, setting marginal values to zero or some constant.

### Sets and Optimization

- **Sets**: Domains of functions, set operations, convex sets, and compact sets.
- **Optimization**: Uses marginal values, derivatives, and second-order conditions.

### Practice Questions

- Simplify expressions, factorize, solve quadratic equations, and calculate growth rates.
- Use logarithms to calculate growth rates and interest rates.

### Sources/Readings

- Melkumian (2011): Math basics, sets, functions, power, exponents, sequences/series, logarithmic and exponential functions, matrices.
- Chiang (1984): Chapters 1 to 5.
- Jacques (2015): Linear and nonlinear functions, matrices.

---

## Homework 2 (Answer Key)

### Instructions

Do the following exercises and provide clear and well-explained answers.

### Questions

1. **From Melkumian (2011)**

   a) Section 2.2, Question 2 (parts (a) and (c))

   - (a) $(3x^{2}y^{\frac{1}{4}}z^{5})^{8} = 3^{8}x^{16}y^{2}z^{40}$ (or $6561x^{16}y^{2}z^{40}$)
   - (c) $\frac{(x + w + e + r)^{\frac{17}{2}}}{(x + w + e + r)^{\frac{15}{2}}} = x + w + e + r$

   b) Section 2.4, Question 4 (part (b))

   - $\sum_{i=1}^{3}\sum_{j=-1}^{2}(i^{2}+j^{2})^{i+j} = 386495$

   c) Section 3.3, Question 4

   - With annual compounding:
     - Triple in about 16 years ($log(3)/log(1.07)=16.24$)
     - Quadruple in about 20 years ($log(4)/log(1.07)=20.49$)
   - With continuous compounding:
     - Triple in about 16 years ($log(3)/0.07=15.69$)
     - Quadruple in about 20 years ($log(4)/0.07=19.80$)

   d) Find the symmetric matrix associated with the quadratic form in Example 7.2 (Section 7.2).

   - $Q = \begin{bmatrix} q_{11} & q_{12} \\ q_{12} & q_{22} \end{bmatrix}$ such that $q_{11} = 2a_{11}$, $q_{22} = 2a_{22}$, $q_{12} = (a_{12} + a_{21})$

2. **Matrix Operations**

   a) Determine the product of the following two matrices:

   - $A = \begin{bmatrix} 2 & 1 \\ 3 & 5 \end{bmatrix}$, $B = \begin{bmatrix} 4 & 0 \\ 1 & 2 \end{bmatrix}$

   - Answer: $\begin{bmatrix} 9 & 2 \\ 17 & 10 \end{bmatrix}$

   b) Find the inverse of matrix $A$ above.

   - Answer: $\frac{1}{7} \begin{bmatrix} 5 & -1 \\ -3 & 2 \end{bmatrix}$

   c) Calculate the determinant of the matrix below:

   - $D = \begin{bmatrix} 1 & 2 & 3 \\ 7 & 0 & 8 \\ 4 & 5 & 6 \end{bmatrix}$

   - Answer: 45

3. **Linear Equation Systems**

   a) $5x + 3y = 11$, $4x + y = 6$

   - Answer: Unique solution ($x = 1, y = 2$)

   b) $2x + y = 4$, $x + 0.5y = 2$

   - Answer: Infinite solutions (equations are dependent)

   c) $2x + y = 6$, $x + 0.5y = 2$

   - Answer: No solution (inconsistent system)

4. **Cramer's Rule**

   - $2x - 4y + 6z = 3$, $-x + 3y + 2z = 2$, $6x - 7y - 2z = 4$

   - Answer: $x=2, y=1, z=0.5$

5. **Functions**

   a) When do we say a function $f(x)$ is continuous at $x=c$?

   - Answer: Left to student.

   b) Which of the following functions is (are) continuous over the domain $x \in [0,3]$?

   - $(1) f(x) = x^{2}+1$
   - $(2) f(x) = \frac{x^{2}-4}{(x^{2}+2)}$
   - $(3) f(x) = |x|$
   - $(4) f(x) = \frac{x^{2}-x+1}{(x^{2}-1)(x^{2}+2)}$

   - Answer: All except the last one.

   c) When do we say a function $f(x)$ is differentiable (has a slope) at $x=c$?

   - Answer: Left to student.

   d) Which of the functions in (b) above are everywhere differentiable?

   - Answer: First two.

6. **Parabola**

   - $y = ax^{2} + bx + c$
   - Observations: When input is 40, output is 4560; when input is 80, output is 7440; when input is 120, output is 9040.

   a) Determine the values of the equation parameters $a, b$ and $c$.

   - Answer: $a = -0.4, b = 120, c = 400$

   b) How does the responsiveness of output vary as input increases from 40 to 80 to 120?

   - Answer: Elasticity of output with respect to input declines from 0.77 to 0.60 to 0.32.

   c) Determine the maximum achievable output for this production relationship.

   - Answer: $x = 150$ and maximum output is $y = 9400$.
```

You can copy and paste this Markdown content into a `.md` file and save it for future reference.