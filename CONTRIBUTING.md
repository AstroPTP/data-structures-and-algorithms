# 🏆 Contributing

🎉 First of all , thank you for your interest in contributing to this project! 🎉  
This repository is a collection of **Data Structures and Algorithms (DSA)** implemented in different programming languages. Our goal is to build a resource that is useful for learners, interview prep, and developers everywhere.

### Table Of Contents

[Code of Conduct](#-code-of-conduct)  
[How Can I Contribute?](#-how-can-i-contribute)

-   [Your First Code Contribution](#your-first-code-contribution)
-   [Instructions](#instructions)
-   [Pull Requests](#pull-requests)

[Style Guidelines](#-style-guidelines)

-   [Git Commit Messages](#git-commit-messages)
-   [Documentation](#documentation)

## 📜 Code of Conduct

This project follows a **Code of Conduct** to ensure a welcoming environment for everyone

-   Be respectful and collaborative
-   Help others learn - this project is beginner-friendly
-   No discrimination, harrassment, or offensive behavior

See our [Code of Conduct](CODE_OF_CONDUCT.md) for more details

## 💻 How Can I Contribute?

### Your First Code Contribution

-   Pick an algorithm or data structure not yet implemented in your language of choice
-   Add an implementation in `src/`
-   Add a **demo** file so beginners can run it easily
-   (Optional but recommended) Add a **test** file so contributors and others can verify correctness
-   Run the code using instructions in the language's `README.md`

### Instructions

1.  **Fork the repo** to your GitHub account
2.  **Clone your fork** to your local machine:

```sh
git clone https://github.com/<your-username>/data-structures-and-algorithms.git
cd data-structures-and-algorithms
```

3. Create a new branch for your contribution:

```sh
git checkout -b <changes-type>/<changes-name>
```

Example:

```sh
git checkout -b feature/quick-sort-java
git checkout -b bugfix/linked-list-python
```

4. **Add your code**:

-   Navigate to the correct language folder(`java/`, `python/`, `cpp/`, etc.)
-   Each language folder has its own **README.md** with instructions on how to build and run code. Please check the file before contributing
-   Inside the folder, add your code to
    -   `src/` -> implementation
    -   `demos/` -> simple runnable examples (for new learners)
    -   `tests/` **(optional)** -> unit tests (JUnit, pytest, etc.) (for contributors)

### Pull Requests

-   Push your branch to your fork:

```sh
git push origin <branch-name>
```

Example:

```sh
git push origin feature/quick-sort-java
```

-   Go to your fork on **Github** and click **Compare & Pull Request**
-   For your Pull Request, please use the [PULL_REQUEST_TEMPLATES](PULL_REQUEST_TEMPLATE.md)

## ✨ Style Guidelines

### Git Commit Messages

-   Use clear and descriptive commit messages
-   Follow the convention:

```sh
<type>: <short summary>
```

#### Types you can use:

-   `feat` -> New implementation
-   `fix` -> Bug fix
-   `docs` -> Documentation changes
-   `test` -> Adding or modifying tests
-   `refactor` -> Code refactor without changing behavior

### Documentation

-   Add comments to your code explaining the algorithm/data structure
-   Keep functions and classes well-documented so beginners can follow along
-   Update the corresponding language `README.md` if new build/run instructions are needed
-   If you implement a new algorithm, add it to the language's list of supported algorithms in its README

---

😎💪 That's everything you need to know!! Thank you for contributing and helping this project grow
