# Shapley values

The code related to this subject can be found in `Shapley.ipynb` file.

We considered the problem of `Fair division of taxi fare`:
 - Multiple agents onboard on a taxi trip
 - The amount the agents have to pay is given by the distance to the last stop.

## Shapley values computation

The exact shapley values were computed for a considerably small problem size: n = {4, 5}. 

For bigger problem sizes, computing the exact shapley values with the proposed method, is computationally intractable due to the fact that 2 ^ n permutations of agents must be taken into consideration.

## Estimation of shapley values

Instead of processing 2 ^ n permutations, a smaller number of permutation are sampled and estimates of exact shapley values are produced.

Considering n = 100 agents, 10 experiments were conducted with different numbers of samples: [10, 50, 100, 500, 1000, 5000, 10000].

Arguably, for this problem size, by sampling more the 5000 permutations, the estimates stabilizes.


### 10 samples of permutations
![shapley_10_samples.png](readme_resources/shapley_10_samples.png)

### 50 samples of permutations
![shapley_50_samples.png](readme_resources/shapley_50_samples.png)

### 100 samples of permutations
![shapley_100_samples.png](readme_resources/shapley_100_samples.png)

### 500 samples of permutations
![shapley_500_samples.png](readme_resources/shapley_500_samples.png)

### 1000 samples of permutations
![shapley_1000_samples.png](readme_resources/shapley_1000_samples.png)

### 5000 samples of permutations
![shapley_5000_samples.png](readme_resources/shapley_5000_samples.png)

### 10000 samples of permutations
![shapley_10000_samples.png](readme_resources/shapley_10000_samples.png)


# Reinforcement Learning

The code related to this subject can be found in `ReinforcementLearning.ipynb` file.
