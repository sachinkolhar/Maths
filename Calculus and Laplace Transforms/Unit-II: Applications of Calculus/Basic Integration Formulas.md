<img width="262" alt="image" src="https://github.com/user-attachments/assets/3a67c3c7-bc6e-405f-9f86-ec291d98c3ec" /> <br>

**Basic Integration Formulas**

1.  ∫xⁿ dx = (xⁿ⁺¹)/(n+1) + C  (where n ≠ -1)
2.  ∫dx = x + C
3.  ∫cos(x) dx = sin(x) + C
4.  ∫sin(x) dx = -cos(x) + C
5.  ∫sec²(x) dx = tan(x) + C
6.  ∫csc²(x) dx = -cot(x) + C
7.  ∫sec(x)tan(x) dx = sec(x) + C
8.  ∫csc(x)cot(x) dx = -csc(x) + C
9.  ∫dx / √(1 - x²) = arcsin(x) + C
10. ∫dx / √(1 - x²) = -arccos(x) + C  (Note: This is also equal to arcsin(x) + C since arccos(x) = π/2 - arcsin(x))
11. ∫dx / (1 + x²) = arctan(x) + C
12. ∫eˣ dx = eˣ + C
13. ∫dx / x = ln|x| + C
14. ∫aˣ dx = aˣ / ln(a) + C

**Trigonometric Integrals**

15. ∫tan(x) dx = ln|sec(x)| + C
16. ∫cot(x) dx = ln|sin(x)| + C
17. ∫sec(x) dx = ln|sec(x) + tan(x)| + C
18. ∫csc(x) dx = ln|csc(x) - cot(x)| + C

**Integrals Involving a² ± x²**

19. ∫dx / (x² - a²) = (1 / 2a) ln|(x - a) / (x + a)| + C
20. ∫dx / (a² - x²) = (1 / 2a) ln|(a + x) / (a - x)| + C
21. ∫dx / (x² + a²) = (1 / a) arctan(x / a) + C
22. ∫dx / √(x² - a²) = ln|x + √(x² - a²)| + C
23. ∫dx / √(a² - x²) = arcsin(x / a) + C
24. ∫dx / √(x² + a²) = ln|x + √(x² + a²)| + C

**Integrals Involving √(a² ± x²)**

25. ∫√(a² - x²) dx = (x/2)√(a² - x²) + (a²/2)arcsin(x/a) + C
26. ∫√(x² + a²) dx = (x/2)√(x² + a²) + (a²/2)ln|x + √(x² + a²)| + C
27. ∫√(x² - a²) dx = (x/2)√(x² - a²) - (a²/2)ln|x + √(x² - a²)| + C
28. cos ^2(x)+sin^2(x)=1
29. sec 
^2
 (x)−tan 
2
 (x)=1


30. <img width="331" alt="image" src="https://github.com/user-attachments/assets/60f6d8fc-3b4d-4cce-bc07-e5fb9effaff1" />
<img width="347" alt="image" src="https://github.com/user-attachments/assets/4eed27f0-9f07-4de5-8c90-acb75dc3eaee" />

-----
<img width="485" alt="image" src="https://github.com/user-attachments/assets/ddb7f093-27f0-4638-8aef-6c9d346f808e" />
<img width="341" alt="image" src="https://github.com/user-attachments/assets/7b3ca41d-257c-416b-bfd6-757b2272d7cb" />

-------------
# Even and Odd Functions in Definite Integrals
<img width="487" alt="image" src="https://github.com/user-attachments/assets/c08b76fa-10f7-4941-ba39-954b1dc80364" />
<img width="342" alt="image" src="https://github.com/user-attachments/assets/1f15edd0-b0bc-4bd8-bde6-82f0722ecf80" />
<img width="329" alt="image" src="https://github.com/user-attachments/assets/8a57b5ae-c5a3-482d-adae-ef37ff17b0ba" />

-------------
# when to multiply by the conjugate 


**1. Look for Expressions of the Form a ± b**

   * **Radicals:** If you have an expression like $\sqrt{a} \pm \sqrt{b}$ in the denominator (or sometimes numerator), multiplying by the conjugate $(\sqrt{a} \mp \sqrt{b})$ will eliminate the radicals using the difference of squares identity: $(a+b)(a-b) = a^2 - b^2$.
   * **Trigonometric Functions:** Similarly, if you have expressions like $1 \pm \sin(x)$, $1 \pm \cos(x)$, $\sec(x) \pm \tan(x)$, etc., in the denominator, multiplying by the conjugate will often allow you to use trigonometric identities to simplify the expression.

**2. Aim to Eliminate Radicals or Simplify Trigonometric Expressions**

   * **Radicals:** The goal is to get rid of square roots in the denominator (or sometimes numerator) to make the integral easier to handle.
   * **Trigonometric Functions:** The goal is to use trigonometric identities (like $\sin^2(x) + \cos^2(x) = 1$ or $\sec^2(x) - \tan^2(x) = 1$) to simplify the expression and make it integrable.

**3. Practice and Pattern Recognition**

   * **Work Through Examples:** The more examples you work through, the better you'll become at recognizing these patterns.
   * **Pay Attention to Denominators:** Focus on the denominators of fractions in integrals. If you see expressions like those mentioned in point 1, consider multiplying by the conjugate.

**Why Does It Work?**

The reason multiplying by the conjugate works is that it uses the difference of squares identity:

$$(a + b)(a - b) = a^2 - b^2$$

In the case of $1 - \sin(x)$:

$$(1 - \sin(x))(1 + \sin(x)) = 1^2 - \sin^2(x) = 1 - \sin^2(x) = \cos^2(x)$$

This eliminates the $\sin(x)$ term in the denominator, making it easier to integrate.

**Let's Summarize:**

* **Identify:** Look for expressions of the form $a \pm b$ in the denominator (radicals or trigonometric functions).
* **Multiply:** Multiply the numerator and denominator by the conjugate $a \mp b$.
* **Simplify:** Use the difference of squares identity and relevant trigonometric identities.
* **Integrate:** Proceed with integration.

Don't worry if it doesn't click immediately! It takes practice to develop this intuition. Keep working through examples, and you'll start to recognize these situations more easily.

-----
# trigonometric identities for the sum and difference of angles:

**Sine Identities:**

* **Sine of a Sum:**
    $$\sin(A + B) = \sin(A) \cos(B) + \cos(A) \sin(B)$$

* **Sine of a Difference:**
    $$\sin(A - B) = \sin(A) \cos(B) - \cos(A) \sin(B)$$

**Cosine Identities:**

* **Cosine of a Sum:**
    $$\cos(A + B) = \cos(A) \cos(B) - \sin(A) \sin(B)$$

* **Cosine of a Difference:**
    $$\cos(A - B) = \cos(A) \cos(B) + \sin(A) \sin(B)$$

**Tangent Identities:**

* **Tangent of a Sum:**
    $$\tan(A + B) = \frac{\tan(A) + \tan(B)}{1 - \tan(A) \tan(B)}$$

* **Tangent of a Difference:**
    $$\tan(A - B) = \frac{\tan(A) - \tan(B)}{1 + \tan(A) \tan(B)}$$

**Key Points:**

* These identities are fundamental in trigonometry and are used to derive other trigonometric formulas and solve various problems.
* The signs in the cosine identities are opposite to those in the sine identities.
* The tangent identities are derived from the sine and cosine identities.

----
# **Substitution in Integration (u-substitution)**

Substitution, often called u-substitution, is a powerful technique for simplifying integrals by essentially "undoing" the chain rule of differentiation. It's particularly useful when you have a composite function within an integral, along with its derivative (or a multiple thereof).

**The Basic Idea**

The core idea is to replace a part of the integrand with a new variable (usually 'u') to make the integral easier to evaluate.  Then, we express the original integral in terms of 'u' and 'du', integrate with respect to 'u', and finally substitute back to express the result in terms of the original variable.

**Steps for Substitution**

1. **Choose a Substitution (u):** Identify a part of the integrand that, when substituted with 'u', simplifies the integral. Look for a function and its derivative (or a multiple) within the integral.

2. **Find du:** Differentiate 'u' with respect to the original variable (usually 'x') to find 'du'.  Rewrite 'du' to isolate 'dx' if needed.

3. **Substitute:** Replace the chosen part of the integrand with 'u' and replace 'dx' with the expression you found for 'dx' in terms of 'du'.

4. **Integrate:** Evaluate the new integral with respect to 'u'.

5. **Substitute Back:** Replace 'u' with the original expression in terms of the original variable to get the final result.

**Example**

Let's illustrate with the integral we discussed earlier:

$$\int \sin^2(3x) \cos(3x) \, dx$$

1. **Choose u:** Let $u = \sin(3x)$

2. **Find du:** $$du = \frac{d}{dx} (\sin(3x)) \, dx$$
   $$du = \cos(3x) \cdot 3 \, dx$$
   $$du = 3 \cos(3x) \, dx$$

   Solve for $\cos(3x) \, dx$:
   $$\cos(3x) \, dx = \frac{1}{3} \, du$$

3. **Substitute:**
   $$\int \sin^2(3x) \cos(3x) \, dx = \int u^2 \cdot \frac{1}{3} \, du$$
   $$= \frac{1}{3} \int u^2 \, du$$

4. **Integrate:**
   $$\frac{1}{3} \int u^2 \, du = \frac{1}{3} \cdot \frac{u^3}{3} + C$$
   $$= \frac{u^3}{9} + C$$

5. **Substitute Back:**
   $$\frac{u^3}{9} + C = \frac{\sin^3(3x)}{9} + C$$

**Key Points**

* **Recognizing Patterns:** The most challenging part is often choosing the right substitution. Practice and familiarity with derivatives will help you spot suitable substitutions.
* **Simplification:** The goal is to make the integral simpler to evaluate.
* **Chain Rule in Reverse:** Substitution essentially reverses the chain rule.

**When to Use Substitution**

Substitution is particularly useful when you have:

* **Composite Functions:** An integral containing a function within another function.
* **A Function and its Derivative:** An integral where you can identify a function and its derivative (or a multiple) within the integrand.

Let me know if you would like to work through another example or have any further questions!

