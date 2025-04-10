## Optimization Using Gradient Descent

**Core Idea:**

* Given a function $f(x)$ that we want to minimize.
* The gradient descent algorithm iteratively updates the parameters $x$ using the formula:
    $$x_{k+1} = x_k - \alpha \nabla f(x_k)$$
    where:
    * $x_k$ is the current point.
    * $\alpha$ is the learning rate (step size).
    * $\nabla f(x_k)$ is the gradient of $f$ at $x_k$.

**Adaptive Learning Rate:**

* Final learning rule:
    $$\alpha_k = \frac{\alpha_0}{1 + k}$$
    where $\alpha_0$ is the initial learning rate and $k$ is the iteration number.

----------------
# **1. Minimizing a Quadratic Function:**


## 1

* Function: $f(x) = x^2$
* Gradient: $\nabla f(x) = 2x$
* Hessian: $H(x) = 2$
* Observation: $f(x)$ is convex (since the second derivative is positive).
* Update rule for this specific function:
    $$x_{k+1} = x_k - \alpha (2x_k)$$

**Example Iterations:**

* **Iteration 1:**
    * Initial point: $x_0 = 5$
    * Learning rate: $\alpha = 0.1$
    * $x_1 = 5 - 0.1(2 \times 5) = 5 - 0.1(10) = 5 - 1 = 4$

* **Iteration 2:**
    * Current point: $x_1 = 4$
    * Learning rate: $\alpha = 0.1$
    * $x_2 = 4 - 0.1(2 \times 4) = 4 - 0.1(8) = 4 - 0.8 = 3.2$

**Observation:**

* Each step moves $x$ closer to the minimum at $x = 0$.

------------

## **Example 2: Minimizing another 1D Quadratic Function**

* **Function:** $f(x) = (x - 2)^2$
* **Goal:** Find the minimum value of this function. We know the minimum occurs at $x = 2$.
* **Gradient:** $\nabla f(x) = \frac{d}{dx} (x - 2)^2 = 2(x - 2)$

Let's perform a few iterations with an initial point $x_0 = -1$ and a learning rate $\alpha = 0.1$.

* **Iteration 1 ($k=0$):**
    * $x_0 = -1$
    * $\nabla f(x_0) = 2(-1 - 2) = 2(-3) = -6$
    * $x_1 = x_0 - \alpha \nabla f(x_0) = -1 - 0.1(-6) = -1 + 0.6 = -0.4$

* **Iteration 2 ($k=1$):**
    * $x_1 = -0.4$
    * $\nabla f(x_1) = 2(-0.4 - 2) = 2(-2.4) = -4.8$
    * $x_2 = x_1 - \alpha \nabla f(x_1) = -0.4 - 0.1(-4.8) = -0.4 + 0.48 = 0.08$

* **Iteration 3 ($k=2$):**
    * $x_2 = 0.08$
    * $\nabla f(x_2) = 2(0.08 - 2) = 2(-1.92) = -3.84$
    * $x_3 = x_2 - \alpha \nabla f(x_2) = 0.08 - 0.1(-3.84) = 0.08 + 0.384 = 0.464$

As we can see, the value of $x$ is iteratively moving closer to the true minimum at $x = 2$. The learning rate $\alpha$ controls the step size in each iteration.
-------------------

## **Example 3: Minimizing a 2D Quadratic Function**
<img width="404" alt="image" src="https://github.com/user-attachments/assets/4beedcb1-3c0d-4e61-9712-2dfe9aa3c93c" />

----------------
## 4
<img width="349" alt="image" src="https://github.com/user-attachments/assets/5b586677-5f18-45fa-adc6-9e6480a054c9" />
<img width="338" alt="image" src="https://github.com/user-attachments/assets/4978e14d-4dd4-4f7e-8bb3-86c50729f043" />
<img width="404" alt="image" src="https://github.com/user-attachments/assets/5bb8ca82-c06c-4824-9169-6bd7fd6d7c47" />
<img width="412" alt="image" src="https://github.com/user-attachments/assets/dd4a4181-a883-436d-b386-4303a98e95fd" />

----------------
## 5 not und
<img width="550" alt="image" src="https://github.com/user-attachments/assets/1ba90995-312a-4f8a-a871-51252598acaf" />

----------------
## 6 not und

<img width="505" alt="image" src="https://github.com/user-attachments/assets/6cb85d97-9cc2-4a35-861b-4b0be9006367" />
