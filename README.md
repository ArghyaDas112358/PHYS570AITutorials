# PHYS570AITutorials

### Notes:

During the recitation, the function `f(x)` we used represented the **true underlying function**, which is a  deterministic mapping without any added noise. This is useful when comparing model predictions against ground truth in a controlled setting.

However, in real-world applications, we rarely have access to the true function. Instead, we observe noisy outputs `y = f(x) + ε`, where ε represents random noise. 

Therefore, when evaluating model performance experimentally, we typically compare predictions against the observed `y` values.
