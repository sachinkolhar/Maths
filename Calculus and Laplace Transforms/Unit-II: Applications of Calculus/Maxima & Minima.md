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

