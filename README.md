

---

<div align="center">

# BuildLens: OCaml Build Tooling with Dune

### A Structured and Reproducible OCaml Build Workflow using Dune & opam

</div>

---

## 📌 Overview

BuildLens is an OCaml project focused on building and managing structured workflows using the Dune build system and opam package manager. It demonstrates how to configure projects, manage dependencies, and automate builds efficiently with reproducibility and scalability.

---

## 🚀 Features

* Dune-based build configuration using S-expressions
* Dependency management with opam
* Multi-package project support
* Reproducible builds across environments
* Parallel and efficient build execution
* Command-line build automation

---

## 🏗️ Project Structure

BuildLens-OCaml-Build-Tooling-with-Dune/
│── dune-project
│── src/
│   ├── dune
│   └── *.ml
│── _build/


---

## ⚙️ How It Works

Dune reads configuration from dune files written in S-expression syntax. These define build rules, dependencies, and targets. Dune then automatically handles compilation, linking, and environment setup, simplifying development workflows.

---

## 💪 Strengths

Composable Architecture – Combine multiple OCaml projects into one unified build system.

Multi-Package Support – Manage multiple packages with correct dependency resolution.

Reproducibility – Ensure consistent builds across environments.

Performance – Fast builds with parallel execution and minimal overhead.

Developer Productivity – Reduce manual setup through automation and standardization.

---

## 🛠️ Installation & Setup

Prerequisites:

* OCaml (>= 4.02.3)
* opam
* Dune

Install Dune:
opam install dune

Initialize environment:
eval $(opam config env)

---

## ▶️ Usage

Build project:
dune build

Run executable:
dune exec ./your_executable

Clean build:
dune clean

---



---

## 👩‍💻 Author

Vidhi Hemal Doshi
[https://github.com/doshividhi](https://github.com/doshividhi)

---

## 📄 License

This project is for educational purposes.



