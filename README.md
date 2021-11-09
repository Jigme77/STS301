# STS301
A course in introductory statistics

---
class: left, top

# Definition of terms 
----

--
### Statistics


Collect, analyze, summarize, interpret, and draw conclusions from the data
or actual numeric descriptions of sample data 

--
### Data
Any observations that you have collected or informatin gathered

--
### Population
The complete set of elements that are being studied or a particular group of interest

???
Population example: 
All males in the world.
All females in the world.
All children between 6 - 9 years of age.

--
### Samples


Some subset of a population or subset of population from which data is collected

--### Census
Collecting from every member of a population

---
class: left, top

# Definiton of terms
----
.panelset[
.panel[.panel-name[Parameter]
### Parameter
A characteristics of a population (*mnemonic*: P-P) or numerical description of a poulation characteristics.
#### Examples
 - Mean height of all males in the world
 - Mean IQ of all females in Bhutan
 - 75% of all kids ages between 6 - 9 play video games
]

.panel[.panel-name[Statistics]
### Statistics
A characteristics of a sample (*mnemonic*: S-S) or numerical description of sample characteristics

#### Examples
- of 100 female asked, 47% dislike chocolate.
]
]

---
class: left, top

## Branches of statistics

.panelset[
.panel[.panel-name[Descriptive statistics]
Gather, sort, and summarize data from samples.

#### Examples
- 65% of seniors in local high school applying to college plan to major in business
]

.panel[.panel-name[Inferential statistics]
It uses descriptive statistics (data) to estimate population parameters.

#### Examples
- Based on phone survey, 22% of all men don't like football
]

]

---
class: left

# Applying definitions in statistics
 
--
#### The height of every fourth bottle in assembly line. Sample or population?

--
.can-edit[
 - Type the answer here]

--
#### Ages of all USA presidents. Population or sample?

--
.can-edit[
- Type the answer here]

--
#### A researcher stops 100 people in a store to survey household income. Identify population and the sample.

--
.can-edit[
* Population: 
* Sample:
]

--
#### Average number of hours per week a sample of 10 year olds spends watching is 20 hours. What is it represent: parameter or statistics? 

--
.can-edit[
* Type your answer here
]

--
#### 87% of all patients in a hospital report having an alcohol problem. Is it a parameter or statistic?

--
.can-edit[
* Type your answer here
]


---
class: left, top

# Types of data
----
.panelset[
.panel[.panel-name[Categorical variable]
Also known as class variable, or qualitative variable or nominal variables

#### Examples
- Sex
- Genotype
- Eye color (blue vs brown vs other)
- Drug treatment ( aspirin vs ibuprofen)
- Province
- Survival (live or die)

]

.panel[.panel-name[Numerical Variable]
Also known as quantitative variable. It can be either discrete or continuous

#### Examples
- Height 
- Weight 
- Tail length
- Dose (microgram per ml)
- Longevity (number of years)

]

.panel[.panel-name[Discrete]
Can be counted (Indivisible units)

#### Examples
- Number of limbs
- Litter size
- Number of offspring
- Number of petals
]

.panel[.panel-name[Continuous]
Can be measured (Infinitely divisible units)

#### Examples
- Arm length
- Height
- Weight
- Age
- Temperature 
- Duration of time
]

.panel[.panel-name[Measurement Scale]
.pull-left[## Categorical variable

### Nominal scale
eg. species, sex, diet
* No ordering 

### Oridinal scale
eg. small/medium/large
* Rank order 
* Differences and ratio undefined or only approximate
]

.pull-right[
## Numerical variable

### Interval scale 
eg. Celsius temperature, Years BC
* Arbitrary zero point
* Differences defined, ratios undefined

### Ratio scale
eg. mass, length, abundance, duration

* Physically meaningful zero point
* Differences and ratios defined

]

]
]

---
class: top, left

# Experiment and observational studies
----
.left-column[
## Experiment
- Measures specific traits after applying a treatment

## Observational studies
- Measures specific traits but doesn't modify subjects

#### Strata: Homogeneous group

#### Cluster: Heterogeneous group
]

.right-column[
## Sampling
Random - each member in a population has equal chance of being in that sample.
1. Simple random sample: each group of size 'n' has equal chance of being in that sample.

2. Convenience sampling: use the results you get easily. Not random, not 

3. Systematic sampling: put a population in order and select "K th" member

3. Stratified random sampling: break population into sub-groups based on some characteristics, then take simple random sample of each subgroup.

4. Cluster sample: break population into 'cluster,' regardless of characteristics, randomly select certain number of clusters and then collect data from cluster
]

---
class: left, top

# Data presentation
----

## Frequency Distribution
Tables that divides data into groups (classes) and shows how many data values occur in each group.


.pull-left[#### Example: Prices of computer in a store
Class  | Frequency
------------- | -------------
0 - 199   | 0
200 - 399 | 5
400 - 599  | 7
600 - 799 | 6
800 - 999 | 2
1000 - 1999|0

class width = $ 200
]
.pull-right[#### Example: Ages when people get married

Class  | Frequency
------------- | -------------
15 - 18  | 2
19 - 22 | 5
23 - 26  | 4
27 - 30 | 5
31 - 34 | 4


class width = 4

class limits = 15, 18, 19, 22, 23, ...
]

---
class: top, left

# Frequency Distribution 
----

 
 .pull-left[.center[### Class boundaries
Value in-between adjacent class limits

 CB = \\(\frac{Upper \ class \ limit + Next \ lower \ class \ limit}{2}\\)
 
 #### Example: Age of people at car show
Class  | Frequency | Class boundaries
--------| ---------|----------
15 - 19  |   7   | 14.5 - 19.5
20 - 24  | 8     | 19.5 -24.5 
25 - 29  | 10    | 24.5 - 29.5
30 - 34  | 2     |29.5 - 34.5
35 - 39  | 3     |34.5 - 39.5


]]

.pull-right[.center[### Relative Frequency distribution
The \\(\%\\) of the data set that falls in a class.

R.F = \\(\frac{Class \ frequency}{\sum(frequencies)}\\)

#### Ages of people buying first car

Class  | Frequency | Relative frequency
--------| ---------|----------
15 - 18  |   2   | 6.45\\(\%\\)
19 - 22  | 7   | 22.58\\(\%\\)
23 - 26  | 4    | 12.90\\(\%\\)
27 - 30 | 15    |48.39\\(\%\\)
31 - 34  | 3     |9.68\\(\%\\)
        |\\(\sum=31\\)|
]]

---
class: left, top

# Frequency Distribution
----
## Cumulative frequency distribution
The sum of a frequency in a class and all previous classes.


#### Example. Ages when getting first job
.center[
Class  | Frequency | Cumulative frequency
--------| ---------|----------
15 - 19  |  12   | 12
20 - 24  | 8      | 20
25 - 29  | 15   | 35
30 - 34 | 12    | 47
35 - 39  | 9     |56
]

What is the frequency of people who got their first job at less than 30 years of age? 

---
class: left, top

# Pie charts, bar graph, and pareto charts
----

.panelset[
.panel[.panel-name[Pie chart]
.pull-left[<img src="img/pie.png" width="400">]


.pull-right[To find the wedges:
- \\(Orange = 0.1 * 360 = 36^{\circ}\\)

- \\(Green = 0.3 * 360 = 108^{\circ}\\)

- \\(Red = 0.6 * 360 = 216^{\circ}\\) 
]

]

.panel[.panel-name[Bar graph]

```{r, echo=FALSE, fig.width=6, fig.length = 4, fig.show='asis'}
ggplot(chickwts, aes(feed)) +
         geom_bar()
```
]

.panel[.panel-name[Pareto chart]
Bar graph in descending order

```{r, echo=FALSE, fig.show='asis'}
ggplot(chickwts, aes(feed)) +
         geom_bar()
```
]


]

---
class: top, left

Histogram
----
Bar chart of frequency distribution
.pull-left[
```{r faithful, fig.height=4, fig.length=5, fig.show='hide'}
hist(faithful$waiting, 
     main = "Waiting Time between Eruptions", 
     xlab = "Waiting Time (in minutes)")
```
]

.pull-right[
```{r, ref.label='faithful', echo=FALSE}
```

]
---
class: left, top

# Stem and leaf plot
----
```{r, fig.show='asis'}
head(rivers, 6)
stem(rivers, scale = 0.5)
```


---
class: left, top
# Introduction to R
----


.pull-left[
[R installation can be done from here](https://cran.r-project.org/)

### It is like a giant calculator
```{r basic-calc, echo=TRUE}
2 + 2 # Addition
2 - 4 # Subtraction
3 * 2 # Multiplication
```

]

.pull-right[
## Why use R?
### Advantages of R
- Free and open source
- High quality plots
- Reproducible reports 
- Continuously growing
- Many packages

### Disadvantages 
- Complicated language
- Spread across various packages
- Inefficient memory allocation
]

---
class: center, left
# Histogram 
----
.pull-left[
```{r first-plot, fig.height=5, echo=FALSE}
hist(mpg$hwy, 
     xlab = "Highway mileage", 
     ylab = "Number of cars", 
     main = "Histogram of mileage on Highway for different models of car")
```
]

.pull-right[
```{r, ref.label = 'first-plot', echo=TRUE, fig.show ='hide'}
```
]

## "Can use minimal codes to produce publication quality charts."
