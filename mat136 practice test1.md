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
---

### **Question 4(a): Height \( h \) in Terms of \( f(x) \)**

**Problem**:  
The area of a rectangle equals the **net area** between \( y = f(x) \), the \( x \)-axis, and \( x = a \) to \( x = b \). Express the height \( h \) of the rectangle in terms of \( f(x) \).

**Solution**:  
1. The area of a rectangle with height \( h \) and width \( (b - a) \) is:
   \[
   \text{Area} = h(b - a).
   \]

2. The net area under \( f(x) \) between \( x = a \) and \( x = b \) is given by:
   \[
   \int_a^b f(x) \, dx.
   \]

3. Since the areas are equal:
   \[
   h(b - a) = \int_a^b f(x) \, dx.
   \]

4. Solving for \( h \), we get:
   \[
   h = \frac{1}{b - a} \int_a^b f(x) \, dx.
   \]

5. This result shows that \( h \) is the **average value** of \( f(x) \) on the interval \([a, b]\).

**Conclusion**: The height \( h \) of the rectangle is:
\[
h = \frac{1}{b - a} \int_a^b f(x) \, dx.
\]

---

### **Question 4(b): Average Velocity Using Integrals**

**Problem**:  
Express the **average velocity** of a particle moving along a straight line from \( t = 0 \) to \( t = 2 \) using integrals and \( v(t) \) (the velocity function).

**Solution**:  
1. The average velocity is defined as:
   \[
   \text{Average velocity} = \frac{\text{Net displacement}}{\text{Time interval}}.
   \]

2. By the **Fundamental Theorem of Calculus**, the net displacement is:
   \[
   p(2) - p(0) = \int_0^2 v(t) \, dt,
   \]
   where \( p(t) \) is the position function and \( v(t) \) is the velocity.

3. The time interval is \( 2 - 0 = 2 \). Therefore, the average velocity is:
   \[
   \text{Average velocity} = \frac{1}{2} \int_0^2 v(t) \, dt.
   \]

**Conclusion**: The average velocity is:
\[
\text{Average velocity} = \frac{1}{2} \int_0^2 v(t) \, dt.
\]

---

### **Question 5(a): Left and Right Riemann Sums**

**Problem**:  
Using the table of \( v(t) \) values, compute the **left Riemann sum** and **right Riemann sum** for \( n = 3 \), then find their average.

| \( t \) | \( v(t) \) |
|---------|-----------|
| 0       | 10        |
| 1       | -5        |
| 2       | 2         |
| 3       | 12        |

**Solution**:  
1. **Left Riemann Sum**: Use values at the **left endpoints** of each subinterval:
   \[
   \text{Left sum} = (1)(v(0)) + (1)(v(1)) + (1)(v(2)).
   \]
   Substituting values:
   \[
   \text{Left sum} = 1(10) + 1(-5) + 1(2) = 7.
   \]

2. **Right Riemann Sum**: Use values at the **right endpoints**:
   \[
   \text{Right sum} = (1)(v(1)) + (1)(v(2)) + (1)(v(3)).
   \]
   Substituting values:
   \[
   \text{Right sum} = 1(-5) + 1(2) + 1(12) = 9.
   \]

3. **Average of the Sums**:
   \[
   \text{Average} = \frac{\text{Left sum} + \text{Right sum}}{2}.
   \]
   Substituting:
   \[
   \text{Average} = \frac{7 + 9}{2} = 8.
   \]

**Conclusion**:  
- **Left Riemann Sum**: \( 7 \).  
- **Right Riemann Sum**: \( 9 \).  
- **Average**: \( 8 \).

---

### **Question 5(b): Interpretation of Riemann Sums**

**Problem**:  
What does the average of the left and right Riemann sums approximate, and in what units is it measured?

**Solution**:  
1. The function \( v(t) \) represents the velocity of the cyclist in **km/min**.

2. The Riemann sums approximate the **net distance** traveled by the cyclist over the given time interval.

3. Therefore, the average of the sums approximates the **net displacement** in kilometers (km).

**Conclusion**: The average value approximates the **net distance traveled** by the cyclist, measured in **kilometers (km)**.

---
---

### **Question 6(a): Number of Antiderivatives of \( k(x) = 6x + 14e^{7x} \)**

**Problem**:  
How many antiderivatives exist for \( k(x) = 6x + 14e^{7x} \)?

**Solution**:  
1. The general form of an antiderivative includes an **arbitrary constant** \( C \), because differentiation of any constant equals zero.

2. To find the antiderivative of \( k(x) \):
   - Integrate \( k(x) = 6x + 14e^{7x} \):
     \[
     \int k(x) \, dx = \int (6x) \, dx + \int (14e^{7x}) \, dx.
     \]

3. Perform the integrations:
   - \( \int 6x \, dx = 3x^2 \),
   - \( \int 14e^{7x} \, dx = 2e^{7x} \) (using substitution for \( 7x \)).

4. The general antiderivative is:
   \[
   F(x) = 3x^2 + 2e^{7x} + C,
   \]
   where \( C \) is an arbitrary constant.

5. Since \( C \) can take **any real value**, there are **infinitely many antiderivatives**.

**Conclusion**: There are **infinitely many antiderivatives** of \( k(x) = 6x + 14e^{7x} \), each differing by a constant \( C \).

---

### **Question 6(b): Specific Antiderivative Through \( (0, 3) \)**

**Problem**:  
Find the antiderivative of \( k(x) = 6x + 14e^{7x} \) whose graph passes through the point \( (0, 3) \).

**Solution**:  
1. The general antiderivative is:
   \[
   F(x) = 3x^2 + 2e^{7x} + C.
   \]

2. Use the condition \( F(0) = 3 \) to solve for \( C \):
   - Substitute \( x = 0 \) and \( F(0) = 3 \):
     \[
     F(0) = 3(0)^2 + 2e^{7(0)} + C.
     \]
   - Simplify:
     \[
     3 = 0 + 2(1) + C \implies 3 = 2 + C.
     \]
   - Solve for \( C \):
     \[
     C = 1.
     \]

3. The specific antiderivative is:
   \[
   F(x) = 3x^2 + 2e^{7x} + 1.
   \]

**Conclusion**: The antiderivative that passes through \( (0, 3) \) is:
\[
F(x) = 3x^2 + 2e^{7x} + 1.
\]

---

### **Question 7: Antiderivative Through a Given Point**

**Problem**:  
Given the expression:
\[
F(x) = \left( \int_0^x t^2 \, dt \right) + C,
\]
find \( C \) such that \( F(3) = 2 \).

**Solution**:  
1. Evaluate \( \int_0^3 t^2 \, dt \):
   - Use the power rule for integration:
     \[
     \int_0^3 t^2 \, dt = \frac{t^3}{3} \Big|_0^3.
     \]
   - Substitute the limits:
     \[
     \int_0^3 t^2 \, dt = \frac{3^3}{3} - \frac{0^3}{3} = \frac{27}{3} = 9.
     \]

2. Substitute \( F(3) = 2 \) into the expression:
   \[
   F(x) = 9 + C.
   \]
   At \( x = 3 \), we are given \( F(3) = 2 \):
   \[
   2 = 9 + C.
   \]

3. Solve for \( C \):
   \[
   C = -7.
   \]

**Conclusion**: The constant \( C \) is \( -7 \), so the function becomes:
\[
F(x) = \left( \int_0^x t^2 \, dt \right) - 7.
\]

---

### **Question 8: Evaluate the Integral**

**Problem**:  
Evaluate:
\[
\int_0^\pi 6 \sin(2x + \pi) e^{\cos(2x + \pi)} \, dx.
\]

**Solution**:  
1. Recognize that the integrand contains a composite function. Let:
   \[
   u = \cos(2x + \pi).
   \]
   Then:
   \[
   \frac{du}{dx} = -2 \sin(2x + \pi) \implies du = -2 \sin(2x + \pi) \, dx.
   \]

2. Rewrite the integral in terms of \( u \):
   - Factor \( -3 \) out to match the derivative:
     \[
     \int_0^\pi 6 \sin(2x + \pi) e^{\cos(2x + \pi)} \, dx = -3 \int_0^\pi -2 \sin(2x + \pi) e^{\cos(2x + \pi)} \, dx.
     \]
   - Substituting:
     \[
     = -3 \int_{u_1}^{u_2} e^u \, du,
     \]
     where \( u_1 = \cos(\pi) = -1 \) and \( u_2 = \cos(0) = -1 \).

3. The limits of integration are identical (\( -1 \) to \( -1 \)), so the integral evaluates to **zero**.

**Conclusion**: The value of the integral is:
\[
\int_0^\pi 6 \sin(2x + \pi) e^{\cos(2x + \pi)} \, dx = 0.
\]

---

### **Question 9: Differentiation Under the Integral**

**Problem**:  
Differentiate the following with respect to \( u \):
\[
\int_0^{\sqrt{u}} e^{-t^2} \, dt.
\]

**Solution**:  
1. Let \( F(u) = \int_0^{\sqrt{u}} e^{-t^2} \, dt \).

2. By the **Fundamental Theorem of Calculus** and the **chain rule**:
   - Differentiating with respect to \( u \):
     \[
     \frac{d}{du} F(u) = \frac{d}{du} \left( F(\sqrt{u}) \right).
     \]

3. Using the chain rule:
   - Let \( x = \sqrt{u} \). Then:
     \[
     \frac{d}{du} \left( \int_0^x e^{-t^2} \, dt \right) = e^{-x^2} \cdot \frac{dx}{du}.
     \]
   - Since \( x = \sqrt{u} \), we have \( \frac{dx}{du} = \frac{1}{2\sqrt{u}} \).

4. Combine terms:
   \[
   \frac{d}{du} \int_0^{\sqrt{u}} e^{-t^2} \, dt = \frac{1}{2\sqrt{u}} e^{-u}.
   \]

**Conclusion**: The derivative is:
\[
\frac{d}{du} \int_0^{\sqrt{u}} e^{-t^2} \, dt = \frac{1}{2\sqrt{u}} e^{-u}.
\]

---
---

### **Question 10: Sketch \( y = f(x) \) Given \( y = f'(x) \)**

**Problem**:  
You are given the graph of \( y = f'(x) \) and need to sketch a possible graph of \( y = f(x) \), knowing that \( f(0) = 0 \).

**Solution**:  
1. **Relationship Between \( f(x) \) and \( f'(x) \)**:  
   - The graph of \( f'(x) \) represents the **slope** of \( f(x) \).
   - Where \( f'(x) > 0 \), the slope of \( f(x) \) is positive, so \( f(x) \) increases.
   - Where \( f'(x) < 0 \), the slope of \( f(x) \) is negative, so \( f(x) \) decreases.
   - Where \( f'(x) = 0 \), \( f(x) \) has a **critical point** (local maximum, minimum, or an inflection point).

2. **Constructing the Graph**:  
   - Start at \( f(0) = 0 \) (the given condition).
   - Analyze the behavior of \( f'(x) \):
     - Identify intervals where \( f'(x) > 0 \): \( f(x) \) will increase on these intervals.
     - Identify intervals where \( f'(x) < 0 \): \( f(x) \) will decrease on these intervals.
     - Identify points where \( f'(x) = 0 \): Sketch a horizontal tangent at these points.

3. **Shape of the Graph**:  
   - Use the behavior of \( f'(x) \) to construct \( f(x) \):
     - Rising when \( f'(x) > 0 \),
     - Falling when \( f'(x) < 0 \),
     - Flattening out at points where \( f'(x) = 0 \).

**Conclusion**: The graph of \( f(x) \) is constructed based on the slopes provided by \( f'(x) \), starting at \( f(0) = 0 \).

---

### **Question 11: Net Area Under the Concentration Curve**

**Problem**:  
The drug concentration \( C(t) = 15tH(t) \), where \( H(10) = 0.1 \) and values of \( H'(t) \) are provided. Estimate the net area under \( C(t) \) from \( t = 0 \) to \( t = 10 \).

**Solution**:  
1. **Set Up the Integral**:  
   The net area under \( C(t) \) is:
   \[
   \int_0^{10} C(t) \, dt = \int_0^{10} 15tH(t) \, dt.
   \]

2. **Simplify Using Integration by Parts**:  
   - Use \( u = H(t) \) and \( dv = t \, dt \), so \( du = H'(t) \, dt \) and \( v = \frac{t^2}{2} \).
   - Apply integration by parts:
     \[
     \int tH(t) \, dt = \frac{t^2}{2}H(t) \Big|_0^{10} - \int_0^{10} \frac{t^2}{2}H'(t) \, dt.
     \]

3. **Evaluate the Boundary Term**:  
   Substituting \( H(10) = 0.1 \) and \( H(0) = 0 \):
   \[
   \frac{t^2}{2}H(t) \Big|_0^{10} = \frac{10^2}{2} \cdot 0.1 = 5.
   \]

4. **Estimate the Remaining Integral**:  
   Use a left Riemann sum to approximate:
   \[
   \int_0^{10} \frac{t^2}{2} H'(t) \, dt \approx 2 \left( \frac{0^2}{2}H'(0) + \frac{2^2}{2}H'(2) + \frac{4^2}{2}H'(4) + \frac{6^2}{2}H'(6) + \frac{8^2}{2}H'(8) \right).
   \]
   Substituting the values of \( H'(t) \):
   - \( H'(0) = -0.2, \ H'(2) = -0.15, \ H'(4) = -0.1, \ H'(6) = -0.06, \ H'(8) = -0.02 \),
   - Compute:
     \[
     2 \left( 0 - 0.6 - 1.6 - 2.16 - 1.28 \right) = -5.64.
     \]

5. **Combine Results**:  
   Substituting back:
   \[
   \int_0^{10} 15tH(t) \, dt = 15 \left( 5 - (-5.64) \right) = 15(10.64) = 159.6.
   \]

**Conclusion**: The net area under the concentration curve is approximately:
\[
159.6 \, \text{(mg·h/ml)}.
\]

---

### **Question 12(a): Second Derivative of \( y \)**

**Problem**:  
Given \( \frac{dy}{dx} = -x^2y^4 \), find \( y''(x) \) as a function of \( x \) and \( y \).

**Solution**:  
1. Differentiate both sides of \( \frac{dy}{dx} = -x^2y^4 \) using the **product rule** and chain rule:
   \[
   \frac{d^2y}{dx^2} = \frac{d}{dx} \left( -x^2y^4 \right).
   \]

2. Apply the product rule to \( -x^2y^4 \):
   \[
   \frac{d}{dx} \left( -x^2y^4 \right) = -2xy^4 - x^2 \cdot 4y^3 \frac{dy}{dx}.
   \]

3. Substitute \( \frac{dy}{dx} = -x^2y^4 \) into the expression:
   \[
   \frac{d^2y}{dx^2} = -2xy^4 + (-x^2)(4y^3)(-x^2y^4).
   \]

4. Simplify:
   \[
   \frac{d^2y}{dx^2} = -2xy^4 + 4x^4y^7.
   \]

**Conclusion**: The second derivative is:
\[
\frac{d^2y}{dx^2} = -2xy^4 + 4x^4y^7.
\]

---

### **Question 12(b): Behavior of Solutions**

**Problem**:  
Are solutions to \( \frac{dy}{dx} = -x^2y^4 \) increasing, decreasing, or both?

**Solution**:  
1. Since \( \frac{dy}{dx} = -x^2y^4 \), analyze the sign of the derivative:
   - \( x^2 \geq 0 \) for all \( x \),
   - \( y^4 > 0 \) for all \( y \neq 0 \).

2. Therefore:
   - \( \frac{dy}{dx} \leq 0 \) for all \( x \) and \( y \),
   - Equality occurs only if \( y = 0 \) or \( x = 0 \).

3. This implies that the solution \( y \) is always **decreasing** (or constant at specific points).

**Conclusion**: Solutions to the differential equation are **decreasing functions**.

---

