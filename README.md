
## About

These notebooks were prepared for the lecture **“Mathematics Meets Scientific AI: From Linear Regression to PINNs and Neural Operators”**,
held at **Ewha Womans University from July 7 to July 9, 2026**.

The materials introduce linear regression, neural network approximation, finite difference methods, physics-informed neural networks, and neural operators for solving differential equations.



## Notebooks

| Lecture | Notebook                                                      | Topic                                                                   |
| ------- | ------------------------------------------------------------- | ----------------------------------------------------------------------- |
| Lec 1   | `practice_lec1_linearfunc.ipynb`                              | Linear functions and basic model fitting                                |
| Lec 2   | `practice_lec2_nonlinearfunc-stepfunc.ipynb`                  | Nonlinear function modeling for a step function                         |
| Lec 2   | `practice_lec2_mlp-stepfunc.ipynb`                            | One-hidden layer NN modeling for a step function                        |
| Lec 3   | `practice_lec3_AD_input_1d2d3d.ipynb`                         | Automatic differentiation with 1D, 2D, and 3D inputs                    |
| Lec 3   | `practice_lec3_heat-fdm.ipynb`                                | Finite difference method for the heat equation                          |
| Lec 3   | `practice_lec3_burgers_fdm.ipynb`                             | Finite difference method for the Burgers equation                       |
| Lec 3   | `practice_lec3_burgers_fdm_v1.ipynb`                          | Finite difference method for the Burgers equation                       |
| Lec 3   | `practice_lec3_burgers_fdm_v2_upwind_central.ipynb`           | Comparison of upwind and central difference schemes                     |
| Lec 4   | `practice_lec4_heat_pinnforward.ipynb`                        | Forward PINN for the heat equation                                      |
| Lec 4   | `practice_lec4_burgers_pinnforward.ipynb`                     | Forward PINN for the Burgers equation                                   |
| Lec 4   | `practice_lec4_burgers_pinninverse.ipynb`                     | Inverse PINN for estimating viscosity                                   |
| Lec 5   | `practice_lec5_operatorlearning_gno_1dburgurs.ipynb`          | Graph Neural Operator for the 1D Burgers equation                       |
| Lec 5   | `practice_lec5_operatorlearning_fno_1dburgurs.ipynb`          | Fourier Neural Operator for the 1D Burgers equation                     |
| Lec 5   | `practice_lec5_operatorlearning_pinofno_2dnavierstokes.ipynb` | Physics-informed Fourier Neural Operator for 2D Navier–Stokes equations |


## Further Study

The following resources are recommended for students who want to study PINNs and neural operators in more depth.

### Blogs and Course Materials

* [Zongyi Li's Neural Operator Blog](https://zongyi-li.github.io/blog/)
  Introductory articles on Graph Neural Operators (GNOs) and Fourier Neural Operators (FNOs).
* [Alessandro Bombini's Teaching Materials](https://androbomb.github.io/teaching/)
  Lecture slides, course materials, and hands-on exercises on PINNs and neural operators.

### Lecture Notes

* [Physics-Informed Neural Networks and Neural Operators — Alessandro Bombini](https://androbomb.github.io/assets/pdf/Bombini_PINN_Lecture_Notes_v20260403.pdf)
  Lecture notes covering numerical differential equations, PINNs, and neural operators.

### Video Lectures

* [Tutorial on Neural Operators — Zongyi Li](https://www.youtube.com/watch?v=PpTkY8lgV3c)
  An introductory tutorial explaining the main ideas behind neural operators.
* [AI in the Sciences and Engineering 2024 — ETH Zürich](https://www.youtube.com/watch?v=LkKvhvsf6jY&list=PLJkYEExhe7rYFkBIB2U5pf_RWzYnFLj7r)
  A lecture series on deep learning, scientific machine learning, PINNs, neural operators, and related applications.

### Implementation

* [NeuralOperator](https://github.com/neuraloperator/neuraloperator)
  An open-source PyTorch library containing implementations of FNOs and other neural operator architectures.

