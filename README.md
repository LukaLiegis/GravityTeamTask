# GravityTeamTask

## Question 1
To answer the first question I used the following python script to calculate the answer.
```python
distance = 1000
circumference = 40000
radius = circumference / (2 * np.pi)

theta = distance / radius

chord = 2 * radius * np.sin(theta / 2)

area = 0.5 * radius * radius * np.sin(theta)

height = 2 * (area / radius)

new_radius = (height / np.sin(theta)) * np.sin(np.pi/2 - theta)

new_theta = distance / new_radius

delta = new_theta - theta

answer = delta * radius
```
After this you get the following answer:
```
The answer is:  12.4651257880026 km
```

## Question 2
```python
def implied_probability(payout):
    return 1 / payout

print("The probability that team a wins is: ", implied_probability(1.2))
print("The probability that it is a draw is: ", implied_probability(19.2))
print("The probability that team b wins is: ", implied_probability(6.4))

total_implied_probability = implied_probability(1.2) + implied_probability(19.2) + implied_probability(6.4)
betting_profit_margin = total_implied_probability - 1
print("The profit margin is: ", betting_profit_margin)
```

The script gives the following answers:
```
The probability that team a wins is:  0.8333333333333334
The probability that it is a draw is:  0.052083333333333336
The probability that team b wins is:  0.15625
The profit margin is:  0.04166666666666674
```

## Question 3

## Question 4