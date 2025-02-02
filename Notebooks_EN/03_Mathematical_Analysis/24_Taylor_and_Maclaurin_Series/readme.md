# 24_Taylor_and_Maclaurin_Series
### **1. $ \int 1 dx = x $**  
**Explanation:** The integral of a constant is the constant multiplied by the variable.

---

### **2. $ \int (x^2 + 2) dx = \frac{x^3}{3} + 2x $**  
**Explanation:** Apply the power rule to each term separately.

---

### **3. $ \int 2 \sin(x) dx = -2 \cos(x) $**  
**Explanation:** The integral of $ \sin(x) $ is $ -\cos(x) $; factor 2 out.

---

### **4. $ \int \frac{3}{x} dx = 3 \ln |x| $**  
**Explanation:** The integral of $ \frac{1}{x} $ is $ \ln |x| $, with the constant 3 factored out.

---

### **5. $ \int \frac{1}{x^2} dx = -\frac{1}{x} $**  
**Explanation:** Rewrite $ \frac{1}{x^2} $ as $ x^{-2} $ and apply the power rule.

---

### **6. $ \int \left( \frac{1}{3} x^4 - 5 \right) dx = \frac{x^5}{15} - 5x $**  
**Explanation:** Apply the power rule to each term separately.

---

### **7. $ \int (\sin^2 x + \cos^2 x) dx = x $**  
**Explanation:** $ \sin^2 x + \cos^2 x = 1 $, so the integral becomes $ \int 1 dx $.

---

### **8. $ \int (5 \sin x + 3e^x) dx = -5 \cos(x) + 3e^x $**  
**Explanation:** Integrate each term separately using trigonometric and exponential rules.

---

### **9. $ \int \sqrt[3]{x} dx = \frac{3}{4} x^{\frac{4}{3}} $**  
**Explanation:** Rewrite $ \sqrt[3]{x} $ as $ x^{1/3} $ and apply the power rule.

---

### **10. $ \int \sqrt{10x} dx = \frac{2\sqrt{10}}{3} x^{\frac{3}{2}} $**  
**Explanation:** Rewrite $ \sqrt{10x} $ as $ (10x)^{1/2} $ and integrate.

---

### **11. $ \int \cos\left(\frac{5}{2}x + 3\right) dx = \frac{2}{5} \sin\left(\frac{5}{2}x + 3\right) $**  
**Explanation:** Use the chain rule to handle the inner function $ \frac{5}{2}x + 3 $.

---

### **12. $ \int \frac{\cos(\ln(x))}{x} dx = \sin(\ln(x)) $**  
**Explanation:** The inner function $ \ln(x) $ has a derivative of $ 1/x $, allowing chain rule application.

---

### **13. $ \int x \ln(x) dx = \frac{x^2}{2} \ln(x) - \frac{x^2}{4} $**  
**Explanation:** Use integration by parts with $ u = \ln(x) $ and $ dv = x dx $.

---

### **14. $ \int x e^x dx = (x - 1) e^x $**  
**Explanation:** Use integration by parts with $ u = x $ and $ dv = e^x dx $.

---

### **1. Integrate $ f(x) = 2x + 1 $ over $ [0, \pi] $**
- **Explanation:** We want to find the area under the curve $ f(x) = 2x + 1 $ from $ x = 0 $ to $ x = \pi $.
  - Integrate:  
    $ \int_0^\pi (2x + 1) dx = \left[ x^2 + x \right]_0^\pi = \pi^2 + \pi $
  - This gives: $ 13.01 $

**Result:**  
$ \int_0^\pi (2x + 1) dx = 13.01 $

---

### **2. Integrate $ g(x) = x^2 $ over $ [0, \pi] $**
- **Explanation:** We want to find the area under the curve $ g(x) = x^2 $ from $ x = 0 $ to $ x = \pi $.
  - Integrate:  
    $ \int_0^\pi x^2 dx = \left[ \frac{x^3}{3} \right]_0^\pi = \frac{\pi^3}{3} $
  - This gives approximately $ 10.34 $.

**Result:**  
$ \int_0^\pi x^2 dx = 10.34 $

---

### **3. Calculate the area of the region bounded by $ x = 1 $, $ x = 2 $, $ y = 0 $, and $ y = x^2 + 1 $**
- **Explanation:** We want to find the area under the curve $ y = x^2 + 1 $ between $ x = 1 $ and $ x = 2 $.
  - Integrate:  
    $ \int_1^2 (x^2 + 1) dx = \left[ \frac{x^3}{3} + x \right]_1^2 $
  - This evaluates to $ \frac{10}{3} \approx 3.33 $.

**Result:**  
$ \int_1^2 (x^2 + 1) dx = \frac{10}{3} \approx 3.33 $

---

### **4. Calculate the area under the sine curve over $ [0, \pi] $**
- **Explanation:** We want to find the area under the curve $ y = \sin(x) $ from $ x = 0 $ to $ x = \pi $.
  - Integrate:  
    $ \int_0^\pi \sin(x) dx = \left[ -\cos(x) \right]_0^\pi = 2 $

**Result:**  
$ \int_0^\pi \sin(x) dx = 2 $

---

### **5. Calculate the length of the sine curve over $ [0, \pi] $**
- **Explanation:** The formula for the arc length of a curve $ y = f(x) $ is given by:  
  $ L = \int_a^b \sqrt{1 + (f'(x))^2} dx $
  
  - For $ f(x) = \sin(x) $, $ f'(x) = \cos(x) $.
  - The arc length integral becomes:  
    $ L = \int_0^\pi \sqrt{1 + \cos^2(x)} dx $
  - This integral cannot be expressed in a simple closed form but can be approximated numerically or visualized in GeoGebra.

---

### **6. Calculate the distance traveled by the particle for $ x(t) = 3t^2 - 6t + 1 $ over $ t \in [0, 2] $**
1. **Find the velocity:**  
   - The velocity is the derivative of the position function:  
     $ V(t) = \frac{dx(t)}{dt} = 6t - 6 $

2. **Calculate the distance:**  
   - The distance traveled is given by the integral of the absolute value of the velocity:  
     $ \text{Distance} = \int_0^2 |V(t)| dt $
   - Since $ V(t) $ changes sign at $ t = 1 $, we split the integral:  
     $ \int_0^2 |V(t)| dt = \int_0^1 (6 - 6t) dt + \int_1^2 (6t - 6) dt = 6 $

**Result:**  
The distance traveled is $ 6 $ units.
