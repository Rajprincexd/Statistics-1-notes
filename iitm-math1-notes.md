# Mathematics 1 - Complete Study Notes for IIT Madras BS Degree Qualifier

**Duration: 4 Weeks | Target: Anyone with zero math background | Goal: Master qualifier concepts**

---

## Table of Contents

1. [Week 1: Numbers, Sets, and Functions](#week-1)
2. [Week 2: Coordinate Geometry and Linear Systems](#week-2) 
3. [Week 3: Quadratic Functions](#week-3)
4. [Week 4: Polynomials and Advanced Topics](#week-4)
5. [Practice Questions and PYQs](#practice-questions)
6. [Quick Revision Guide](#quick-revision)

---

## Week 1: Numbers, Sets, and Functions

### 1.1 Numbers and Types of Numbers

**What are Numbers?**
Numbers are symbols used to represent quantities. Think of them as different types of objects in mathematics.

#### Types of Numbers (From Simple to Complex)

**1. Natural Numbers (N)**
- Definition: Counting numbers starting from 1
- Set: N = {1, 2, 3, 4, 5, ...}
- Example: If you count apples: 1 apple, 2 apples, 3 apples...

**2. Whole Numbers (W)**  
- Definition: Natural numbers + zero
- Set: W = {0, 1, 2, 3, 4, 5, ...}
- Example: Number of books you have (can be 0)

**3. Integers (Z)**
- Definition: Whole numbers + negative numbers  
- Set: Z = {..., -3, -2, -1, 0, 1, 2, 3, ...}
- Example: Temperature (can be -5°C or +25°C)

**4. Rational Numbers (Q)**
- Definition: Numbers that can be written as p/q where p, q are integers and q ≠ 0
- Examples: 1/2, 3/4, -2/5, 7 (can be written as 7/1)
- Decimal form: Either terminating (0.5) or repeating (0.333...)

**5. Irrational Numbers**
- Definition: Numbers that CANNOT be written as p/q
- Examples: √2, π, e
- Decimal form: Non-terminating, non-repeating

**6. Real Numbers (R)**
- Definition: All rational + irrational numbers
- Basically all numbers on the number line

**7. Complex Numbers (C)**
- Definition: Numbers of the form a + bi where i = √(-1)
- Examples: 3 + 4i, 2 - 5i

**Practice Example:**
Classify these numbers: 5, -3, 1/2, √3, 0, π

**Solution:**
- 5: Natural, Whole, Integer, Rational, Real
- -3: Integer, Rational, Real  
- 1/2: Rational, Real
- √3: Irrational, Real
- 0: Whole, Integer, Rational, Real
- π: Irrational, Real

### 1.2 Sets and Venn Diagrams

**What is a Set?**
A collection of distinct objects. Think of it as a box containing items.

#### Set Notation
- **Roster Form**: A = {1, 2, 3, 4}
- **Set Builder Form**: A = {x | x is a natural number ≤ 4}

#### Types of Sets
1. **Empty Set (∅)**: No elements. Example: Set of married bachelors
2. **Finite Set**: Limited elements. Example: {1, 2, 3}  
3. **Infinite Set**: Unlimited elements. Example: Natural numbers
4. **Universal Set (U)**: Contains all elements under consideration

#### Set Operations

**1. Union (A ∪ B)**
- Definition: All elements in A OR B (or both)
- Example: If A = {1, 2, 3} and B = {3, 4, 5}, then A ∪ B = {1, 2, 3, 4, 5}

**2. Intersection (A ∩ B)**  
- Definition: Elements common to both A AND B
- Example: A ∩ B = {3}

**3. Difference (A - B)**
- Definition: Elements in A but NOT in B
- Example: A - B = {1, 2}

**4. Complement (A')**
- Definition: Elements in universal set U but NOT in A
- If U = {1, 2, 3, 4, 5, 6} and A = {1, 2, 3}, then A' = {4, 5, 6}

#### Venn Diagrams
Visual representation of sets using circles.

**Practical Problem:**
In a class of 50 students:
- 30 like Mathematics
- 25 like Physics  
- 10 like both subjects

Find: (a) Students who like only Math (b) Students who like only Physics (c) Students who like neither

**Solution:**
- Both subjects = 10
- Only Math = 30 - 10 = 20
- Only Physics = 25 - 10 = 20  
- Neither = 50 - (20 + 10 + 20) = 0

### 1.3 Functions and Relations

**What is a Relation?**
A relation connects elements from one set to another. Like connecting students to their marks.

**What is a Function?**
A special relation where each input has exactly ONE output.

#### Function Notation
- f(x) = 2x + 1 means "function f takes input x and gives output 2x + 1"
- If x = 3, then f(3) = 2(3) + 1 = 7

#### Types of Functions

**1. Linear Function**
- Form: f(x) = mx + c
- Graph: Straight line
- Example: f(x) = 2x + 3

**2. Quadratic Function**  
- Form: f(x) = ax² + bx + c
- Graph: Parabola
- Example: f(x) = x² + 2x + 1

**3. Constant Function**
- Form: f(x) = c
- Graph: Horizontal line
- Example: f(x) = 5

#### Domain and Range
- **Domain**: All possible input values (x-values)
- **Range**: All possible output values (y-values)

**Example:**
For f(x) = √x
- Domain: x ≥ 0 (can't take square root of negative numbers)
- Range: y ≥ 0 (square root is always non-negative)

---

## Week 2: Coordinate Geometry and Linear Systems

### 2.1 Coordinate System Basics

**The Coordinate Plane**
Two perpendicular lines (axes) that intersect at origin (0,0).
- **x-axis**: Horizontal line
- **y-axis**: Vertical line  
- **Point**: (x, y) where x is horizontal position, y is vertical position

#### Quadrants
1. **Quadrant I**: x > 0, y > 0 (both positive)
2. **Quadrant II**: x < 0, y > 0  
3. **Quadrant III**: x < 0, y < 0 (both negative)
4. **Quadrant IV**: x > 0, y < 0

### 2.2 Distance and Midpoint

**Distance Formula**
Distance between points (x₁, y₁) and (x₂, y₂):
d = √[(x₂ - x₁)² + (y₂ - y₁)²]

**Example:** Find distance between (1, 2) and (4, 6)
d = √[(4-1)² + (6-2)²] = √[9 + 16] = √25 = 5

**Midpoint Formula**
Midpoint of line segment joining (x₁, y₁) and (x₂, y₂):
M = ((x₁ + x₂)/2, (y₁ + y₂)/2)

**Example:** Midpoint of (1, 2) and (4, 6)
M = ((1+4)/2, (2+6)/2) = (2.5, 4)

### 2.3 Straight Lines

#### Slope of a Line
**Definition:** Measure of steepness
**Formula:** m = (y₂ - y₁)/(x₂ - x₁)

**Types of Slopes:**
- **Positive slope**: Line rises from left to right
- **Negative slope**: Line falls from left to right  
- **Zero slope**: Horizontal line
- **Undefined slope**: Vertical line

#### Equation of a Line

**1. Slope-Intercept Form**
y = mx + c
- m = slope
- c = y-intercept (where line crosses y-axis)

**2. Point-Slope Form**  
y - y₁ = m(x - x₁)
Use when you know slope and one point

**3. Two-Point Form**
(y - y₁)/(y₂ - y₁) = (x - x₁)/(x₂ - x₁)
Use when you know two points

**Example Problem:**
Find equation of line passing through (1, 3) and (4, 9).

**Solution:**
Step 1: Find slope
m = (9-3)/(4-1) = 6/3 = 2

Step 2: Use point-slope form
y - 3 = 2(x - 1)
y - 3 = 2x - 2  
y = 2x + 1

#### Parallel and Perpendicular Lines
- **Parallel lines**: Same slope
- **Perpendicular lines**: Product of slopes = -1

If line 1 has slope m₁ and line 2 has slope m₂:
- Parallel: m₁ = m₂  
- Perpendicular: m₁ × m₂ = -1

### 2.4 Linear Equations and Inequalities

#### Solving Linear Equations
**Standard Form:** ax + b = 0

**Steps:**
1. Collect like terms
2. Isolate the variable
3. Check your answer

**Example:** Solve 3x + 7 = 22
3x = 22 - 7
3x = 15  
x = 5

**Check:** 3(5) + 7 = 15 + 7 = 22 ✓

#### System of Linear Equations
Two or more equations with same variables.

**Example:**
2x + y = 7  ... (1)
x - y = 2   ... (2)

**Solution by Elimination:**
Add equations (1) + (2):
3x = 9
x = 3

Substitute in equation (2):
3 - y = 2
y = 1

**Answer:** x = 3, y = 1

#### Linear Inequalities
Similar to equations but with ≤, ≥, <, > instead of =

**Example:** Solve 2x + 3 > 7
2x > 7 - 3
2x > 4
x > 2

**Solution:** All numbers greater than 2

---

## Week 3: Quadratic Functions

### 3.1 Introduction to Quadratic Functions

**Definition:** A function of the form f(x) = ax² + bx + c where a ≠ 0

**Why is a ≠ 0?**
If a = 0, we get f(x) = bx + c, which is linear, not quadratic.

#### Standard Form vs Vertex Form

**Standard Form:** f(x) = ax² + bx + c
- a, b, c are constants
- c is the y-intercept

**Vertex Form:** f(x) = a(x - h)² + k  
- (h, k) is the vertex of parabola
- h is axis of symmetry

### 3.2 Graphing Parabolas

**Shape of Graph:**
- If a > 0: Parabola opens upward (∪ shape)
- If a < 0: Parabola opens downward (∩ shape)

#### Key Features of Parabola

**1. Vertex**
The highest or lowest point.
- For f(x) = ax² + bx + c: Vertex x-coordinate = -b/(2a)
- Substitute to find y-coordinate

**2. Axis of Symmetry**
Vertical line passing through vertex: x = -b/(2a)

**3. y-intercept**
Where parabola crosses y-axis: (0, c)

**4. x-intercepts (Roots)**
Where parabola crosses x-axis. Found by solving ax² + bx + c = 0

**Example:** Analyze f(x) = x² - 4x + 3

**Solution:**
- a = 1 > 0, so parabola opens upward
- Vertex: x = -(-4)/(2×1) = 2
  f(2) = 4 - 8 + 3 = -1
  Vertex: (2, -1)
- y-intercept: f(0) = 3, so (0, 3)  
- x-intercepts: x² - 4x + 3 = 0
  (x - 1)(x - 3) = 0
  x = 1 or x = 3
  Points: (1, 0) and (3, 0)

### 3.3 Solving Quadratic Equations

#### Method 1: Factoring
**When to use:** When equation factors easily

**Steps:**
1. Write in standard form: ax² + bx + c = 0
2. Factor the expression  
3. Set each factor equal to zero
4. Solve for x

**Example:** x² - 5x + 6 = 0
Factor: (x - 2)(x - 3) = 0
Solutions: x = 2 or x = 3

#### Method 2: Quadratic Formula
**When to use:** Always works!

**Formula:** x = [-b ± √(b² - 4ac)] / (2a)

**Discriminant (Δ):** b² - 4ac
- If Δ > 0: Two real roots
- If Δ = 0: One real root (repeated)  
- If Δ < 0: No real roots (complex roots)

**Example:** 2x² + 3x - 2 = 0
Here a = 2, b = 3, c = -2

Δ = 3² - 4(2)(-2) = 9 + 16 = 25

x = [-3 ± √25] / (2×2) = [-3 ± 5] / 4

x = (-3 + 5)/4 = 1/2 or x = (-3 - 5)/4 = -2

#### Method 3: Completing the Square
**When to use:** To convert to vertex form

**Steps:**
1. Move constant to right side
2. Complete the square on left side
3. Factor perfect square trinomial
4. Solve

**Example:** x² + 6x + 5 = 0
x² + 6x = -5
x² + 6x + 9 = -5 + 9  (adding (6/2)² = 9)
(x + 3)² = 4
x + 3 = ±2
x = -3 ± 2
x = -1 or x = -5

### 3.4 Maximum and Minimum Values

#### For Parabola f(x) = ax² + bx + c:

**If a > 0:** Parabola opens upward
- Has minimum value at vertex
- Minimum value = f(-b/(2a))

**If a < 0:** Parabola opens downward  
- Has maximum value at vertex
- Maximum value = f(-b/(2a))

**Real-World Example:**
A ball is thrown upward. Its height h(t) = -16t² + 64t + 5 feet after t seconds.

Find: (a) Maximum height (b) When it reaches maximum height

**Solution:**
a = -16 < 0, so parabola opens downward (has maximum)

Maximum occurs at t = -64/(2×(-16)) = 64/32 = 2 seconds

Maximum height = h(2) = -16(4) + 64(2) + 5 = -64 + 128 + 5 = 69 feet

---

## Week 4: Polynomials and Advanced Topics

### 4.1 Introduction to Polynomials

**Definition:** An expression with variables, coefficients, and non-negative integer exponents

**General Form:** P(x) = aₙxⁿ + aₙ₋₁xⁿ⁻¹ + ... + a₁x + a₀

#### Terms and Terminology
- **Coefficient:** Number multiplying the variable (a₃ in a₃x³)
- **Degree:** Highest power of variable
- **Leading Coefficient:** Coefficient of highest degree term
- **Constant Term:** Term without variable

**Example:** P(x) = 3x⁴ - 2x² + 7x - 1
- Degree: 4
- Leading coefficient: 3
- Constant term: -1
- Number of terms: 4

#### Types of Polynomials by Degree
1. **Constant (degree 0):** P(x) = 5
2. **Linear (degree 1):** P(x) = 2x + 3  
3. **Quadratic (degree 2):** P(x) = x² - 4x + 1
4. **Cubic (degree 3):** P(x) = x³ + 2x² - x + 5
5. **Quartic (degree 4):** P(x) = x⁴ - 3x + 2

#### Types of Polynomials by Number of Terms
1. **Monomial:** One term (3x²)
2. **Binomial:** Two terms (x² + 5)  
3. **Trinomial:** Three terms (x² + 3x - 2)
4. **Polynomial:** More than three terms

### 4.2 Polynomial Operations

#### Addition and Subtraction
**Rule:** Combine like terms (same variable with same power)

**Example:**
P(x) = 2x³ + 5x² - 3x + 1
Q(x) = x³ - 2x² + 4x - 5

P(x) + Q(x) = (2x³ + x³) + (5x² - 2x²) + (-3x + 4x) + (1 - 5)
             = 3x³ + 3x² + x - 4

P(x) - Q(x) = (2x³ - x³) + (5x² + 2x²) + (-3x - 4x) + (1 + 5)  
             = x³ + 7x² - 7x + 6

#### Multiplication
**Methods:**
1. **Monomial × Polynomial:** Distribute
2. **Polynomial × Polynomial:** Use FOIL or distributive property

**Example 1:** 3x(2x² - 5x + 1)
= 3x × 2x² + 3x × (-5x) + 3x × 1
= 6x³ - 15x² + 3x

**Example 2:** (x + 2)(x² - 3x + 4)
= x(x² - 3x + 4) + 2(x² - 3x + 4)
= x³ - 3x² + 4x + 2x² - 6x + 8
= x³ - x² - 2x + 8

#### Special Products (Very Important!)

**1. Square of Binomial:**
- (a + b)² = a² + 2ab + b²
- (a - b)² = a² - 2ab + b²

**2. Difference of Squares:**
- (a + b)(a - b) = a² - b²

**3. Cube of Binomial:**
- (a + b)³ = a³ + 3a²b + 3ab² + b³
- (a - b)³ = a³ - 3a²b + 3ab² - b³

**Example Applications:**
- (2x + 3)² = 4x² + 12x + 9
- (5x - 2)(5x + 2) = 25x² - 4
- (x + 1)³ = x³ + 3x² + 3x + 1

### 4.3 Factoring Polynomials

#### Method 1: Common Factor
**Example:** 6x³ + 9x² - 3x = 3x(2x² + 3x - 1)

#### Method 2: Grouping
**Example:** x³ + 2x² + 3x + 6
= x²(x + 2) + 3(x + 2)
= (x² + 3)(x + 2)

#### Method 3: Special Patterns

**Difference of Squares:** a² - b² = (a + b)(a - b)
**Example:** x² - 25 = (x + 5)(x - 5)

**Perfect Square Trinomial:** a² ± 2ab + b² = (a ± b)²
**Example:** x² + 6x + 9 = (x + 3)²

#### Method 4: Quadratic Trinomials
**For ax² + bx + c**, find two numbers that:
- Multiply to ac
- Add to b

**Example:** x² + 5x + 6
Need two numbers that multiply to 6 and add to 5: 2 and 3
x² + 5x + 6 = (x + 2)(x + 3)

### 4.4 Polynomial Division

#### Long Division Method
**Example:** Divide (2x³ + 3x² - 8x + 3) by (x + 2)

```
                2x² - x - 6
              ________________
    x + 2  |  2x³ + 3x² - 8x + 3
              2x³ + 4x²
              ___________
                  -x² - 8x
                  -x² - 2x  
                  _________
                      -6x + 3
                      -6x - 12
                      ________
                           15
```

**Answer:** 2x² - x - 6 + 15/(x + 2)

#### Synthetic Division
**Use when dividing by (x - a)**

**Example:** Divide (x³ - 6x² + 11x - 6) by (x - 2)

```
  2  |  1  -6   11  -6
     |     2  -8    6
     |________________
        1  -4    3   0
```

**Answer:** x² - 4x + 3 (remainder 0)

### 4.5 Exponents and Logarithms

#### Laws of Exponents
1. **Product Rule:** aᵐ × aⁿ = aᵐ⁺ⁿ
2. **Quotient Rule:** aᵐ ÷ aⁿ = aᵐ⁻ⁿ  
3. **Power Rule:** (aᵐ)ⁿ = aᵐⁿ
4. **Power of Product:** (ab)ⁿ = aⁿbⁿ
5. **Power of Quotient:** (a/b)ⁿ = aⁿ/bⁿ
6. **Zero Exponent:** a⁰ = 1 (a ≠ 0)
7. **Negative Exponent:** a⁻ⁿ = 1/aⁿ

**Examples:**
- 2³ × 2⁴ = 2⁷ = 128
- x⁸ ÷ x³ = x⁵
- (3²)⁴ = 3⁸
- (2x)³ = 8x³
- 5⁻² = 1/25

#### Introduction to Logarithms
**Definition:** If aˣ = y, then log_a(y) = x

**Common Logarithms:**
- log₁₀(x) = log(x) (base 10)
- logₑ(x) = ln(x) (natural log, base e)

**Properties:**
1. log_a(xy) = log_a(x) + log_a(y)
2. log_a(x/y) = log_a(x) - log_a(y)  
3. log_a(xⁿ) = n·log_a(x)
4. log_a(a) = 1
5. log_a(1) = 0

**Example:** Solve 2ˣ = 16
Since 16 = 2⁴, we have 2ˣ = 2⁴
Therefore, x = 4

### 4.6 Sequences and Series

#### Arithmetic Progression (AP)
**Definition:** Sequence where difference between consecutive terms is constant

**General Term:** aₙ = a + (n-1)d
- a = first term
- d = common difference  
- n = term number

**Sum of n terms:** Sₙ = n/2[2a + (n-1)d] or Sₙ = n/2[a + l]
where l = last term

**Example:** Find 10th term and sum of first 10 terms of AP: 3, 7, 11, 15...

**Solution:**
a = 3, d = 4
a₁₀ = 3 + (10-1)×4 = 3 + 36 = 39
S₁₀ = 10/2[2×3 + (10-1)×4] = 5[6 + 36] = 5×42 = 210

#### Geometric Progression (GP)
**Definition:** Sequence where ratio between consecutive terms is constant

**General Term:** aₙ = ar^(n-1)
- a = first term
- r = common ratio

**Sum of n terms:** Sₙ = a(rⁿ - 1)/(r - 1) if r ≠ 1
**Sum to infinity:** S∞ = a/(1 - r) if |r| < 1

**Example:** Find 5th term of GP: 2, 6, 18, 54...

**Solution:**
a = 2, r = 3
a₅ = 2×3⁴ = 2×81 = 162

---

## Practice Questions and PYQs

### Week 1 Practice Questions

**Q1:** If A = {1, 2, 3, 4} and B = {3, 4, 5, 6}, find A ∪ B, A ∩ B, and A - B.

**Solution:**
- A ∪ B = {1, 2, 3, 4, 5, 6}
- A ∩ B = {3, 4}  
- A - B = {1, 2}

**Q2:** Find the domain and range of f(x) = √(x - 2).

**Solution:**
- For √(x - 2) to be real, x - 2 ≥ 0, so x ≥ 2
- Domain: [2, ∞)
- Range: [0, ∞)

**Q3:** If f(x) = 2x + 1 and g(x) = x² - 1, find (f ∘ g)(x).

**Solution:**
(f ∘ g)(x) = f(g(x)) = f(x² - 1) = 2(x² - 1) + 1 = 2x² - 2 + 1 = 2x² - 1

### Week 2 Practice Questions  

**Q4:** Find the equation of line passing through (2, 3) and perpendicular to line 2x + 3y = 6.

**Solution:**
Given line: 2x + 3y = 6 ⟹ y = -2x/3 + 2
Slope of given line = -2/3
Slope of perpendicular line = 3/2

Using point-slope form: y - 3 = (3/2)(x - 2)
y - 3 = (3/2)x - 3
y = (3/2)x

**Q5:** Find the distance between points (-1, 2) and (3, -1).

**Solution:**
d = √[(3-(-1))² + (-1-2)²] = √[16 + 9] = √25 = 5

### Week 3 Practice Questions

**Q6:** Find vertex and axis of symmetry of f(x) = 2x² - 8x + 5.

**Solution:**
a = 2, b = -8, c = 5
Axis of symmetry: x = -b/(2a) = 8/4 = 2
Vertex y-coordinate: f(2) = 2(4) - 8(2) + 5 = 8 - 16 + 5 = -3
Vertex: (2, -3)

**Q7:** Solve x² - 5x + 6 = 0 using factoring.

**Solution:**
x² - 5x + 6 = 0
(x - 2)(x - 3) = 0
x = 2 or x = 3

### Week 4 Practice Questions

**Q8:** Factor x³ - 8 completely.

**Solution:**
x³ - 8 = x³ - 2³ = (x - 2)(x² + 2x + 4)

**Q9:** If 2ˣ = 32, find x.

**Solution:**
2ˣ = 32 = 2⁵
Therefore, x = 5

**Q10:** Find the sum of first 8 terms of AP: 5, 9, 13, 17...

**Solution:**
a = 5, d = 4, n = 8
S₈ = 8/2[2×5 + (8-1)×4] = 4[10 + 28] = 4×38 = 152

### Previous Year Questions (PYQs)

**PYQ 1 (2023):** The number of elements in the power set of {1, 2, 3} is:
(a) 6  (b) 8  (c) 9  (d) 12

**Solution:** For a set with n elements, power set has 2ⁿ elements.
Here n = 3, so power set has 2³ = 8 elements. **Answer: (b)**

**PYQ 2 (2022):** If f(x) = x² + 1 and g(x) = 2x - 1, then f(g(2)) equals:
(a) 8  (b) 10  (c) 12  (d) 14

**Solution:**
g(2) = 2(2) - 1 = 3
f(g(2)) = f(3) = 3² + 1 = 10 **Answer: (b)**

**PYQ 3 (2023):** The roots of x² - 6x + 9 = 0 are:
(a) 3, 3  (b) 3, -3  (c) 2, 4  (d) 1, 5

**Solution:**
x² - 6x + 9 = (x - 3)² = 0
So x = 3 (repeated root) **Answer: (a)**

**PYQ 4 (2022):** The slope of line passing through (1, 2) and (4, 8) is:
(a) 1  (b) 2  (c) 3  (d) 4

**Solution:**
m = (8-2)/(4-1) = 6/3 = 2 **Answer: (b)**

**PYQ 5 (2023):** The vertex of parabola y = x² - 4x + 7 is:
(a) (2, 3)  (b) (2, 7)  (c) (4, 7)  (d) (-2, 19)

**Solution:**
x-coordinate: x = 4/(2×1) = 2
y-coordinate: y = 4 - 8 + 7 = 3
Vertex: (2, 3) **Answer: (a)**

---

## Quick Revision Guide

### Formula Sheet

#### Coordinate Geometry
- **Distance:** d = √[(x₂-x₁)² + (y₂-y₁)²]
- **Midpoint:** M = ((x₁+x₂)/2, (y₁+y₂)/2)
- **Slope:** m = (y₂-y₁)/(x₂-x₁)
- **Line equation:** y - y₁ = m(x - x₁)

#### Quadratic Functions  
- **Vertex x-coordinate:** x = -b/(2a)
- **Discriminant:** Δ = b² - 4ac
- **Quadratic formula:** x = [-b ± √Δ]/(2a)

#### Sequences
- **AP:** aₙ = a + (n-1)d, Sₙ = n/2[2a + (n-1)d]
- **GP:** aₙ = ar^(n-1), Sₙ = a(rⁿ-1)/(r-1)

#### Exponents
- aᵐ × aⁿ = aᵐ⁺ⁿ
- aᵐ ÷ aⁿ = aᵐ⁻ⁿ
- (aᵐ)ⁿ = aᵐⁿ
- a⁰ = 1, a⁻ⁿ = 1/aⁿ

### Common Mistakes to Avoid

1. **Sign errors** in coordinate geometry calculations
2. **Forgetting domain restrictions** for functions like √x
3. **Not checking discriminant** before using quadratic formula
4. **Mixing up parallel/perpendicular slope relationships**
5. **Arithmetic errors** in polynomial operations
6. **Forgetting to check answers** by substitution

### Study Tips for Last Week

1. **Practice 2-3 PYQs daily** from each topic
2. **Focus on weak areas** identified through practice
3. **Memorize key formulas** using flashcards  
4. **Time yourself** on practice sets (aim for 2 minutes per question)
5. **Review mistakes** and understand why they occurred

### Exam Strategy

1. **Read questions carefully** - don't rush
2. **Start with easier questions** to build confidence
3. **Show your work clearly** for partial credit
4. **Check answers** if time permits
5. **Don't spend too much time** on any single question
6. **Use elimination method** for MCQs when unsure

---

**Good luck with your IIT Madras BS Qualifier Exam! Remember: consistent practice and understanding concepts (not just memorizing) is the key to success.**

---

*Note: This guide covers the essential topics for the Mathematics 1 portion of the qualifier exam. Supplement this with official course materials and additional practice from your preferred resources.*