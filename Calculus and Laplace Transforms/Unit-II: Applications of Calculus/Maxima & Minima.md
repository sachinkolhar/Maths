# **Conclusion: How to Find Local and Absolute Maxima & Minima**
<img width="397" alt="image" src="https://github.com/user-attachments/assets/ec16dc88-3aa0-4c7c-ada2-13bda2278cee" />
<img width="287" alt="image" src="https://github.com/user-attachments/assets/23fd7cce-8f9e-4749-8aba-a5859d5a355f" />

To determine **local and absolute extrema**, follow these key steps:

### **1. Find Critical Points**
- Compute the **first derivative** \( f'(x) \).
- Solve \( f'(x) = 0 \) or find where \( f'(x) \) is **undefined**.
- These values are the **critical points**, which are possible extrema.

### **2. Determine Local Extrema**
- Use the **Second Derivative Test**:
  - If \( f''(x) > 0 \), \( f(x) \) has a **local minimum** at \( x \).
  - If \( f''(x) < 0 \), \( f(x) \) has a **local maximum** at \( x \).
  - If \( f''(x) = 0 \), the test is inconclusive.
  
  **OR**
  
- Use the **First Derivative Test**:
  - If \( f'(x) \) changes from **positive to negative**, there is a **local maximum**.
  - If \( f'(x) \) changes from **negative to positive**, there is a **local minimum**.

### **3. Find Absolute Extrema**
- Check **critical points** (from Step 1).
- If the function is given on a **closed interval** \([a, b]\), also evaluate \( f(a) \) and \( f(b) \).
- Compare function values:
  - The **largest** function value is the **absolute maximum**.
  - The **smallest** function value is the **absolute minimum**.

### **4. Key Differences**
| Local Extrema | Absolute Extrema |
|--------------|----------------|
| Highest or lowest point **in a small region** | Highest or lowest value in the **entire domain** |
| Found using **first or second derivative tests** | Found by checking **critical points and endpoints** (if a closed interval) |
| May not be the highest or lowest overall | Always the highest or lowest function value |

### **Final Thought**
- **Local extrema** help understand function behavior **near critical points**.
- **Absolute extrema** are useful for **optimization problems** where we need the **highest or lowest possible value**.
  
--------------------------------------------------------------------------------------------------------------------------------

# **Example: Find Absolute Maximum and Minimum of**  
\[
f(x) = x^2 - 4x + 3
\]
on the **closed interval** \( [0, 3] \).



### **Step 1: Compute First Derivative**
\[
f'(x) = 2x - 4
\]

### **Step 2: Find Critical Points (Solve \( f'(x) = 0 \))**
\[
2x - 4 = 0
\]

\[
2x = 4
\]

\[
x = 2
\]

Since \( x = 2 \) is **inside** the given interval \( [0,3] \), it is a **critical point**.



### **Step 3: Evaluate Function at Critical Points and Endpoints**
Now, we find \( f(x) \) at:
- The critical point \( x = 2 \),
- The **endpoints** \( x = 0 \) and \( x = 3 \).

\[
f(0) = (0)^2 - 4(0) + 3 = 3
\]

\[
f(2) = (2)^2 - 4(2) + 3 = 4 - 8 + 3 = -1
\]

\[
f(3) = (3)^2 - 4(3) + 3 = 9 - 12 + 3 = 0
\]



### **Step 4: Identify Absolute Max and Min**
- The **absolute maximum** is the **highest** value:  
  - \( f(0) = 3 \), so the **absolute maximum is 3 at \( x = 0 \)**.
  
- The **absolute minimum** is the **lowest** value:  
  - \( f(2) = -1 \), so the **absolute minimum is -1 at \( x = 2 \)**.



### **Final Answer**
- **Absolute Maximum:** \( f(0) = 3 \) at \( x = 0 \).  
- **Absolute Minimum:** \( f(2) = -1 \) at \( x = 2 \).

Since the function is defined on a **closed interval**, we considered **both critical points and endpoints**, which is the key to finding absolute extrema.

-------------------------------------------------------------------------------------------------------
# **4. Example Problem: Find Local maxima and minima**
Find the local and absolute extrema of:

\[
f(x) = x^3 - 3x^2 + 4
\]

#### **Step 1: Compute First Derivative**
\[
f'(x) = 3x^2 - 6x
\]

#### **Step 2: Solve \( f'(x) = 0 \)**
\[
3x^2 - 6x = 0
\]

Factor:

\[
3x(x - 2) = 0
\]

So, \( x = 0 \) and \( x = 2 \) are **critical points**.

#### **Step 3: Compute Second Derivative**
\[
f''(x) = 6x - 6
\]

Evaluate at critical points:
- \( f''(0) = 6(0) - 6 = -6 \) (**Negative**, so \( x = 0 \) is a **local maximum**).
- \( f''(2) = 6(2) - 6 = 6 \) (**Positive**, so \( x = 2 \) is a **local minimum**).

#### **Step 4: Find Absolute Extrema**
- If the domain is **not specified**, check behavior at **infinity**:
  - Since \( x^3 \) dominates, \( f(x) \to \infty \) as \( x \to \infty \) and \( f(x) \to -\infty \) as \( x \to -\infty \).
  - This means **there is no absolute maximum or minimum** in an **unbounded domain**.

---

### **Final Answer**
- **Local Maximum**: \( f(0) = 4 \) at \( x = 0 \).
- **Local Minimum**: \( f(2) = 2 \) at \( x = 2 \).
- **No absolute maximum or minimum** if the domain is **all real numbers**.

---

### **Summary**
1. **Find the first derivative** and **solve \( f'(x) = 0 \)** for critical points.
2. **Use the second derivative test** (or first derivative test) to classify points as local maxima or minima.
3. **For absolute extrema**, check function values at critical points and endpoints.

---------------------
## A sheet of cardboard 3 ft. by 4 ft. will be made into a box by cutting equal-sized squares
from each corner and folding up the four edges. What will be the dimensions of the box
with largest volume ?

You start with a rectangular sheet of cardboard measuring 4 feet by 3 feet. The goal is to cut squares from each corner and fold up the sides to create an open-top box.

Step 1: Cutting the Corners
You cut equal-sized squares from each corner of the cardboard.
Let 
𝑥
x be the side length of each square.
This means you are removing a square of size 
𝑥
×
𝑥
x×x from all four corners.

<img width="311" alt="image" src="https://github.com/user-attachments/assets/4d5bc79d-9f0b-4c59-9bbc-909f535f3e81" />
<img width="292" alt="image" src="https://github.com/user-attachments/assets/4b6713d1-c71d-4af5-9e48-4c9ac544fa53" />
<img width="299" alt="image" src="https://github.com/user-attachments/assets/0797fde4-9b4b-4a88-8485-2cbad3bae06a" />
<img width="577" alt="image" src="https://github.com/user-attachments/assets/8322c968-02cc-4fd7-ab99-3b8e575d0bae" />

-----------------
## Find the point on the unit circle cent red at origin closed to the point (1, 1)?

Let's solve this problem step-by-step.

**1. Define the Problem:**

* **Unit Circle:** The equation of the unit circle centered at the origin is x² + y² = 1.
* **Point:** We are given the point (1, 1).
* **Goal:** Find the point (x, y) on the unit circle that is closest to (1, 1).

**2. Distance Formula:**

The distance between two points (x₁, y₁) and (x₂, y₂) is given by:

d = √((x₂ - x₁)² + (y₂ - y₁)²)

In our case, the distance between (x, y) on the unit circle and (1, 1) is:

d = √((x - 1)² + (y - 1)²)

**3. Minimize the Distance:**

To minimize the distance, we can minimize the square of the distance, which simplifies calculations:

d² = (x - 1)² + (y - 1)²

Since (x, y) is on the unit circle, we have x² + y² = 1. We can solve for y²:

y² = 1 - x²

and thus y = ±√(1 - x²).

Substitute y = ±√(1 - x²) into the squared distance equation:

d² = (x - 1)² + (±√(1 - x²) - 1)²

Let's work with y = √(1 - x²) for now (the case with y = -√(1 - x²) will lead to a farther point).

d² = (x - 1)² + (√(1 - x²) - 1)²

**4. Use Calculus to Minimize:**

To minimize d², we take the derivative with respect to x and set it to zero:

d² = x² - 2x + 1 + 1 - x² - 2√(1 - x²) + 1
d² = 3 - 2x - 2√(1 - x²)

Let's differentiate d² with respect to x:

d(d²)/dx = -2 - 2 * (1/2)(1 - x²)^(-1/2) * (-2x)
d(d²)/dx = -2 + 2x / √(1 - x²)

Set d(d²)/dx = 0:

-2 + 2x / √(1 - x²) = 0
2x / √(1 - x²) = 2
x / √(1 - x²) = 1
x = √(1 - x²)

Square both sides:

x² = 1 - x²
2x² = 1
x² = 1/2
x = ±√(1/2) = ±1/√2

Since we are looking for the point closest to (1, 1), we should consider x = 1/√2 (because it's positive and closer to 1).

Now, find y:

y = √(1 - x²) = √(1 - 1/2) = √(1/2) = 1/√2

So the point is (1/√2, 1/√2).

**5. Verify the Point:**

* **Unit Circle:** (1/√2)² + (1/√2)² = 1/2 + 1/2 = 1.
* **Distance:** The distance from (1/√2, 1/√2) to (1, 1) is:

d = √((1 - 1/√2)² + (1 - 1/√2)²)
d = √((1 - √2/2)² + (1 - √2/2)²)
d = √((1 - √2/2)² * 2)
d = √(2 * (1 - √2 + 1/2))
d = √(2 * (3/2 - √2))
d = √(3 - 2√2)

**Final Answer:**

The point on the unit circle closest to (1, 1) is **(1/√2, 1/√2)**, or **(√2/2, √2/2)**.

---------------------
## A rectangle is to be inscribed in a semicircle of radius 2. What is the largest area the
rectangle can have? What are its dimensions?

<img width="281" alt="image" src="https://github.com/user-attachments/assets/ad9d0907-f550-44d1-b671-c16c56ec70ee" />
<img width="262" alt="image" src="https://github.com/user-attachments/assets/d0385548-3ff8-472a-a45b-033eba889a3c" />
<img width="259" alt="image" src="https://github.com/user-attachments/assets/210dc469-7473-41a2-aa5c-f5a3c23ddc4e" />

------------------
## A farmer has only enough material for 60 meters of fencing. If he were to fence a
rectangular patch of garden, what dimensions of the rectangle will the fenced area be
maximum?
<img width="246" alt="image" src="https://github.com/user-attachments/assets/01b6091e-ee59-4fe3-8463-3ccf280f8e27" />
<img width="254" alt="image" src="https://github.com/user-attachments/assets/6ee1f477-e011-4ef7-ab30-b9019435e724" />

------------------
## There are 50 apple trees in an orchard. Each tree produces 800 apples. For each additional
tree planted in the orchard, the output per tree drops by 10 apples. How many trees
should be added to the existing orchard in order to maximize the total output of trees ?

<img width="290" alt="image" src="https://github.com/user-attachments/assets/5ed71f5d-b717-4df0-8742-2e73088d1083" />
<img width="294" alt="image" src="https://github.com/user-attachments/assets/547c5a08-f277-4c17-8302-8da322f53f9b" />

---------------
## A concert promoter has found that if she sells tickets for INR500 each, she can sell 1200
tickets, but for each INR50 increase in the price, 50 less people attend. At what price
should she sell the tickets to maximize her revenue? [Hint: Revenue function f(x) = xy;
where x = price per ticket, y = number of tickets sold, needs to be maximized]

<img width="290" alt="image" src="https://github.com/user-attachments/assets/08ede832-14f9-4770-8f25-59412abcdeb4" />
<img width="271" alt="image" src="https://github.com/user-attachments/assets/82d4cde4-245f-4893-9f7b-de59fb48a5f6" />

----------
<img width="310" alt="image" src="https://github.com/user-attachments/assets/d2bb37b1-f7fe-4aba-ac77-ec8bf0bebf91" />
