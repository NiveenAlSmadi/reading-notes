# Random functions
1. Randint
 Generate random integers between two numbers.
```python
import random
print random.randint(0, 5)
```
This will output either 1, 2, 3, 4 or 5.
2. Random
Generate random floats between 0.0 - 1.0
```py
import random
random.random() 
```
3. Choice
Generate a random value from the sequence.
```py
random.choice( ['red', 'black', 'green'] ).
```
4. Shuffle
The shuffle function, shuffles the elements in list in place, so they are in a random order.
```py
from random import shuffle
x = [[i] for i in range(10)]
shuffle(x)
```
```
Output:
# print x  gives  [[9], [2], [7], [0], [4], [5], [3], [1], [8], [6]]
# of course your results will vary
```
5. Randrange
Generate a randomly selected element from range(start, stop, step)
```py
random.randrange(start, stop[, step])
import random
for i in range(3):
    print random.randrange(0, 101, 5)
```
# What is Risk Analysis in Software Testing and how to perform it?
Risk: The probability of any unwanted incident is defined as
In Software Testing:
Risk: analysis is the process of identifying the risks in applications or software that you built and prioritizing them to test.
## Possible risks that could be encounter?
1. Use of new hardware
2. Use of new technology
3. Use of new automation tool
4. The sequence of code
5. Availability of test resources for the application
## Risks that are unavoidable
1. The time that you allocated for testing
2. A defect leakage due to the complexity or size of the application
3. Urgency from the clients to deliver the project
4. Incomplete requirements
## Risk magnitude indicators
1. High.
2. Medium.
3. Low.
## Risk Identification
There are different sets of risks included in the risk identification process. Those are as follows:
1. Business Risks.
2. Testing Risks.
3. Premature Release Risk.
4. Software Risks
## The perspective of Risk Assessment
There are three perspectives of Risk Assessment:
1. Effect – To assess risk by Effect. In case you identify a condition, event or action and try to determine its impact.
2. Cause – To assess risk by Cause is opposite of by Effect. Initialize scanning the problem and reach to the point that could be the most probable reason behind that.
3. Likelihood – To assess risk by Likelihood is to say that there is a probability that a requirement won't be satisfied.
## How to perform Risk Analysis?
There are three steps:
1. Searching the risk
2. Analyzing the impact of each individual risk
3. Measures for the risk identified