# Hubble and Baker Simulation in Python

### The Problem:
In this assignment for the Simulation course, we want to simulate an Autorastaurant 1000 times (1000 customers), we have two servicers named "Hubble" and "Baker", Hubble is better at work and much faster, so when a customer comes in the place, if Hubble is not busy, the customer goes to the Hubble to get the service.

### Distribution of Hubble service time:
| Time of Service | Probability | Cumulative Probability | Allocation of random numbers |
| --------------- | ----------- | ---------------------- | ---------------------------- |
| 2               | 0.3         | 0.30                   | 01-30                        |
| 3               | 0.28        | 0.58                   | 31-58                        |
| 4               | 0.25        | 0.83                   | 59-83                        |
| 5               | 0.17        | 1.00                   | 84-100                       |

### Distribution of Baker service time:
| Time of Service | Probability | Cumulative Probability | Allocation of random numbers |
| --------------- | ----------- | ---------------------- | ---------------------------- |
| 3               | 0.35        | 0.35                   | 01-35                        |
| 4               | 0.25        | 0.60                   | 36-60                        |
| 5               | 0.20        | 0.80                   | 61-80                        |
| 6               | 0.20        | 1.00                   | 81-100                       |

### Distribution Inter-arrival times of customers:
| Interarrival time | Probability | Cumulative Probability | Allocation of random numbers |
| ----------------- | ----------- | ---------------------- | ---------------------------- |
| 1                 | 0.25        | 0.25                   | 01-25                        |
| 2                 | 0.40        | 0.65                   | 26-65                        |
| 3                 | 0.20        | 0.85                   | 66-85                        |
| 4                 | 0.15        | 1.00                   | 86-100                       |
