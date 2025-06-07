# Physics-Informed Neural Network with Symbolic Regression for Deriving Analytical Approximate Solutions to Nonlinear Partial Differential Equations

This work explores an interpretable approach based on **Physics-Informed Neural Networks (PINNs)** combined with **Symbolic Regression (SR)** to derive mathematical expressions for approximate solutions to nonlinear partial differential equations (PDEs) modeling arterial blood flow influenced by external magnetic fields.

While PINNs are adept at learning physics-informed representations, they often lack interpretability and require significant computational resources. To address this, we integrate the **PySR symbolic regression framework** with PINNs. PySR utilizes **evolutionary genetic programming** with a customizable set of mathematical operators (trigonometric, exponential, arithmetic, etc.) to extract concise symbolic expressions from PINN-generated data.

### Highlights:
- PINNs capture physical laws from PDEs representing pulsatile blood flow under magnetic influence.
- Symbolic regression provides transparent, analytical approximations of these solutions.
- The resulting expressions are:
  - Accurate (low MSE)
  - Statistically validated
  - Real-time executable
- Numerical and statistical validations confirm the reliability and effectiveness of the hybrid approach.
- This methodology offers interpretable insights into biofluid mechanics, especially the interaction between magnetic fields and viscoelastic blood flow.

---

## 📁 Associated Files and Figures

| **File Name**                                | **Associated Figures**                        |
|---------------------------------------------|----------------------------------------------|
| `Numerical_Validation_Data_Points_Burger`   | Fig. 21(a), 22(a), 22(b), 22(c), 22(d)        |
| `Statistical_Validation_fifth`              | Fig. 19(b), 20(b)                             |
| `Statistical_Validation_Forced_Burger`      | Fig. 19(a), 20(a)                             |
| `Symbolic_Burger_M_0_2`                     | Fig. 8(a), 9(a), 10(a), 11(a), 11(b), 12(a)   |
| `Symbolic_Burger_M_0_4`                     | Fig. 8(b), 9(b), 10(b), 11(c), 11(d), 12(b)   |
| `Symbolic_Burger_M_5`                       | Fig. 8(c), 9(c), 10(c), 13(a), 13(b), 14(a)   |
| `Symbolic_Burger_M_10`                      | Fig. 8(d), 9(d), 10(d), 13(c), 13(d), 14(b)   |
| `Symbolic_fifth_order_M_0.2`                | Fig. 15(a), 16(a), 16(b), 17(a), 18(a), 18(b) |
| `Symbolic_fifth_order_M_0.4`                | Fig. 15(b), 16(c), 16(d), 17(b), 18(c), 18(d) |

---

## 🔗 Repository Link
[GitHub - SymPINNPDE](https://github.com/satyasaran/SymPINNPDE)

---

## 🏷️ Keywords
Physics-Informed Neural Networks, Symbolic Regression, Nonlinear PDEs, Arterial Blood Flow, Magnetic Fields, PySR, Biofluid Mechanics, Analytical Approximation
