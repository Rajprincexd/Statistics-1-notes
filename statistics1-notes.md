# Statistics 1 - Complete Study Notes for IIT Madras BS Degree Qualifier

**Duration: 4 Weeks | Target: Anyone with zero statistics background | Goal: Master qualifier concepts**

---

## Table of Contents

1. [Week 1: Introduction to Statistics and Data Types](#week-1)
2. [Week 2: Descriptive Statistics and Data Visualization](#week-2)
3. [Week 3: Probability Fundamentals](#week-3)
4. [Week 4: Probability Distributions](#week-4)
5. [Practice Questions and PYQs](#practice-questions)
6. [Quick Revision Guide](#quick-revision)

---

## Week 1: Introduction to Statistics and Data Types

### 1.1 What is Statistics?

**Definition:** Statistics is the science of collecting, organizing, analyzing, interpreting, and presenting data to make informed decisions.

Think of statistics as a toolkit for understanding the world through numbers. Just like a detective uses clues to solve cases, statisticians use data to uncover patterns and make predictions.

#### Why is Statistics Important?
- **Business**: Market research, sales forecasting, quality control
- **Medicine**: Clinical trials, disease patterns, treatment effectiveness  
- **Sports**: Player performance, game strategy, predictions
- **Education**: Student performance analysis, curriculum effectiveness
- **Daily Life**: Weather forecasts, opinion polls, product reviews

### 1.2 Types of Statistics

#### 1. Descriptive Statistics
**Purpose**: Summarize and describe data that you have collected

**Example**: In a class of 30 students:
- Average height = 5.6 feet
- Most common age = 20 years
- Score range = 45 to 95 marks

**Key Tools**:
- Measures of central tendency (mean, median, mode)
- Measures of spread (range, standard deviation)
- Charts and graphs

#### 2. Inferential Statistics
**Purpose**: Make predictions or conclusions about a population based on sample data

**Example**: 
- Surveying 1000 people to predict election results for entire country
- Testing 100 light bulbs to determine quality of entire production batch
- Studying 500 patients to evaluate effectiveness of new medicine

**Key Tools**:
- Hypothesis testing
- Confidence intervals
- Probability distributions

### 1.3 Population vs Sample

#### Population
**Definition**: The entire group that you want to study

**Examples**:
- All students in IIT Madras
- All smartphones sold in India in 2024
- All voters in Maharashtra

**Symbol**: N (for population size)

#### Sample
**Definition**: A subset of the population that you actually study

**Examples**:
- 500 students randomly selected from IIT Madras
- 1000 smartphones randomly selected for quality testing
- 2000 voters surveyed before election

**Symbol**: n (for sample size)

#### Why Use Samples?
1. **Cost-effective**: Cheaper than studying entire population
2. **Time-saving**: Faster to collect and analyze
3. **Practical**: Sometimes impossible to study entire population
4. **Accurate**: Well-chosen samples can represent population well

**Example Scenario**:
*Question*: What is the average height of Indian college students?
- **Population**: All college students in India (millions of students)
- **Sample**: 5,000 randomly selected college students from different states
- **Process**: Measure height of sample, calculate average, estimate population average

### 1.4 Types of Data

Understanding data types is crucial because different types require different statistical methods.

#### 1. Categorical Data (Qualitative)
**Definition**: Data that represents categories or groups

#### 1a. Nominal Data
**Characteristic**: Categories with no inherent order

**Examples**:
- Gender: Male, Female, Other
- Colors: Red, Blue, Green, Yellow  
- Brands: Apple, Samsung, OnePlus
- Blood type: A, B, AB, O

**Statistical Operations**: Count, Mode, Percentages
**Cannot do**: Calculate average (What's the average of Red and Blue?)

#### 1b. Ordinal Data  
**Characteristic**: Categories with meaningful order

**Examples**:
- Education level: Primary, Secondary, Graduate, Post-graduate
- Satisfaction rating: Very Dissatisfied, Dissatisfied, Neutral, Satisfied, Very Satisfied
- Movie ratings: 1 star, 2 stars, 3 stars, 4 stars, 5 stars
- Income groups: Low, Middle, High

**Statistical Operations**: Count, Mode, Median, Percentages
**Cannot do**: Calculate exact average (difference between categories unknown)

#### 2. Numerical Data (Quantitative)
**Definition**: Data that represents measurable quantities

#### 2a. Discrete Data
**Characteristic**: Countable values, usually whole numbers

**Examples**:
- Number of students in a class: 25, 30, 35
- Number of cars in parking lot: 0, 1, 2, 3...
- Number of goals scored: 0, 1, 2, 3, 4...
- Number of children in family: 0, 1, 2, 3, 4...

**Key Point**: You can list all possible values

#### 2b. Continuous Data
**Characteristic**: Measurable values that can take any value in a range

**Examples**:
- Height: 5.6 feet, 5.65 feet, 5.657 feet...
- Weight: 60.5 kg, 70.25 kg, 65.789 kg...
- Temperature: 25.3°C, 30.75°C, 28.456°C...
- Time: 2.5 hours, 3.75 minutes, 10.234 seconds...

**Key Point**: Infinite possible values between any two measurements

### 1.5 Data Collection Methods

#### 1. Primary Data Collection
**Definition**: Data collected directly by the researcher

**Methods**:
- **Surveys/Questionnaires**: Asking people questions
- **Interviews**: Face-to-face conversations
- **Observations**: Watching and recording behavior
- **Experiments**: Controlled studies to test hypotheses

**Advantages**: 
- Specific to your research needs
- Current and relevant
- Higher accuracy

**Disadvantages**:
- Time-consuming
- Expensive
- Requires expertise

#### 2. Secondary Data Collection
**Definition**: Data collected by someone else and used by researcher

**Sources**:
- Government databases (Census, Economic surveys)
- Research papers and journals
- Company reports
- Online databases

**Advantages**:
- Quick and inexpensive
- Large datasets available
- Historical data accessible

**Disadvantages**:
- May not fit exact research needs
- Possibly outdated
- Unknown data quality

### 1.6 Scales of Measurement

Understanding measurement scales helps choose appropriate statistical methods.

#### 1. Nominal Scale
- **Categories only, no order**
- Examples: Gender, Religion, Nationality
- **Operations**: Counting, Finding mode
- **Cannot**: Rank, calculate average

#### 2. Ordinal Scale  
- **Categories with order, but unequal intervals**
- Examples: Grades (A, B, C, D), Rankings (1st, 2nd, 3rd)
- **Operations**: Counting, Mode, Median, Ranking
- **Cannot**: Calculate meaningful average

#### 3. Interval Scale
- **Ordered with equal intervals, but no true zero**
- Examples: Temperature in Celsius (0°C doesn't mean no temperature)
- **Operations**: All above + Mean, Addition, Subtraction
- **Cannot**: Meaningful multiplication/division

#### 4. Ratio Scale
- **Ordered with equal intervals and true zero point**
- Examples: Height, Weight, Income, Age
- **Operations**: All statistical operations possible
- **Can**: Multiply, divide, find ratios

**Memory Tip**: **N**ominal = **N**ames, **O**rdinal = **O**rder, **I**nterval = **I**ntervals, **R**atio = **R**atios

### 1.7 Basic Statistical Concepts

#### Variable
**Definition**: A characteristic that can take different values

**Examples**:
- Student's test score (can be 0, 50, 85, 95...)
- Person's height (can be 5.2 ft, 6.1 ft, 5.8 ft...)
- Car color (can be red, blue, white, black...)

#### Observation  
**Definition**: A single measurement or data point

**Example**: 
If we measure heights of 5 students: 5.6, 5.8, 5.4, 6.0, 5.9
Each height measurement is one observation.

#### Dataset
**Definition**: Collection of all observations

**Example**:
```
Student | Height | Weight | Grade
--------|--------|--------|-------
John    | 5.8    | 70     | A
Mary    | 5.4    | 55     | B  
Sam     | 6.0    | 80     | A
Lisa    | 5.6    | 65     | C
```

This is a dataset with 4 observations and 4 variables.

---

## Week 2: Descriptive Statistics and Data Visualization

### 2.1 Frequency Distributions

#### What is Frequency Distribution?
**Definition**: A table that shows how often each value occurs in a dataset.

**Simple Example**:
Grades of 20 students: A, B, A, C, B, A, A, B, C, A, B, A, C, B, A, B, A, C, B, A

**Frequency Table**:
| Grade | Frequency | Percentage |
|-------|-----------|------------|
| A     | 10        | 50%        |
| B     | 7         | 35%        |
| C     | 3         | 15%        |
| **Total** | **20** | **100%** |

#### For Continuous Data: Grouped Frequency Distribution

**Example**: Heights of 30 students (in feet)
5.2, 5.4, 5.6, 5.8, 6.0, 5.3, 5.7, 5.9, 5.5, 5.8...

**Grouped Frequency Table**:
| Height Range | Frequency | Percentage |
|--------------|-----------|------------|
| 5.0 - 5.3    | 6         | 20%        |
| 5.4 - 5.7    | 12        | 40%        |
| 5.8 - 6.1    | 8         | 27%        |
| 6.2 - 6.5    | 4         | 13%        |
| **Total**    | **30**    | **100%**   |

#### Constructing Grouped Frequency Distribution

**Steps**:
1. **Find Range**: Maximum value - Minimum value
2. **Decide number of groups**: Usually 5-10 groups
3. **Calculate class width**: Range ÷ Number of groups
4. **Create intervals**: Start from minimum, add class width
5. **Count frequencies**: How many observations in each interval

**Practice Example**:
Test scores: 45, 52, 67, 73, 81, 56, 78, 65, 59, 71, 48, 63, 77, 69, 55

**Solution**:
1. Range = 81 - 45 = 36
2. Number of groups = 6
3. Class width = 36 ÷ 6 = 6
4. Intervals: 45-50, 51-56, 57-62, 63-68, 69-74, 75-81
5. Count frequencies

### 2.2 Measures of Central Tendency

Central tendency tells us about the "typical" or "central" value in a dataset.

#### 1. Mean (Average)

**Definition**: Sum of all values divided by number of values

**Formula**: Mean = (Sum of all values) ÷ (Number of values)

**Symbol**: x̄ (for sample), μ (for population)

**Example 1**: Test scores of 5 students: 70, 80, 85, 75, 90
Mean = (70 + 80 + 85 + 75 + 90) ÷ 5 = 400 ÷ 5 = 80

**When to use**:
- With numerical data
- When distribution is not heavily skewed
- When you want to consider all values

**Limitations**:
- Affected by extreme values (outliers)
- Cannot be used with nominal data

**Example with Outlier**:
Salaries: $30,000, $35,000, $40,000, $38,000, $500,000
Mean = $128,600 (not representative of typical salary!)

#### 2. Median

**Definition**: The middle value when data is arranged in order

**Steps to find median**:
1. Arrange data in ascending order
2. If odd number of values: median = middle value
3. If even number of values: median = average of two middle values

**Example 1** (odd number): 23, 34, 45, 56, 67
Median = 45 (middle value)

**Example 2** (even number): 23, 34, 45, 56, 67, 78
Median = (45 + 56) ÷ 2 = 50.5

**When to use**:
- With skewed data
- With ordinal data
- When outliers are present

**Advantages**:
- Not affected by extreme values
- Easy to understand and calculate

#### 3. Mode

**Definition**: The value that appears most frequently in the dataset

**Example 1**: 2, 3, 4, 4, 4, 5, 6, 7
Mode = 4 (appears 3 times)

**Example 2**: Red, Blue, Red, Green, Red, Blue, Yellow
Mode = Red (appears 3 times)

**Types of Mode**:
- **Unimodal**: One mode (most common)
- **Bimodal**: Two modes
- **Multimodal**: More than two modes
- **No mode**: All values appear equally often

**When to use**:
- With categorical data
- To find most common value
- With any type of data

### 2.3 Measures of Spread (Variability)

Measures of spread tell us how scattered or spread out the data points are.

#### 1. Range

**Definition**: Difference between maximum and minimum values

**Formula**: Range = Maximum value - Minimum value

**Example**: Test scores: 45, 67, 72, 81, 89
Range = 89 - 45 = 44

**Advantages**:
- Easy to calculate and understand
- Gives quick idea of spread

**Disadvantages**:
- Only considers two extreme values
- Affected by outliers
- Doesn't consider distribution of middle values

#### 2. Variance

**Definition**: Average of squared differences from the mean

**Why square the differences?**
- Negative and positive differences would cancel out
- Squaring makes all values positive
- Gives more weight to larger deviations

**Sample Variance Formula**:
s² = Σ(x - x̄)² ÷ (n - 1)

Where:
- s² = sample variance
- x = individual values
- x̄ = sample mean
- n = number of values

**Step-by-step calculation**:

**Example**: Heights: 5.6, 5.8, 5.4, 6.0, 5.7

**Step 1**: Calculate mean
Mean = (5.6 + 5.8 + 5.4 + 6.0 + 5.7) ÷ 5 = 28.5 ÷ 5 = 5.7

**Step 2**: Calculate differences from mean
| Value | Difference (x - x̄) |
|-------|-------------------|
| 5.6   | -0.1              |
| 5.8   | 0.1               |  
| 5.4   | -0.3              |
| 6.0   | 0.3               |
| 5.7   | 0.0               |

**Step 3**: Square the differences
| Value | (x - x̄)² |
|-------|-----------|
| 5.6   | 0.01      |
| 5.8   | 0.01      |
| 5.4   | 0.09      |
| 6.0   | 0.09      |
| 5.7   | 0.00      |

**Step 4**: Sum squared differences and divide by (n-1)
Variance = (0.01 + 0.01 + 0.09 + 0.09 + 0.00) ÷ (5-1) = 0.20 ÷ 4 = 0.05

#### 3. Standard Deviation

**Definition**: Square root of variance

**Formula**: s = √(variance)

**Using previous example**: 
Standard deviation = √0.05 = 0.224 feet

**Why use standard deviation instead of variance?**
- Same units as original data
- Easier to interpret
- More intuitive understanding of spread

**Interpretation**:
- Small standard deviation = data points close to mean
- Large standard deviation = data points spread out from mean

**Example comparison**:
- **Class A scores**: Mean = 75, SD = 5 (scores between 70-80)
- **Class B scores**: Mean = 75, SD = 15 (scores between 60-90)

Class A has more consistent performance.

### 2.4 Data Visualization

#### Why Visualize Data?
1. **Quick understanding**: Pictures are easier to understand than tables
2. **Pattern identification**: Trends and relationships become obvious
3. **Outlier detection**: Unusual values stand out
4. **Communication**: Easier to explain to others

#### 1. Bar Charts

**Use for**: Categorical data (nominal and ordinal)

**Example**: Student enrollment by department
```
Department    | Students
Computer Sci  | 150
Mechanical    | 120
Electrical    | 100
Civil         | 80
Chemical      | 60
```

**Vertical Bar Chart**: Categories on x-axis, frequencies on y-axis
**Horizontal Bar Chart**: Categories on y-axis, frequencies on x-axis

**When to use horizontal**:
- Long category names
- Many categories
- Better readability

#### 2. Histograms  

**Use for**: Continuous numerical data (grouped)

**Difference from Bar Chart**:
- Bars touch each other (continuous data)
- Shows distribution shape
- X-axis shows ranges, not categories

**Example**: Student test scores
```
Score Range | Frequency
40-50       | 5
51-60       | 12
61-70       | 25
71-80       | 18
81-90       | 8
91-100      | 2
```

**Histogram interpretation**:
- **Shape**: Normal, skewed, uniform
- **Center**: Where most data is located
- **Spread**: How scattered the data is

#### 3. Pie Charts

**Use for**: Parts of a whole (categorical data)

**Best practices**:
- Use for 5 or fewer categories
- Start largest slice at 12 o'clock
- Use different colors
- Include percentages

**Example**: Time spent on daily activities
- Sleep: 33% (8 hours)
- Work/Study: 33% (8 hours)  
- Meals: 12% (3 hours)
- Exercise: 8% (2 hours)
- Entertainment: 14% (3 hours)

**When NOT to use**:
- Too many categories (hard to read)
- Similar-sized categories (hard to distinguish)
- When exact values are important

#### 4. Box Plots (Box-and-Whisker Plots)

**Use for**: Showing distribution summary and outliers

**Components**:
- **Box**: Shows middle 50% of data (IQR)
- **Median line**: Middle of the box
- **Whiskers**: Extend to show range (within 1.5 × IQR)
- **Outliers**: Points beyond whiskers

**Five-number summary**:
1. Minimum (excluding outliers)
2. Q1 (25th percentile)
3. Median (50th percentile)  
4. Q3 (75th percentile)
5. Maximum (excluding outliers)

**Example interpretation**:
```
Test Scores Box Plot:
|---[====|====]---|  (outliers: 25, 95)
0   40   60  80   100

- Q1 = 50, Median = 65, Q3 = 75
- Most students scored between 50-75
- Few very low (25) and very high (95) scores
```

#### 5. Scatter Plots

**Use for**: Relationship between two numerical variables

**Example**: Height vs Weight of students
- X-axis: Height
- Y-axis: Weight  
- Each point represents one student

**Patterns to look for**:
- **Positive correlation**: As one increases, other increases
- **Negative correlation**: As one increases, other decreases
- **No correlation**: No clear pattern
- **Outliers**: Points far from the pattern

---

## Week 3: Probability Fundamentals

### 3.1 Introduction to Probability

#### What is Probability?
**Definition**: The likelihood or chance that an event will occur

**Real-life examples**:
- Chance of rain tomorrow = 70%
- Probability of getting heads when flipping a coin = 50%
- Chance of winning a lottery = 0.000001%

#### Why Study Probability?
- **Decision making**: Should I carry an umbrella?
- **Risk assessment**: Is this investment safe?
- **Quality control**: What percentage of products are defective?
- **Medical diagnosis**: How likely is this disease?

#### Probability Scale
**Range**: 0 to 1 (or 0% to 100%)

- **0 (0%)**: Impossible event (Sun rising in the west)
- **0.5 (50%)**: Equally likely (Coin flip result)
- **1 (100%)**: Certain event (Sun rising in the east)

### 3.2 Basic Probability Concepts

#### Random Experiment
**Definition**: An activity whose outcome cannot be predicted with certainty

**Examples**:
- Flipping a coin
- Rolling a dice
- Drawing a card from a deck
- Selecting a student randomly from class

**Key characteristics**:
- Multiple possible outcomes
- Cannot predict exact outcome
- Can repeat under same conditions

#### Sample Space (S)
**Definition**: Set of all possible outcomes of a random experiment

**Examples**:
- **Coin flip**: S = {Heads, Tails}
- **Single die roll**: S = {1, 2, 3, 4, 5, 6}
- **Two coins**: S = {HH, HT, TH, TT}
- **Drawing a card suit**: S = {Hearts, Diamonds, Clubs, Spades}

#### Event (E)
**Definition**: A subset of the sample space

**Examples** (for single die roll):
- Event A: Getting an even number = {2, 4, 6}
- Event B: Getting a number greater than 4 = {5, 6}
- Event C: Getting a 3 = {3}

**Types of events**:
- **Simple event**: Contains exactly one outcome
- **Compound event**: Contains more than one outcome

### 3.3 Classical (Theoretical) Probability

**Definition**: Probability based on logical analysis

**Formula**: 
P(Event) = (Number of favorable outcomes) ÷ (Total number of possible outcomes)

#### Assumptions:
1. All outcomes are equally likely
2. Finite number of outcomes

#### Examples:

**Example 1**: Single die roll
Find P(getting a 4)
- Favorable outcomes = 1 (only one way to get 4)
- Total outcomes = 6
- P(getting 4) = 1/6 = 0.167 = 16.7%

**Example 2**: Drawing a card
Find P(getting a red card) from standard deck
- Favorable outcomes = 26 (13 hearts + 13 diamonds)  
- Total outcomes = 52
- P(red card) = 26/52 = 1/2 = 0.5 = 50%

**Example 3**: Two coin flips
Find P(getting exactly one head)
- Sample space = {HH, HT, TH, TT}
- Favorable outcomes = 2 (HT, TH)
- Total outcomes = 4
- P(exactly one head) = 2/4 = 1/2 = 50%

### 3.4 Properties of Probability

#### Property 1: Range
For any event A: 0 ≤ P(A) ≤ 1

#### Property 2: Certain Event
P(Sample Space) = P(S) = 1

**Example**: P(getting 1, 2, 3, 4, 5, or 6 on die roll) = 6/6 = 1

#### Property 3: Impossible Event
P(Empty Set) = P(∅) = 0

**Example**: P(getting 7 on a standard die) = 0/6 = 0

#### Property 4: Complement
P(A') = 1 - P(A)

Where A' is the complement of event A (all outcomes NOT in A)

**Example**: If P(rain tomorrow) = 0.3, then P(no rain tomorrow) = 1 - 0.3 = 0.7

#### Property 5: Addition Rule for Mutually Exclusive Events
If events A and B cannot occur together: P(A or B) = P(A) + P(B)

**Example**: Rolling a die
P(getting 2 or 5) = P(getting 2) + P(getting 5) = 1/6 + 1/6 = 2/6 = 1/3

### 3.5 Types of Events

#### 1. Mutually Exclusive (Disjoint) Events
**Definition**: Events that cannot occur at the same time

**Examples**:
- Getting heads OR tails in single coin flip
- Being absent OR present in class
- Getting A OR B grade (assuming no A+ grade exists)

**Key property**: P(A and B) = 0

#### 2. Independent Events
**Definition**: The outcome of one event does not affect the probability of another event

**Examples**:
- Results of two separate coin flips
- Drawing cards WITH replacement
- Weather on different days (approximately)

**Key property**: P(A and B) = P(A) × P(B)

#### 3. Dependent Events  
**Definition**: The outcome of one event affects the probability of another event

**Examples**:
- Drawing cards WITHOUT replacement
- Choosing students without putting names back
- Traffic lights (if one is red, next might be more likely green)

### 3.6 Conditional Probability

#### Definition
**Conditional Probability**: Probability of event A given that event B has already occurred

**Notation**: P(A|B) read as "probability of A given B"

**Formula**: P(A|B) = P(A and B) ÷ P(B), provided P(B) > 0

#### Example: Card Drawing
A standard deck has 52 cards. A card is drawn.
- Event A: Card is a King
- Event B: Card is a face card (Jack, Queen, King)

Find P(A|B) = Probability card is King, given it's a face card

**Solution**:
- Face cards in deck = 12 (4 Jacks + 4 Queens + 4 Kings)
- Kings among face cards = 4
- P(A|B) = 4/12 = 1/3 = 33.3%

**Interpretation**: If we know the card is a face card, there's a 1/3 chance it's a King.

#### Tree Diagrams for Conditional Probability

**Example**: Bag contains 3 red balls and 2 blue balls. Draw 2 balls without replacement.

```
First Draw    Second Draw    Probability
   3/5 Red -----> 2/4 Red     (3/5) × (2/4) = 6/20 = 3/10
            \---> 2/4 Blue    (3/5) × (2/4) = 6/20 = 3/10

   2/5 Blue ----> 3/4 Red     (2/5) × (3/4) = 6/20 = 3/10  
            \---> 1/4 Blue    (2/5) × (1/4) = 2/20 = 1/10
```

**Verification**: 3/10 + 3/10 + 3/10 + 1/10 = 10/10 = 1 ✓

### 3.7 Bayes' Theorem (Basic)

#### Introduction
**Purpose**: Update probability based on new evidence

**Real-world application**: Medical diagnosis
- Initial probability of having disease (before test)
- Updated probability after positive test result

#### Simple Form
If we have two events A and B:
P(A|B) = [P(B|A) × P(A)] ÷ P(B)

#### Example: Medical Test
- Disease affects 1% of population: P(Disease) = 0.01
- Test accuracy: 95% (detects disease correctly 95% of time)
- False positive rate: 5% (test positive when no disease)

**Question**: If test is positive, what's probability of having disease?

**Solution using Bayes' theorem**:
Let D = having disease, T = positive test

P(D|T) = [P(T|D) × P(D)] ÷ P(T)

Where:
- P(T|D) = 0.95 (test positive given disease)
- P(D) = 0.01 (disease prevalence)  
- P(T) = P(T|D) × P(D) + P(T|D') × P(D')
- P(T) = 0.95 × 0.01 + 0.05 × 0.99 = 0.0095 + 0.0495 = 0.059

Therefore: P(D|T) = (0.95 × 0.01) ÷ 0.059 = 0.0095 ÷ 0.059 ≈ 0.16

**Interpretation**: Even with positive test, only 16% chance of having disease!

This surprising result shows importance of considering base rates.

---

## Week 4: Probability Distributions

### 4.1 Introduction to Probability Distributions

#### What is a Probability Distribution?
**Definition**: A function that describes the probability of different outcomes in an experiment

Think of it as a complete description of how likely each possible outcome is.

**Example**: Rolling a fair die
- Outcome 1: Probability = 1/6
- Outcome 2: Probability = 1/6
- Outcome 3: Probability = 1/6
- Outcome 4: Probability = 1/6
- Outcome 5: Probability = 1/6
- Outcome 6: Probability = 1/6

This is a probability distribution!

#### Types of Probability Distributions

**1. Discrete Probability Distributions**
- For countable outcomes
- Examples: Number of heads in coin flips, number of defective items

**2. Continuous Probability Distributions**  
- For measurable outcomes with infinite possibilities
- Examples: Height, weight, temperature

### 4.2 Discrete Probability Distributions

#### 1. Binomial Distribution

**Definition**: Probability distribution for the number of successes in a fixed number of independent trials, where each trial has the same probability of success

**Real-world examples**:
- Number of heads in 10 coin flips
- Number of students passing in a class of 30
- Number of defective items in a batch of 100

**Requirements (Binomial Conditions)**:
1. **Fixed number of trials** (n)
2. **Two possible outcomes** per trial (success/failure)
3. **Constant probability** of success (p)
4. **Independent trials**

**Notation**: X ~ Binomial(n, p)
- n = number of trials
- p = probability of success in each trial
- X = number of successes

#### Binomial Probability Formula
P(X = k) = C(n,k) × p^k × (1-p)^(n-k)

Where:
- C(n,k) = n! / (k! × (n-k)!) = number of ways to choose k items from n
- k = number of successes we want

#### Binomial Distribution Example

**Problem**: A multiple-choice quiz has 5 questions, each with 4 options. If a student guesses randomly, what's the probability of getting exactly 2 questions correct?

**Solution**:
- n = 5 (5 questions)
- p = 1/4 = 0.25 (probability of guessing correctly)
- k = 2 (want exactly 2 correct)

P(X = 2) = C(5,2) × (0.25)² × (0.75)³

Step 1: C(5,2) = 5! / (2! × 3!) = 120 / (2 × 6) = 10

Step 2: (0.25)² = 0.0625

Step 3: (0.75)³ = 0.421875

Step 4: P(X = 2) = 10 × 0.0625 × 0.421875 = 0.264

**Answer**: 26.4% chance of getting exactly 2 questions correct

#### Mean and Standard Deviation of Binomial Distribution
- **Mean**: μ = n × p
- **Standard Deviation**: σ = √(n × p × (1-p))

**For our example**:
- Mean = 5 × 0.25 = 1.25 questions correct on average
- Standard deviation = √(5 × 0.25 × 0.75) = √0.9375 ≈ 0.97

### 4.3 Continuous Probability Distributions

#### 1. Normal Distribution

**Definition**: A continuous probability distribution that is symmetric and bell-shaped

**Why is it important?**
- Many natural phenomena follow normal distribution
- Heights, weights, test scores, measurement errors
- Central Limit Theorem makes it fundamental to statistics
- Foundation for many statistical tests

#### Characteristics of Normal Distribution
1. **Bell-shaped curve**
2. **Symmetric** around the mean
3. **Mean = Median = Mode**
4. **Total area under curve = 1**
5. **Defined by two parameters**: Mean (μ) and Standard Deviation (σ)

#### Notation
X ~ Normal(μ, σ²) or X ~ N(μ, σ²)

#### The 68-95-99.7 Rule (Empirical Rule)
In a normal distribution:
- **68%** of data falls within 1 standard deviation of mean (μ ± 1σ)
- **95%** of data falls within 2 standard deviations of mean (μ ± 2σ)
- **99.7%** of data falls within 3 standard deviations of mean (μ ± 3σ)

#### Example: Student Heights
Suppose heights of male students are normally distributed with:
- Mean (μ) = 70 inches
- Standard deviation (σ) = 3 inches

**Using 68-95-99.7 Rule**:
- 68% of students have heights between 67 and 73 inches (70 ± 3)
- 95% of students have heights between 64 and 76 inches (70 ± 6)  
- 99.7% of students have heights between 61 and 79 inches (70 ± 9)

#### Standard Normal Distribution

**Definition**: Normal distribution with mean = 0 and standard deviation = 1

**Notation**: Z ~ N(0, 1)

#### Standardization (Z-score)
**Formula**: Z = (X - μ) / σ

**Purpose**: Convert any normal distribution to standard normal distribution

**Example**: From previous height example
If a student is 76 inches tall:
Z = (76 - 70) / 3 = 6 / 3 = 2

**Interpretation**: This student is 2 standard deviations above average height

#### Using Z-tables (Basic Concept)
Z-tables give us probabilities for standard normal distribution

**Example**: P(Z < 1.5) = 0.9332 = 93.32%

This means 93.32% of values in standard normal distribution are less than 1.5

### 4.4 Applications of Normal Distribution

#### Example 1: Test Scores
Test scores are normally distributed with mean = 75 and standard deviation = 10

**Question**: What percentage of students scored above 85?

**Solution**:
1. Standardize: Z = (85 - 75) / 10 = 1.0
2. From Z-table: P(Z < 1.0) = 0.8413
3. Therefore: P(Z > 1.0) = 1 - 0.8413 = 0.1587 = 15.87%

**Answer**: About 15.87% of students scored above 85

#### Example 2: Quality Control
Light bulbs have lifetimes normally distributed with mean = 1000 hours, standard deviation = 50 hours

**Question**: What's the probability a randomly selected bulb lasts between 950 and 1050 hours?

**Solution**:
1. Standardize both values:
   - Z₁ = (950 - 1000) / 50 = -1.0
   - Z₂ = (1050 - 1000) / 50 = 1.0

2. Find probabilities:
   - P(Z < -1.0) = 0.1587
   - P(Z < 1.0) = 0.8413

3. Calculate: P(-1.0 < Z < 1.0) = 0.8413 - 0.1587 = 0.6826 = 68.26%

**Answer**: About 68.26% of bulbs last between 950 and 1050 hours

This confirms our 68-95-99.7 rule (68% within 1 standard deviation)!

### 4.5 Choosing the Right Distribution

#### When to Use Binomial Distribution
✅ **Use Binomial when**:
- Fixed number of trials
- Each trial has two outcomes (success/failure)
- Probability of success is constant
- Trials are independent

**Examples**: Coin flips, pass/fail exams, defective/non-defective items

#### When to Use Normal Distribution  
✅ **Use Normal when**:
- Continuous data
- Data is approximately symmetric
- Bell-shaped distribution
- Large sample sizes (Central Limit Theorem)

**Examples**: Heights, weights, test scores, measurement errors

#### Quick Decision Guide
**Count of successes in fixed trials** → Binomial
**Measurements on continuous scale** → Normal
**Proportions with large sample** → Normal (approximately)
**Time until first success** → Geometric (not covered in detail)

---

## Practice Questions and PYQs

### Data Types Practice

**Q1**: Classify the following data types:
(a) Temperature in degrees Celsius
(b) Customer satisfaction ratings (Poor, Fair, Good, Excellent)  
(c) Number of cars in a parking lot
(d) Brand of smartphone (Apple, Samsung, OnePlus)

**Solution**:
(a) Continuous (Interval scale)
(b) Ordinal 
(c) Discrete
(d) Nominal

**Q2**: A survey asks: "How many hours do you study per day?" What type of data is this?
(a) Nominal (b) Ordinal (c) Discrete (d) Continuous

**Answer: (c) Discrete** - Countable values (0, 1, 2, 3... hours)

### Descriptive Statistics Practice

**Q3**: Find mean, median, and mode for: 12, 15, 18, 15, 20, 15, 25

**Solution**:
- **Mean**: (12 + 15 + 18 + 15 + 20 + 15 + 25) ÷ 7 = 120 ÷ 7 = 17.14
- **Median**: Arrange in order: 12, 15, 15, 15, 18, 20, 25 → Median = 15
- **Mode**: 15 (appears 3 times)

**Q4**: Calculate the range and standard deviation for: 10, 12, 14, 16, 18

**Solution**:
- **Range**: 18 - 10 = 8
- **Mean**: (10 + 12 + 14 + 16 + 18) ÷ 5 = 14
- **Variance**: [(10-14)² + (12-14)² + (14-14)² + (16-14)² + (18-14)²] ÷ (5-1)
- **Variance**: [16 + 4 + 0 + 4 + 16] ÷ 4 = 40 ÷ 4 = 10
- **Standard deviation**: √10 = 3.16

### Probability Practice

**Q5**: A bag contains 5 red balls and 3 blue balls. If one ball is drawn randomly, find:
(a) P(Red) (b) P(Blue) (c) P(Green)

**Solution**:
(a) P(Red) = 5/8 = 0.625
(b) P(Blue) = 3/8 = 0.375  
(c) P(Green) = 0/8 = 0 (no green balls)

**Q6**: Two dice are rolled. Find P(sum = 7).

**Solution**:
- Total outcomes = 6 × 6 = 36
- Favorable outcomes for sum = 7: (1,6), (2,5), (3,4), (4,3), (5,2), (6,1) = 6 ways
- P(sum = 7) = 6/36 = 1/6 = 0.167

### Probability Distribution Practice

**Q7**: A coin is flipped 4 times. Find the probability of getting exactly 2 heads.

**Solution** (Binomial Distribution):
- n = 4, p = 0.5, k = 2
- P(X = 2) = C(4,2) × (0.5)² × (0.5)²
- C(4,2) = 4!/(2! × 2!) = 6
- P(X = 2) = 6 × 0.25 × 0.25 = 0.375 = 37.5%

**Q8**: Test scores are normally distributed with mean = 80 and standard deviation = 10. What percentage scored above 90?

**Solution**:
- Z = (90 - 80) / 10 = 1.0
- From Z-table: P(Z < 1.0) = 0.8413
- P(Z > 1.0) = 1 - 0.8413 = 0.1587 = 15.87%

### Previous Year Questions

**PYQ 1 (2023)**: The median of 5, 8, 12, 15, 20 is:
(a) 8 (b) 12 (c) 15 (d) 10

**Answer: (b) 12** - Middle value when arranged in order

**PYQ 2 (2022)**: If P(A) = 0.3 and P(B) = 0.4, and A and B are mutually exclusive events, then P(A or B) is:
(a) 0.12 (b) 0.7 (c) 0.1 (d) 0.58

**Answer: (b) 0.7** - P(A or B) = P(A) + P(B) = 0.3 + 0.4 = 0.7

**PYQ 3 (2024)**: In a normal distribution, what percentage of data falls within one standard deviation of the mean?
(a) 50% (b) 68% (c) 95% (d) 99.7%

**Answer: (b) 68%** - From the 68-95-99.7 rule

---

## Quick Revision Guide

### Key Formulas

#### Descriptive Statistics
- **Mean**: x̄ = Σx / n
- **Variance**: s² = Σ(x - x̄)² / (n-1)  
- **Standard Deviation**: s = √(variance)

#### Probability
- **Basic**: P(A) = Favorable outcomes / Total outcomes
- **Complement**: P(A') = 1 - P(A)
- **Addition Rule (Mutually Exclusive)**: P(A or B) = P(A) + P(B)
- **Multiplication Rule (Independent)**: P(A and B) = P(A) × P(B)

#### Distributions
- **Binomial**: P(X = k) = C(n,k) × p^k × (1-p)^(n-k)
- **Z-score**: Z = (X - μ) / σ

### Data Types Summary
- **Nominal**: Categories, no order (colors, brands)
- **Ordinal**: Categories with order (ratings, grades)
- **Discrete**: Countable numbers (students, cars)
- **Continuous**: Measurable values (height, weight)

### Distribution Decision Tree
```
Is data discrete? 
├─ Yes: Fixed trials with success/failure? → Binomial
├─ No: Continuous and bell-shaped? → Normal
└─ Categorical? → Use frequencies and proportions
```

### Common Mistakes to Avoid
1. **Confusing discrete and continuous** data
2. **Using mean with ordinal** data
3. **Forgetting to check binomial conditions**
4. **Misinterpreting conditional probability**
5. **Not standardizing before using Z-table**

### Study Tips for Final Week
1. **Practice calculations** without calculator first
2. **Memorize key formulas** and when to use them
3. **Work through complete examples** step-by-step
4. **Focus on concept understanding**, not just memorization
5. **Time yourself** on practice problems

---

**Success Formula**: Understand concepts + Practice calculations + Apply to real examples = Statistics mastery!

Remember: Statistics is about making sense of data and uncertainty. Focus on understanding what each measure tells you about your data, and when to use different methods. The calculations are just tools to get meaningful insights!

---

*Good luck with your IIT Madras BS Qualifier exam! With systematic practice and conceptual understanding, you'll master statistics! 📊*