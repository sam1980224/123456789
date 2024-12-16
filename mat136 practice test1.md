---

## Practice Test 1 Solutions

---

### **Question 1: Over-Approximation vs. Under-Approximation**

**Problem**:  
The degree-2 Taylor polynomial \( P_2(x) = -3 + 5x - 7x^2 \) approximates \( f(x) \) near \( x = 0 \). Does the **linear approximation** \( L(0.01) \) overestimate or underestimate \( f(0.01) \)?

**Solution**:  
1. The linear approximation \( L(x) \) at \( x = 0 \) is the tangent line:
   \[
   L(x) = f(0) + f'(0)x.
   \]
   From \( P_2(x) = -3 + 5x - 7x^2 \):
   - \( f(0) = -3 \) (constant term),
   - \( f'(0) = 5 \) (coefficient of \( x \)).

   Thus, the tangent line is:
   \[
   L(x) = -3 + 5x.
   \]

2. The concavity of \( f(x) \) depends on \( f''(0) \), derived from the \( x^2 \)-term:
   \[
   \frac{f''(0)}{2!} = -7 \implies f''(0) = -14.
   \]
   Since \( f''(0) < 0 \), \( f(x) \) is **concave down** near \( x = 0 \).

3. For a concave-down function:
   - The tangent line lies **above** the curve.

4. Therefore, the linear approximation \( L(0.01) \) **overestimates** \( f(0.01) \).

**Conclusion**: \( L(0.01) \) is an **over-approximation** of \( f(0.01) \).

---

### **Question 2: Degree-100 Taylor Polynomial**

**Problem**:  
Find the degree-100 Taylor polynomial of \( f(x) = 4x^2 + 5x + 6 \) centered at \( x = 1 \).

**Solution**:  
1. The Taylor series centered at \( x = 1 \) is:
   \[
   P_n(x) = f(1) + f'(1)(x - 1) + \frac{f''(1)}{2!}(x - 1)^2 + \dots
   \]
   Since \( f(x) \) is a **degree-2 polynomial**, its derivatives beyond the second are zero:
   \[
   f'''(x) = 0, \ f^{(4)}(x) = 0, \dots
   \]

2. Compute \( f(1), f'(1), \) and \( f''(1) \):
   - \( f(x) = 4x^2 + 5x + 6 \),
   - \( f'(x) = 8x + 5 \implies f'(1) = 13 \),
   - \( f''(x) = 8 \implies f''(1) = 8 \),
   - \( f(1) = 4(1)^2 + 5(1) + 6 = 15 \).

3. Substitute these into the Taylor series:
   \[
   P_{100}(x) = f(1) + f'(1)(x - 1) + \frac{f''(1)}{2!}(x - 1)^2.
   \]
   Simplifying:
   \[
   P_{100}(x) = 15 + 13(x - 1) + 4(x - 1)^2.
   \]

**Conclusion**: The degree-100 Taylor polynomial is:
\[
P_{100}(x) = 15 + 13(x - 1) + 4(x - 1)^2.
\]

---

### **Question 3: Total Distance vs. Net Distance**

**Problem**:  
A squirrel travels for 10 minutes. Is the **total distance** \( T \) greater than, less than, or equal to the **net distance** \( N \)? Explain.

**Solution**:  
1. **Net Distance \( N \)**:
   - Net distance considers direction. Forward movement is **positive**, and backward movement is **negative**.
   - If the squirrel moves 5 meters forward and 5 meters backward:
     \[
     N = 5 + (-5) = 0 \ \text{meters}.
     \]

2. **Total Distance \( T \)**:
   - Total distance adds the absolute values of distances, ignoring direction:
     \[
     T = |5| + |5| = 10 \ \text{meters}.
     \]

3. **Relationship**:
   - The total distance \( T \) is **always greater than or equal to** the net distance \( N \).
   - Equality \( T = N \) occurs only if the squirrel moves in a straight line without reversing direction.

**Conclusion**: The total distance \( T \) is **greater than or equal to** the net distance \( N \). Equality happens if the motion is in a single direction.

---
