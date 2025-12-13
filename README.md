# 📄 Matys Laguerre -  Resume

This repository contains the LaTeX source code for my professional resume.
It uses the **AltaCV** class and is automated with **GitHub Actions** to generate the PDF on every push.

## 🛠 Tech Stack
- **Language:** LaTeX (TeX Live 2024)
- **Class:** [AltaCV](https://github.com/liantze/alta-cv)
- **Compiler:** XeLaTeX (for custom fonts: Roboto & Lato)
- **Automation:** GitHub Actions (CI/CD)

## 🚀 How to build locally
If you want to compile it on your machine:

1. Install a LaTeX distribution (TeX Live or MiKTeX).
2. Clone the repo:
   ```bash
   git clone [https://github.com/Matyslgr/Resume.git](https://github.com/Matyslgr/Resume.git)
   ```
3. Compile using `latexmk` or `xelatex`:
   ```bash
   xelatex main.tex
   ```
