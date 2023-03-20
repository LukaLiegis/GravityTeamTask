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
```python
The answer is:  12.4651257880026 km
```


## Question 2

## Question 3

## Question 4