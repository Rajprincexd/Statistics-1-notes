# Computational Thinking - Complete Study Notes for IIT Madras BS Degree Qualifier

**Duration: 4 Weeks | Target: Anyone with zero programming background | Goal: Master qualifier concepts**

---

## Table of Contents

1. [Week 1: Problem-Solving and Algorithms](#week-1)
2. [Week 2: Flowcharts, Pseudocode and Programming Logic](#week-2)
3. [Week 3: Number Systems and Logic Gates](#week-3)  
4. [Week 4: Programming Concepts and Applications](#week-4)
5. [Practice Questions and PYQs](#practice-questions)
6. [Quick Revision Guide](#quick-revision)

---

## Week 1: Problem-Solving and Algorithms

### 1.1 What is Computational Thinking?

**Definition**: A problem-solving process that breaks down complex problems into smaller, manageable parts using concepts fundamental to computer science.

Think of computational thinking as a way of thinking like a computer scientist - systematic, logical, and step-by-step.

#### Four Pillars of Computational Thinking

**1. Decomposition**
Breaking down complex problems into smaller, more manageable sub-problems.

**Example**: Planning a birthday party
- Big problem: Organize a birthday party
- Smaller problems: 
  - Choose venue
  - Send invitations  
  - Order cake
  - Plan activities
  - Arrange music

**2. Pattern Recognition**
Identifying similarities and patterns in problems.

**Example**: Solving math problems
- All quadratic equations follow similar solving patterns
- Recipe instructions follow similar formats
- Daily routines have patterns

**3. Abstraction**
Focusing on essential features while ignoring irrelevant details.

**Example**: London Underground Map
- Shows: Stations, connections, lines
- Hides: Actual distances, street details, building locations
- Focus: How to get from A to B

**4. Algorithm Design**
Creating step-by-step solutions that can be followed repeatedly.

**Example**: Making tea
1. Boil water
2. Add tea leaves/bag
3. Wait 3-5 minutes
4. Add sugar (optional)
5. Add milk (optional)
6. Serve

### 1.2 What is an Algorithm?

**Definition**: A finite sequence of well-defined, step-by-step instructions to solve a problem or accomplish a task.

#### Characteristics of a Good Algorithm

**1. Clear and Unambiguous**
- Each step should be precisely defined
- No confusion about what to do

**2. Finite**
- Must terminate after finite number of steps
- Should not run forever

**3. Effective**
- Each step must be doable
- Should produce correct result

**4. Input/Output**
- Should clearly define what inputs are needed
- Should specify what output is produced

#### Real-World Algorithm Examples

**Example 1: Finding Maximum Number**
**Problem**: Find the largest number in a list: [23, 45, 67, 12, 89, 34]

**Algorithm**:
1. Start with first number as maximum (max = 23)
2. Compare max with next number (45)
3. If next number is larger, update max (max = 45)
4. Repeat step 2-3 for all remaining numbers
5. Return max as the answer

**Step-by-step execution**:
- Start: max = 23
- Compare with 45: 45 > 23, so max = 45
- Compare with 67: 67 > 45, so max = 67  
- Compare with 12: 12 < 67, so max remains 67
- Compare with 89: 89 > 67, so max = 89
- Compare with 34: 34 < 89, so max remains 89
- **Answer**: 89

**Example 2: GCD (Greatest Common Divisor) - Euclidean Algorithm**
**Problem**: Find GCD of 48 and 18

**Algorithm**:
1. If second number is 0, return first number
2. Otherwise, replace first number with second number
3. Replace second number with remainder of (first ÷ second)
4. Repeat steps 1-3

**Execution**:
- Step 1: GCD(48, 18)
- Step 2: 48 ÷ 18 = 2 remainder 12, so GCD(18, 12)
- Step 3: 18 ÷ 12 = 1 remainder 6, so GCD(12, 6)
- Step 4: 12 ÷ 6 = 2 remainder 0, so GCD(6, 0)
- Step 5: Second number is 0, so **answer is 6**

### 1.3 Problem-Solving Strategies

#### Strategy 1: Divide and Conquer
Break the problem into smaller sub-problems, solve each, then combine solutions.

**Example**: Sorting a large list of numbers
1. Divide list into two halves
2. Sort each half separately  
3. Merge the sorted halves

#### Strategy 2: Greedy Approach
Make the locally optimal choice at each step.

**Example**: Making change for ₹67 using coins of ₹50, ₹20, ₹10, ₹5, ₹1
- Use one ₹50 coin (remaining: ₹17)
- Use zero ₹20 coins (₹20 > ₹17)
- Use one ₹10 coin (remaining: ₹7)
- Use one ₹5 coin (remaining: ₹2)
- Use two ₹1 coins (remaining: ₹0)
- **Solution**: 1×₹50 + 1×₹10 + 1×₹5 + 2×₹1

#### Strategy 3: Brute Force
Try all possible solutions and pick the best one.

**Example**: Finding shortest route visiting 4 cities
- List all possible routes: 4! = 24 routes
- Calculate distance for each route
- Pick the shortest one

**Note**: Works for small problems but becomes slow for larger ones.

### 1.4 Algorithm Efficiency

#### Time Complexity
How execution time increases with input size.

**Common Categories**:
- **Constant Time**: O(1) - Same time regardless of input size
- **Linear Time**: O(n) - Time proportional to input size
- **Quadratic Time**: O(n²) - Time proportional to square of input size

**Example Comparison**: Finding maximum in list of n numbers
- **Linear search**: Check each number once → O(n)
- **If list was sorted**: Could use binary search → O(log n)

#### Space Complexity
How much memory the algorithm uses.

**Example**: Storing a list of n numbers requires O(n) space.

### 1.5 Common Algorithm Types

#### 1. Searching Algorithms

**Linear Search**
- Check each element one by one
- Works on unsorted data
- Time complexity: O(n)

**Algorithm**:
1. Start from first element
2. Compare with target value
3. If match found, return position
4. If not found, move to next element
5. Repeat until found or end of list

**Binary Search** (for sorted data)
- Divide and conquer approach
- Much faster than linear search
- Time complexity: O(log n)

**Algorithm**:
1. Find middle element
2. If middle equals target, return position
3. If target < middle, search left half
4. If target > middle, search right half
5. Repeat until found or no more elements

#### 2. Sorting Algorithms

**Bubble Sort**
- Compare adjacent elements and swap if needed
- Simple but slow for large data
- Time complexity: O(n²)

**Algorithm**:
1. Compare first two elements
2. Swap if first > second  
3. Move to next pair
4. Repeat for entire list
5. Repeat entire process until no swaps needed

**Example**: Sort [64, 34, 25, 12]
- Pass 1: [34, 25, 12, 64] (64 bubbles to end)
- Pass 2: [25, 12, 34, 64] (34 moves to position)
- Pass 3: [12, 25, 34, 64] (25 moves to position)
- **Result**: [12, 25, 34, 64]

### 1.6 Algorithm Analysis Practice

**Practice Problem 1**: Sum of First N Natural Numbers

**Approach 1**: Using Loop
```
Algorithm:
1. Set sum = 0
2. For i = 1 to N:
   - Add i to sum
3. Return sum
```
**Time Complexity**: O(n)

**Approach 2**: Using Formula
```
Algorithm:  
1. Calculate sum = N × (N + 1) / 2
2. Return sum
```
**Time Complexity**: O(1)

**Example**: N = 5
- Approach 1: 1 + 2 + 3 + 4 + 5 = 15
- Approach 2: 5 × 6 / 2 = 15

Both give same result, but Approach 2 is much faster for large N!

**Practice Problem 2**: Check if Number is Prime

**Algorithm**:
1. If number ≤ 1, return "Not Prime"
2. For i = 2 to √number:
   - If number is divisible by i, return "Not Prime"
3. Return "Prime"

**Example**: Check if 29 is prime
- Check divisibility by 2: 29 ÷ 2 = 14.5 (not divisible)
- Check divisibility by 3: 29 ÷ 3 = 9.67 (not divisible)
- Check divisibility by 4: 29 ÷ 4 = 7.25 (not divisible)
- Check divisibility by 5: 29 ÷ 5 = 5.8 (not divisible)
- Stop at 5 because 5² = 25 < 29 and 6² = 36 > 29
- **Result**: 29 is prime

---

## Week 2: Flowcharts, Pseudocode and Programming Logic

### 2.1 What are Flowcharts?

**Definition**: A visual representation of the step-by-step solution to a problem using standardized symbols connected by arrows.

Think of flowcharts as a map showing the path from problem to solution.

#### Why Use Flowcharts?

**Advantages**:
1. **Visual clarity**: Easier to understand than text
2. **Logic verification**: Can spot errors in thinking
3. **Communication**: Share ideas with others easily
4. **Planning**: Plan before writing code
5. **Documentation**: Record how solution works

#### Standard Flowchart Symbols

**1. Terminal (Oval)**
- **Purpose**: Start and End points
- **Shape**: Oval or rounded rectangle
- **Examples**: "START", "STOP", "END"

**2. Process (Rectangle)**  
- **Purpose**: Processing steps, calculations, assignments
- **Shape**: Rectangle
- **Examples**: "Add 5 to X", "Set total = 0", "Calculate area"

**3. Decision (Diamond)**
- **Purpose**: Questions requiring Yes/No or True/False answers
- **Shape**: Diamond
- **Examples**: "Is X > 10?", "End of data?", "Password correct?"

**4. Input/Output (Parallelogram)**
- **Purpose**: Getting input from user or showing output
- **Shape**: Parallelogram
- **Examples**: "Enter your name", "Display result", "Read number"

**5. Connector (Circle)**
- **Purpose**: Connect different parts of flowchart
- **Shape**: Small circle
- **Examples**: Connect flowchart across pages

**6. Flow Lines (Arrows)**
- **Purpose**: Show direction of flow
- **Shape**: Lines with arrowheads
- **Examples**: Connect all symbols

### 2.2 Creating Flowcharts - Step by Step

#### Example 1: Simple Calculator (Addition)

**Problem**: Create a program to add two numbers.

**Flowchart**:
```
    START
      ↓
   Input A
      ↓  
   Input B
      ↓
  Sum = A + B
      ↓
  Display Sum
      ↓
     END
```

**Step-by-step process**:
1. **Start**: Begin the program
2. **Input A**: Get first number from user
3. **Input B**: Get second number from user
4. **Process**: Calculate sum = A + B
5. **Output**: Display the result
6. **End**: Terminate the program

#### Example 2: Find Maximum of Two Numbers

**Problem**: Compare two numbers and find the larger one.

**Flowchart**:
```
    START
      ↓
   Input A
      ↓
   Input B
      ↓
   Is A > B?
     ↙    ↘
   Yes      No
    ↓        ↓
Display A  Display B
    ↓        ↓
     END ←─── 
```

**Logic explanation**:
1. Get two numbers from user
2. Compare them using decision symbol
3. Based on comparison, choose which number to display
4. Both paths lead to the same end point

#### Example 3: Sum of First N Natural Numbers

**Problem**: Find sum of 1 + 2 + 3 + ... + N

**Flowchart**:
```
    START
      ↓
   Input N
      ↓
   Sum = 0
      ↓
    I = 1
      ↓
   Is I ≤ N? ───No──→ Display Sum ──→ END
      ↓ Yes            
   Sum = Sum + I
      ↓
    I = I + 1
      ↓
      └──────┘ (loop back to "Is I ≤ N?")
```

**Trace through example** (N = 4):
- Initial: Sum = 0, I = 1
- Loop 1: I ≤ 4? Yes. Sum = 0+1=1, I = 2
- Loop 2: I ≤ 4? Yes. Sum = 1+2=3, I = 3
- Loop 3: I ≤ 4? Yes. Sum = 3+3=6, I = 4
- Loop 4: I ≤ 4? Yes. Sum = 6+4=10, I = 5
- Loop 5: I ≤ 4? No. Display Sum = 10, END

### 2.3 What is Pseudocode?

**Definition**: An informal high-level description of a computer program's logic using natural language mixed with programming constructs.

Pseudocode is like writing instructions in plain English but with some structure.

#### Pseudocode Conventions

**1. Structure**:
- BEGIN/END for program boundaries
- Indentation to show program structure
- Clear, concise statements

**2. Common Keywords**:
- INPUT/READ: Get data from user
- OUTPUT/PRINT/DISPLAY: Show results
- SET/LET: Assign values to variables
- IF/THEN/ELSE: Decision making
- WHILE/FOR: Loops
- BEGIN/END: Program blocks

#### Pseudocode Examples

**Example 1**: Simple Calculator
```
BEGIN Addition Program
    PRINT "Enter first number:"
    INPUT first_number
    PRINT "Enter second number:"
    INPUT second_number
    SET sum = first_number + second_number
    PRINT "The sum is: " + sum
END
```

**Example 2**: Grade Calculator
```
BEGIN Grade Calculator
    PRINT "Enter your score:"
    INPUT score
    
    IF score >= 90 THEN
        SET grade = "A"
    ELSE IF score >= 80 THEN
        SET grade = "B"
    ELSE IF score >= 70 THEN
        SET grade = "C"
    ELSE IF score >= 60 THEN
        SET grade = "D"
    ELSE
        SET grade = "F"
    END IF
    
    PRINT "Your grade is: " + grade
END
```

**Example 3**: Factorial Calculation
```
BEGIN Factorial Calculator
    PRINT "Enter a positive integer:"
    INPUT n
    SET factorial = 1
    SET i = 1
    
    WHILE i <= n DO
        SET factorial = factorial * i
        SET i = i + 1
    END WHILE
    
    PRINT n + "! = " + factorial
END
```

### 2.4 Control Structures

#### 1. Sequence Structure
Instructions executed one after another in order.

**Example**: Making tea
1. Boil water
2. Add tea leaves  
3. Add sugar
4. Add milk
5. Serve

#### 2. Selection Structure (Decision Making)
Choose between alternative paths based on conditions.

**Types**:

**Simple IF**:
```
IF condition THEN
    action
END IF
```

**IF-ELSE**:
```  
IF condition THEN
    action1
ELSE
    action2
END IF
```

**Multi-way Selection**:
```
IF condition1 THEN
    action1
ELSE IF condition2 THEN
    action2
ELSE IF condition3 THEN
    action3
ELSE
    default_action
END IF
```

#### 3. Iteration Structure (Loops)
Repeat actions multiple times.

**Types**:

**WHILE Loop** (condition checked before each iteration):
```
WHILE condition DO
    actions
END WHILE
```

**FOR Loop** (fixed number of iterations):
```
FOR variable = start_value TO end_value DO
    actions
END FOR
```

### 2.5 Common Programming Logic Patterns

#### Pattern 1: Input Validation
Ensure user enters valid data.

**Pseudocode**:
```
BEGIN Input Validation
    REPEAT
        PRINT "Enter a positive number:"
        INPUT number
        IF number <= 0 THEN
            PRINT "Error: Number must be positive!"
        END IF
    UNTIL number > 0
    
    PRINT "Thank you! You entered: " + number
END
```

#### Pattern 2: Menu-Driven Program
Let user choose from options.

**Pseudocode**:
```
BEGIN Calculator Menu
    REPEAT
        PRINT "Calculator Menu:"
        PRINT "1. Addition"
        PRINT "2. Subtraction"  
        PRINT "3. Multiplication"
        PRINT "4. Division"
        PRINT "5. Exit"
        PRINT "Enter choice:"
        INPUT choice
        
        IF choice = 1 THEN
            // Addition logic
        ELSE IF choice = 2 THEN
            // Subtraction logic
        ELSE IF choice = 3 THEN
            // Multiplication logic
        ELSE IF choice = 4 THEN
            // Division logic
        ELSE IF choice = 5 THEN
            PRINT "Goodbye!"
        ELSE
            PRINT "Invalid choice!"
        END IF
    UNTIL choice = 5
END
```

#### Pattern 3: Data Processing
Process a series of data items.

**Example**: Find average of student scores
```
BEGIN Average Calculator
    SET total = 0
    SET count = 0
    
    PRINT "Enter scores (enter -1 to stop):"
    INPUT score
    
    WHILE score != -1 DO
        SET total = total + score
        SET count = count + 1
        INPUT score
    END WHILE
    
    IF count > 0 THEN
        SET average = total / count
        PRINT "Average score: " + average
    ELSE
        PRINT "No scores entered!"
    END IF
END
```

### 2.6 Converting Between Representations

#### From Problem Statement to Pseudocode to Flowchart

**Problem**: Check if a number is even or odd.

**Step 1: Understand Problem**
- Input: A number
- Process: Check if divisible by 2
- Output: "Even" or "Odd"

**Step 2: Write Pseudocode**
```
BEGIN Even-Odd Checker
    PRINT "Enter a number:"
    INPUT number
    
    IF number MOD 2 = 0 THEN
        PRINT number + " is even"
    ELSE
        PRINT number + " is odd"
    END IF
END
```

**Step 3: Draw Flowchart**
```
    START
      ↓
   Input number
      ↓
  Is number MOD 2 = 0?
     ↙         ↘
   Yes          No
    ↓            ↓
Print "Even"  Print "Odd"
    ↓            ↓
     END ←────────
```

---

## Week 3: Number Systems and Logic Gates

### 3.1 Introduction to Number Systems

#### What are Number Systems?
**Definition**: Different ways of representing numbers using different bases (radix).

In daily life, we use decimal (base 10), but computers use binary (base 2).

#### Common Number Systems

**1. Decimal (Base 10)**
- Uses digits: 0, 1, 2, 3, 4, 5, 6, 7, 8, 9
- Position values: ...10³, 10², 10¹, 10⁰
- Example: 1234 = 1×10³ + 2×10² + 3×10¹ + 4×10⁰

**2. Binary (Base 2)**
- Uses digits: 0, 1
- Position values: ...2³, 2², 2¹, 2⁰
- Example: 1011₂ = 1×2³ + 0×2² + 1×2¹ + 1×2⁰ = 8 + 0 + 2 + 1 = 11₁₀

**3. Octal (Base 8)**
- Uses digits: 0, 1, 2, 3, 4, 5, 6, 7
- Position values: ...8³, 8², 8¹, 8⁰
- Example: 127₈ = 1×8² + 2×8¹ + 7×8⁰ = 64 + 16 + 7 = 87₁₀

**4. Hexadecimal (Base 16)**
- Uses digits: 0-9, A-F (A=10, B=11, C=12, D=13, E=14, F=15)
- Position values: ...16³, 16², 16¹, 16⁰
- Example: 2AB₁₆ = 2×16² + 10×16¹ + 11×16⁰ = 512 + 160 + 11 = 683₁₀

### 3.2 Number System Conversions

#### 1. Decimal to Binary Conversion

**Method**: Divide by 2 repeatedly, collect remainders from bottom to top.

**Example**: Convert 25₁₀ to binary
```
25 ÷ 2 = 12 remainder 1
12 ÷ 2 = 6  remainder 0  
6  ÷ 2 = 3  remainder 0
3  ÷ 2 = 1  remainder 1
1  ÷ 2 = 0  remainder 1

Reading from bottom to top: 25₁₀ = 11001₂
```

**Verification**: 1×2⁴ + 1×2³ + 0×2² + 0×2¹ + 1×2⁰ = 16 + 8 + 0 + 0 + 1 = 25 ✓

#### 2. Binary to Decimal Conversion

**Method**: Multiply each digit by its position value and sum.

**Example**: Convert 1101₂ to decimal
```
Position values: 2³  2²  2¹  2⁰
Digits:          1   1   0   1

1×2³ + 1×2² + 0×2¹ + 1×2⁰
= 1×8 + 1×4 + 0×2 + 1×1
= 8 + 4 + 0 + 1
= 13₁₀
```

#### 3. Decimal to Hexadecimal Conversion

**Method**: Divide by 16 repeatedly, collect remainders.

**Example**: Convert 255₁₀ to hexadecimal
```
255 ÷ 16 = 15 remainder 15 (F in hex)
15  ÷ 16 = 0  remainder 15 (F in hex)

Reading from bottom to top: 255₁₀ = FF₁₆
```

**Verification**: F×16¹ + F×16⁰ = 15×16 + 15×1 = 240 + 15 = 255 ✓

#### 4. Binary to Hexadecimal (Quick Method)

**Method**: Group binary digits in sets of 4 (from right), convert each group.

**Example**: Convert 11010011₂ to hexadecimal
```
11010011₂ = 1101 0011
            ↓    ↓
           D₁₆   3₁₆

Result: 11010011₂ = D3₁₆
```

**Conversion table for 4-bit groups**:
```
0000 = 0    0100 = 4    1000 = 8    1100 = C
0001 = 1    0101 = 5    1001 = 9    1101 = D  
0010 = 2    0110 = 6    1010 = A    1110 = E
0011 = 3    0111 = 7    1011 = B    1111 = F
```

### 3.3 Binary Arithmetic

#### 1. Binary Addition

**Rules**:
- 0 + 0 = 0
- 0 + 1 = 1  
- 1 + 0 = 1
- 1 + 1 = 10 (0 with carry 1)

**Example**: Add 1011₂ + 1101₂
```
   1011
 + 1101
 ------
  11000

Step by step:
1 + 1 = 10 (write 0, carry 1)
1 + 0 + 1(carry) = 10 (write 0, carry 1)  
0 + 1 + 1(carry) = 10 (write 0, carry 1)
1 + 1 + 1(carry) = 11 (write 1, carry 1)
0 + 0 + 1(carry) = 1

Result: 11000₂
```

**Verification in decimal**:
- 1011₂ = 11₁₀
- 1101₂ = 13₁₀  
- 11₁₀ + 13₁₀ = 24₁₀
- 11000₂ = 24₁₀ ✓

#### 2. Binary Subtraction

**Rules**:
- 0 - 0 = 0
- 1 - 0 = 1
- 1 - 1 = 0  
- 0 - 1 = 1 (with borrow from next position)

**Example**: Subtract 1010₂ - 0011₂
```
  1010
- 0011
------
  0111

Result: 0111₂ = 7₁₀
```

### 3.4 Introduction to Logic Gates

#### What are Logic Gates?
**Definition**: Electronic circuits that perform logical operations on binary inputs to produce binary outputs.

Logic gates are the building blocks of digital computers.

#### Basic Logic Gates

#### 1. AND Gate
**Function**: Output is 1 only when ALL inputs are 1

**Truth Table**:
```
A | B | Output
--|---|-------
0 | 0 |   0
0 | 1 |   0
1 | 0 |   0  
1 | 1 |   1
```

**Symbol**: Rectangle with curved input side

**Real-world analogy**: A door that opens only when BOTH keys are turned.

#### 2. OR Gate
**Function**: Output is 1 when ANY input is 1

**Truth Table**:
```
A | B | Output
--|---|-------
0 | 0 |   0
0 | 1 |   1
1 | 0 |   1
1 | 1 |   1
```

**Real-world analogy**: A door that opens when ANY valid card is swiped.

#### 3. NOT Gate (Inverter)
**Function**: Output is opposite of input

**Truth Table**:
```
A | Output
--|-------
0 |   1
1 |   0
```

**Real-world analogy**: A switch that turns light OFF when pressed, ON when released.

#### 4. NAND Gate
**Function**: NOT + AND = Output is 0 only when ALL inputs are 1

**Truth Table**:
```
A | B | Output
--|---|-------
0 | 0 |   1
0 | 1 |   1
1 | 0 |   1
1 | 1 |   0
```

**Note**: NAND is a universal gate - can create any other gate using only NAND gates.

#### 5. NOR Gate  
**Function**: NOT + OR = Output is 1 only when ALL inputs are 0

**Truth Table**:
```
A | B | Output
--|---|-------
0 | 0 |   1
0 | 1 |   0
1 | 0 |   0
1 | 1 |   0
```

#### 6. XOR Gate (Exclusive OR)
**Function**: Output is 1 when inputs are different

**Truth Table**:
```
A | B | Output
--|---|-------
0 | 0 |   0
0 | 1 |   1
1 | 0 |   1
1 | 1 |   0
```

**Real-world analogy**: A room light controlled by two switches - flipping either switch changes the light state.

### 3.5 Logic Gate Applications

#### Example 1: Home Security System
**Requirements**: Alarm sounds if door is open OR window is open AND motion is detected.

**Logic**: Alarm = Door OR (Window AND Motion)

**Implementation**:
```
Door ──┐
       │
       OR ── Alarm
       │
Window ──┐
        AND
Motion ──┘
```

#### Example 2: Voting System
**Requirements**: Decision passes if at least 2 out of 3 people vote YES.

**Logic**: Result = (A AND B) OR (B AND C) OR (A AND C)

**Truth Table**:
```
A | B | C | Result
--|---|---|-------
0 | 0 | 0 |   0
0 | 0 | 1 |   0
0 | 1 | 0 |   0
0 | 1 | 1 |   1  ← 2 votes
1 | 0 | 0 |   0
1 | 0 | 1 |   1  ← 2 votes
1 | 1 | 0 |   1  ← 2 votes
1 | 1 | 1 |   1  ← 3 votes
```

### 3.6 Boolean Algebra (Basic)

#### Laws of Boolean Algebra

**Identity Laws**:
- A + 0 = A (OR with 0)
- A · 1 = A (AND with 1)

**Null Laws**:
- A + 1 = 1 (OR with 1)
- A · 0 = 0 (AND with 0)

**Complement Laws**:
- A + A' = 1
- A · A' = 0

**De Morgan's Laws** (very important):
- (A + B)' = A' · B' (NOT of OR equals AND of NOTs)
- (A · B)' = A' + B' (NOT of AND equals OR of NOTs)

#### Simplification Example
**Original**: A · B + A · B'
**Simplify**: A · (B + B')    [Factor out A]
            = A · 1          [B + B' = 1]
            = A              [A · 1 = A]

This shows that A · B + A · B' can be simplified to just A.

---

## Week 4: Programming Concepts and Applications

### 4.1 Introduction to Programming

#### What is Programming?
**Definition**: The process of creating a set of instructions that tell a computer how to perform a task.

Programming is like teaching a computer to solve problems step by step.

#### Why Learn Programming Concepts?
1. **Problem-solving skills**: Learn to break down complex problems
2. **Logical thinking**: Develop systematic approach to solutions  
3. **Automation**: Make computers do repetitive tasks
4. **Career opportunities**: High demand in technology industry
5. **Understanding technology**: Better understand how digital world works

### 4.2 Variables and Data Types

#### Variables
**Definition**: Named storage locations that hold data values.

Think of variables as labeled boxes that store information.

**Variable Names (Identifiers)**:
- Must start with letter or underscore
- Can contain letters, numbers, underscores
- Cannot use reserved words (if, while, for, etc.)
- Case-sensitive (Name ≠ name)

**Examples**:
```
Valid:   name, age, student_count, firstName, _temp
Invalid: 2ndNumber, class, while, my-name
```

#### Data Types

**1. Integer (int)**
- Whole numbers: ..., -2, -1, 0, 1, 2, ...
- Examples: age = 25, count = 100, temperature = -5

**2. Float (Real numbers)**
- Numbers with decimal points: 3.14, -2.5, 0.001
- Examples: height = 5.8, price = 299.99, pi = 3.14159

**3. String (Text)**
- Sequence of characters enclosed in quotes
- Examples: name = "John", message = "Hello World", city = "Mumbai"

**4. Boolean**
- True or False values
- Examples: is_student = True, is_passed = False

**5. Character**
- Single character enclosed in quotes  
- Examples: grade = 'A', initial = 'J', symbol = '#'

#### Variable Declaration and Assignment

**Pseudocode Examples**:
```
// Declaration with assignment
SET name = "Alice"
SET age = 20  
SET height = 5.6
SET is_student = True

// Using variables
SET full_name = "Ms. " + name
SET next_year_age = age + 1
```

### 4.3 Expressions and Operators

#### Arithmetic Operators
```
+  Addition:       5 + 3 = 8
-  Subtraction:    5 - 3 = 2  
*  Multiplication: 5 * 3 = 15
/  Division:       5 / 3 = 1.67
%  Modulo:        5 % 3 = 2 (remainder)
^  Exponentiation: 5 ^ 3 = 125
```

#### Comparison Operators
```
==  Equal to:           5 == 3  → False
!=  Not equal to:       5 != 3  → True
>   Greater than:       5 > 3   → True
<   Less than:          5 < 3   → False  
>=  Greater or equal:   5 >= 3  → True
<=  Less or equal:      5 <= 3  → False
```

#### Logical Operators
```
AND  Both conditions true:     (5 > 3) AND (2 < 4)  → True
OR   At least one true:        (5 < 3) OR (2 < 4)   → True  
NOT  Opposite of condition:    NOT (5 > 3)          → False
```

#### Operator Precedence
Order of operations (like BODMAS in math):
1. Parentheses ()
2. Exponentiation ^
3. Multiplication *, Division /, Modulo %
4. Addition +, Subtraction -
5. Comparison operators
6. Logical operators

**Example**: 2 + 3 * 4 = 2 + 12 = 14 (not 20)

### 4.4 Control Flow Structures

#### 1. Sequential Execution
Instructions executed in order from top to bottom.

**Example**: Calculate area of rectangle
```
BEGIN Rectangle Area
    INPUT length
    INPUT width  
    SET area = length * width
    PRINT "Area is: " + area
END
```

#### 2. Selection (Conditional) Structures

**IF Statement**:
```
IF condition THEN
    statements
END IF
```

**IF-ELSE Statement**:
```
IF condition THEN
    statements1
ELSE  
    statements2
END IF
```

**Multi-way Selection**:
```
IF condition1 THEN
    statements1
ELSE IF condition2 THEN
    statements2  
ELSE IF condition3 THEN
    statements3
ELSE
    default_statements
END IF
```

**Example**: Grade Assignment
```
BEGIN Grade Calculator
    INPUT score
    
    IF score >= 90 THEN
        SET grade = "A"
    ELSE IF score >= 80 THEN
        SET grade = "B"
    ELSE IF score >= 70 THEN  
        SET grade = "C"
    ELSE IF score >= 60 THEN
        SET grade = "D"
    ELSE
        SET grade = "F"
    END IF
    
    PRINT "Your grade is: " + grade
END
```

#### 3. Iteration (Loop) Structures

**WHILE Loop** (condition tested before each iteration):
```
WHILE condition DO
    statements
END WHILE
```

**Example**: Countdown
```
BEGIN Countdown  
    SET count = 10
    WHILE count > 0 DO
        PRINT count
        SET count = count - 1
    END WHILE
    PRINT "Blast off!"
END
```

**FOR Loop** (fixed number of iterations):
```
FOR variable = start TO end DO
    statements
END FOR
```

**Example**: Multiplication Table
```
BEGIN Multiplication Table
    INPUT number
    FOR i = 1 TO 10 DO
        SET result = number * i
        PRINT number + " x " + i + " = " + result
    END FOR
END
```

### 4.5 Functions and Scope

#### What are Functions?
**Definition**: Reusable blocks of code that perform specific tasks.

Functions help organize code and avoid repetition.

#### Function Structure
```
FUNCTION function_name(parameters)
    // Function body
    statements
    RETURN value (optional)
END FUNCTION
```

#### Function Examples

**Example 1**: Simple Function
```
FUNCTION greet(name)
    PRINT "Hello, " + name + "!"
END FUNCTION

// Using the function  
CALL greet("Alice")
CALL greet("Bob")
```

**Example 2**: Function with Return Value
```
FUNCTION calculate_area(length, width)
    SET area = length * width
    RETURN area
END FUNCTION

// Using the function
SET room_area = calculate_area(10, 12)
PRINT "Room area is: " + room_area
```

**Example 3**: Mathematical Function
```
FUNCTION factorial(n)
    IF n <= 1 THEN
        RETURN 1
    ELSE
        RETURN n * factorial(n - 1)
    END IF
END FUNCTION

SET result = factorial(5)  // Returns 120
```

#### Variable Scope
**Definition**: The region of code where a variable can be accessed.

**Local Variables**:
- Declared inside functions
- Only accessible within that function
- Created when function starts, destroyed when function ends

**Global Variables**:
- Declared outside functions  
- Accessible throughout entire program
- Exist for entire program duration

**Example**:
```
SET global_var = "I am global"

FUNCTION example_function()
    SET local_var = "I am local"
    PRINT global_var  // Works
    PRINT local_var   // Works
END FUNCTION

PRINT global_var  // Works
PRINT local_var   // Error! local_var doesn't exist here
```

### 4.6 Arrays and Basic Data Structures

#### What are Arrays?
**Definition**: Collections of elements of the same data type, stored in contiguous memory locations.

Think of arrays as numbered boxes in a row, each holding one piece of data.

#### Array Declaration and Access
```
// Declaration
DECLARE numbers[5]  // Array of 5 integers
DECLARE names[3]    // Array of 3 strings

// Assignment  
SET numbers[0] = 10
SET numbers[1] = 20
SET numbers[2] = 30
SET numbers[3] = 40
SET numbers[4] = 50

SET names[0] = "Alice"
SET names[1] = "Bob"  
SET names[2] = "Charlie"
```

**Note**: Arrays typically start at index 0 (zero-based indexing).

#### Array Examples

**Example 1**: Find Sum of Array Elements
```
BEGIN Array Sum
    DECLARE numbers[5] = {10, 20, 30, 40, 50}
    SET sum = 0
    
    FOR i = 0 TO 4 DO
        SET sum = sum + numbers[i]
    END FOR
    
    PRINT "Sum is: " + sum  // Output: 150
END
```

**Example 2**: Find Maximum in Array
```
FUNCTION find_maximum(arr, size)
    SET max = arr[0]
    
    FOR i = 1 TO size-1 DO
        IF arr[i] > max THEN
            SET max = arr[i]
        END IF
    END FOR
    
    RETURN max
END FUNCTION
```

### 4.7 Searching and Sorting Algorithms

#### 1. Linear Search
**Purpose**: Find if an element exists in array.

**Algorithm**:
```
FUNCTION linear_search(arr, size, target)
    FOR i = 0 TO size-1 DO
        IF arr[i] == target THEN
            RETURN i  // Found at index i
        END IF
    END FOR
    RETURN -1  // Not found
END FUNCTION
```

**Example**: Search for 30 in [10, 20, 30, 40, 50]
- Check arr[0] = 10 ≠ 30
- Check arr[1] = 20 ≠ 30  
- Check arr[2] = 30 = 30 → Found at index 2

#### 2. Binary Search (for sorted arrays)
**Purpose**: Faster searching in sorted arrays.

**Algorithm**:
```
FUNCTION binary_search(arr, size, target)
    SET left = 0
    SET right = size - 1
    
    WHILE left <= right DO
        SET mid = (left + right) / 2
        
        IF arr[mid] == target THEN
            RETURN mid
        ELSE IF arr[mid] < target THEN
            SET left = mid + 1
        ELSE
            SET right = mid - 1
        END IF
    END WHILE
    
    RETURN -1  // Not found
END FUNCTION
```

#### 3. Bubble Sort
**Purpose**: Sort array in ascending order.

**Algorithm**:
```
FUNCTION bubble_sort(arr, size)
    FOR i = 0 TO size-2 DO
        FOR j = 0 TO size-2-i DO
            IF arr[j] > arr[j+1] THEN
                // Swap elements
                SET temp = arr[j]
                SET arr[j] = arr[j+1]
                SET arr[j+1] = temp
            END IF
        END FOR
    END FOR
END FUNCTION
```

**Example**: Sort [64, 34, 25, 12]
- Pass 1: [34, 25, 12, 64] (64 moves to end)
- Pass 2: [25, 12, 34, 64] (34 moves to position)
- Pass 3: [12, 25, 34, 64] (25 moves to position)

### 4.8 Problem-Solving with Programming

#### Problem-Solving Steps
1. **Understand the problem**
2. **Break into smaller parts**  
3. **Plan the solution**
4. **Write pseudocode**
5. **Test with examples**
6. **Refine and optimize**

#### Example Problem: Student Grade Management

**Problem**: Create a program to manage student grades and calculate statistics.

**Requirements**:
- Store grades for multiple students
- Calculate average grade
- Find highest and lowest grades
- Count students in each grade category

**Solution**:
```
BEGIN Student Grade Management
    DECLARE grades[100]
    SET num_students = 0
    
    // Input grades
    PRINT "Enter student grades (enter -1 to stop):"
    INPUT grade
    WHILE grade != -1 AND num_students < 100 DO
        grades[num_students] = grade
        SET num_students = num_students + 1
        INPUT grade
    END WHILE
    
    // Calculate statistics
    SET sum = 0
    SET max_grade = grades[0]
    SET min_grade = grades[0]
    
    FOR i = 0 TO num_students-1 DO
        SET sum = sum + grades[i]
        
        IF grades[i] > max_grade THEN
            SET max_grade = grades[i]
        END IF
        
        IF grades[i] < min_grade THEN
            SET min_grade = grades[i]
        END IF
    END FOR
    
    SET average = sum / num_students
    
    // Display results
    PRINT "Number of students: " + num_students
    PRINT "Average grade: " + average
    PRINT "Highest grade: " + max_grade
    PRINT "Lowest grade: " + min_grade
END
```

---

## Practice Questions and PYQs

### Algorithm and Problem-Solving Practice

**Q1**: Write an algorithm to find the second largest number in an array.

**Solution**:
```
ALGORITHM Find Second Largest
1. Initialize first = -infinity, second = -infinity
2. FOR each element in array DO
   a. IF element > first THEN
      - SET second = first
      - SET first = element
   b. ELSE IF element > second AND element != first THEN  
      - SET second = element
3. RETURN second
```

**Q2**: Create a flowchart to check if a year is a leap year.

**Logic**: A year is leap if:
- Divisible by 4 AND not divisible by 100, OR
- Divisible by 400

**Flowchart**:
```
START → Input year → Is year%4==0? 
                      ↓ Yes        ↓ No
                 Is year%100==0? → Print "Not Leap" → END
                  ↓ Yes    ↓ No
            Is year%400==0?  Print "Leap" → END  
             ↓ Yes   ↓ No
        Print "Leap" Print "Not Leap" → END
```

### Number Systems Practice

**Q3**: Convert 156₁₀ to binary.

**Solution**:
```
156 ÷ 2 = 78 remainder 0
78  ÷ 2 = 39 remainder 0
39  ÷ 2 = 19 remainder 1
19  ÷ 2 = 9  remainder 1
9   ÷ 2 = 4  remainder 1
4   ÷ 2 = 2  remainder 0
2   ÷ 2 = 1  remainder 0
1   ÷ 2 = 0  remainder 1

Answer: 156₁₀ = 10011100₂
```

**Q4**: What is 1A3₁₆ in decimal?

**Solution**:
1A3₁₆ = 1×16² + A×16¹ + 3×16⁰
      = 1×256 + 10×16 + 3×1
      = 256 + 160 + 3
      = 419₁₀

### Logic Gates Practice

**Q5**: Complete the truth table for (A AND B) OR (NOT C):

**Solution**:
```
A | B | C | NOT C | A AND B | Result
--|---|---|-------|---------|-------
0 | 0 | 0 |   1   |    0    |   1
0 | 0 | 1 |   0   |    0    |   0
0 | 1 | 0 |   1   |    0    |   1
0 | 1 | 1 |   0   |    0    |   0
1 | 0 | 0 |   1   |    0    |   1
1 | 0 | 1 |   0   |    0    |   0
1 | 1 | 0 |   1   |    1    |   1
1 | 1 | 1 |   0   |    1    |   1
```

### Programming Logic Practice

**Q6**: Write pseudocode to reverse an array.

**Solution**:
```
FUNCTION reverse_array(arr, size)
    SET start = 0
    SET end = size - 1
    
    WHILE start < end DO
        // Swap elements
        SET temp = arr[start]
        SET arr[start] = arr[end]
        SET arr[end] = temp
        
        SET start = start + 1
        SET end = end - 1
    END WHILE
END FUNCTION
```

### Previous Year Questions

**PYQ 1 (2023)**: What is the binary representation of 13₁₀?
(a) 1011 (b) 1101 (c) 1110 (d) 1001

**Answer: (b) 1101**
13 = 8 + 4 + 1 = 2³ + 2² + 2⁰ = 1101₂

**PYQ 2 (2022)**: In flowchart, which symbol is used for decision making?
(a) Rectangle (b) Oval (c) Diamond (d) Parallelogram

**Answer: (c) Diamond**

**PYQ 3 (2024)**: What does XOR gate output when both inputs are the same?
(a) Always 0 (b) Always 1 (c) Same as input (d) Opposite of input

**Answer: (a) Always 0**
XOR outputs 1 only when inputs are different.

**PYQ 4 (2023)**: Time complexity of linear search is:
(a) O(1) (b) O(log n) (c) O(n) (d) O(n²)

**Answer: (c) O(n)**
Linear search may need to check all n elements in worst case.

---

## Quick Revision Guide

### Key Algorithms to Remember

#### 1. Finding Maximum
```
max = first_element
FOR each remaining element:
    IF element > max:
        max = element
```

#### 2. Linear Search
```
FOR each element:
    IF element == target:
        RETURN position
RETURN "not found"
```

#### 3. Bubble Sort
```
FOR i = 0 to n-2:
    FOR j = 0 to n-2-i:
        IF arr[j] > arr[j+1]:
            SWAP(arr[j], arr[j+1])
```

### Number System Conversions

#### Decimal to Binary
Divide by 2, collect remainders bottom-to-top

#### Binary to Decimal  
Multiply each digit by power of 2, sum results

#### Binary to Hex
Group 4 binary digits, convert each group

### Logic Gate Truth Tables

Remember: 
- **AND**: All inputs 1 → Output 1
- **OR**: Any input 1 → Output 1  
- **XOR**: Inputs different → Output 1
- **NAND**: NOT(AND)
- **NOR**: NOT(OR)

### Flowchart Symbols
- **Oval**: Start/End
- **Rectangle**: Process
- **Diamond**: Decision
- **Parallelogram**: Input/Output

### Programming Concepts
- **Variables**: Store data values
- **Loops**: Repeat instructions
- **Conditionals**: Make decisions
- **Functions**: Reusable code blocks
- **Arrays**: Store multiple values

### Common Mistakes to Avoid
1. **Mixing up binary and decimal** in calculations
2. **Wrong flowchart symbols** for different operations
3. **Incorrect loop conditions** causing infinite loops
4. **Array index errors** (remember 0-based indexing)
5. **Logic gate confusion** between similar gates

### Final Week Study Strategy
1. **Practice number conversions** daily
2. **Draw flowcharts** for simple problems  
3. **Memorize truth tables** for basic gates
4. **Write pseudocode** for standard algorithms
5. **Solve previous year questions** under time pressure

---

**Success Formula**: Logical thinking + Step-by-step approach + Regular practice = Computational Thinking mastery!

Remember: Computational thinking is about breaking problems into smaller pieces and solving them systematically. Focus on understanding the logical flow rather than memorizing syntax. Practice with different problems to develop pattern recognition skills!

---

*Good luck with your IIT Madras BS Qualifier exam! With systematic practice and logical thinking, you'll excel in computational thinking! 💻*