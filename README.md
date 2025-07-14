# 📐 Gagliardo-Nirenberg-Sobolev Inequality – Theoretical Project

This repository contains the full Beamer presentation and theoretical study around the **Gagliardo-Nirenberg-Sobolev Inequality**, a fundamental result in the analysis of partial differential equations.

---

## 📌 Project Overview

📄 **Title**: Inégalité de Gagliardo-Nirenberg-Sobolev  
👩‍💻 **Author**: Hajar BADRAOUI  
🏛️ **University**: Faculté des Sciences, Université Mohammed V – Rabat  
📅 **Presentation Date**: October 24, 2023  
🎓 **Supervisor**: Mr. Abdallah MAICHINE

This project was developed as part of an academic presentation in mathematical analysis, focusing on:

- Sobolev embeddings  
- Gagliardo-Nirenberg inequalities  
- Functional analysis techniques  
- Use of Hölder’s and interpolation inequalities

---

## 🧠 Theoretical Statement

For any function \( u \in C_c^1(\mathbb{R}^N) \) and \( p \in [1, N[ \), there exists a constant \( C > 0 \) depending only on \( p \) and \( N \) such that:

\[
\|u\|_{L^{p^*}(\mathbb{R}^N)} \leq C \|\nabla u\|_{L^p(\mathbb{R}^N)}
\]

Where:
- \( p^* = \frac{Np}{N - p} \) is the Sobolev conjugate exponent.

---

## 🧪 Proof Strategy

- Case \( p = 1 \): direct estimation using one-dimensional integrals and repeated application of Hölder's inequality.  
- Case \( p \in (1, N) \): apply the previous case to \( |u|^\alpha \), use chain rule and generalized Hölder inequality.  
- Final optimization: choose \( \alpha = \frac{p(N-1)}{N - p} \) to align exponents.

Result:
\[
\|u\|_{L^{p^*}(\mathbb{R}^N)} \leq \frac{p(N - 1)}{N - p} \|\nabla u\|_{L^p(\mathbb{R}^N)}
\]

---

## 📚 References

- Evans, Lawrence C. *Partial Differential Equations*. AMS, 2022.

---

## 📂 Contents

- `presentation.pdf` — Beamer slides with full proof  
- `README.md` — This description

---

## 📎 License

This work is shared for educational and academic reference purposes.  
© 2023 Hajar BADRAOUI

> This project was presented as part of a theoretical seminar in mathematical analysis at the Faculty of Sciences, University Mohammed V of Rabat, supervised by Mr. Abdallah Maichine.
